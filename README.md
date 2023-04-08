# fake-ecommerce-site
This was a new project finished recently, However The JS is currently being fixed otherwise the HTML and CSS has been coded well and is working perfectly fine


//This was made using VS code, unfortanetley unable to directly upload the file here.
//HTML Script behind the site >>>>>>>>>>>>> Copy and paste onto IDE (VS CODE)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto+Slab&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
    <title>Simply Bags</title>
</head>
<body>
    <nav id="nav">
        <div class="navTop">
            <div class="navItem">
                <img src="images/logo .png" width="100px" height="100px" alt="">
            </div>
            <div class="navitem">
                <div class="search">
                    <input type="text" placeholder= "Search..." class="search">
                </div>
            </div>
            <div class="navitem">
                <span class="limitedOffer">Limited Offer!</span>
            </div>
        </div>
        <div class="navbottom">
            <h3 class="menuitem">PURSES</h3>
            <h3 class="menuitem">CLUTCHES</h3>
            <h3 class="menuitem">DESIGNER BAGS</h3>
            <h3 class="menuitem">CROSS BODY BAGS</h3>
            <h3 class="menuitem">TOTE BAGS</h3>
        </div>
    </nav>
    <div class="slider">
        <div class="sliderwrapper">
            <div class="slideritem">
                <img src="images/cross_body_bags-removebg-preview.png" alt="">
                <div class="sliderBG"></div>
                <h1 class="slidertitle">Shop Luxurious Purses</h1>
                <h2 class="sliderprice">£34.99</h2>
                <a href="#product">
                    <button class="buybutton">Buy Now</button>
                </a>
                
            </div>
            <div class="slideritem">
                <img src="images/clutches.png" alt="" class="sliderimage">
                <div class="sliderBG"></div>
                <h1 class="slidertitle">Shop Luxurious Clutches!</h1>
                <h2 class="sliderprice">£45.00</h2>
                <a href="#product">
                    <button class="buybutton">Buy Now</button>
                </a>
            
            </div>
            <div class="slideritem">
                <img src="images/designer_bags-removebg-preview.png" alt="" class="sliderimage">
                <div class="sliderBG"></div>
                <h1 class="slidertitle">Shop Luxurious Designer Bags</h1>
                <h2 class="sliderprice">£350.00</h2>
                <a href="#product">
                    <button class="buybutton">Buy Now</button>
                </a>
            </div>
            <div class="slideritem">
                <img src="images/purses.png" alt="" class="sliderimage">
                <div class="sliderBG"></div>
                <h1 class="slidertitle">Shop Luxurious Cross Body Bags</h1>
                <h2 class="sliderprice">£78.00</h2>
                <a href="#product">
                    <button class="buybutton">Buy Now</button>
                </a>
            </div>
            <div class="slideritem">
                <img src="images/tote_bags-removebg-preview.png" alt="" class="sliderimage">
                <div class="sliderBG"></div>
                <h1 class="slidertitle">Luxurious Tote Bags Available now</h1>
                <h2 class="sliderprice">£129.00</h2>
                <a href="#product">
                    <button class="buybutton">Buy Now</button>
                </a>
            </div>
        </div>
    </div>
    <div class="features">
        <div class="features">
            <img src="./images/shipping logo.png" alt="" class="featuresimage">
            <span class="featuretitle">FREE SHIPPING</span>
            <span class="featuredes">Free worldwild shipping + Redunds eligible.</span>
        </div>
        <div class="features">
            <img src="./images/contact logo.png" alt="" class="featuresimage">
            <span class="featuretitle">CONTACT US</span>
            <span class="featuredes">Call or Email us any questions/concerns you have, we are available 24/7.</span>
        </div>
        <div class="features">
            <img src="./images/discounts logo.png" alt="" class="featuresimage">
            <span class="featuretitle">DISCOUNTS/VOUCHERS</span>
            <span class="featuredes">Get a 10% discount after making your first purchase!, Check your emails and see if you have any vouchers or discounts.</span>
        </div>
    </div>
    <div class="product" id="product">
        <img src="images/cross_body_bags-removebg-preview.png" alt="" class="productimage">
        <div class="productdetails">
            <h1 class="producttitles">PURSES</h1>
            <h1 class="productprices">£34.99</h1>
            <p class="productdesc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita illo excepturi natus ad dignissimos dicta iste est inventore unde, optio rem, voluptatem sequi rerum quae doloribus pariatur dolor doloremque odit?</p>
            <div class="colors">
                <div class="color"></div>
                <div class="color"></div>
            </div>
            <button class="productButton">BUY NOW!</button>
        </div>
        <div class="payment">
            <h1 class="paytitle">Personal Information</h1>
            <label>Name and Surename</label>
            <input type="text" placeholder="John Doe" class="payinput">
            <label>Phone Number</label>
            <input type="text" placeholder="+44 756 675 238" class="payinput">
            <label>Address</label>
            <input type="text" placeholder="Elton St 21 22-145" class="payinput">
            <h1 class="paytitle">Card Information</h1>
            <div class="cardicons">
                <img src="images/visa png.png" alt="" width="40" class="cardicons">
                <img src="images/Mastercard-logo.png" alt="" width="40" class="cardicons">
            </div>
            <input type="password" class="payinputs" placeholder="Card Number">
            <div class="cardinfo">
                <input type="text" placeholder="mm" class="payinputs sm">
                <input type="text" placeholder="yyyy" class="payinputs sm">
                <input type="text" placeholder="cvv" class="payinputs sm">
            </div>
            <button class="payButton">Checkout</button>
            <span class="close">X</span>
        </div>
        <div class="newseason">
            <div class="nsitem">
                <img src="./images/new szn1.png" alt="" class="nsimage">  
            </div>
            <div class="nsitem">
                <h3 class="nstitlesm">NEW ARRIVALS!</h3>
                <h1 class="nstitle">New Collection</h1>
                <a href="#nav">
                    <button class="nsbutton">TAKE A LOOK</button>
                </a>
            </div>
            <div class="newseason">
                <div class="nsitem">
                    <img src="./images/new szn 2.png" alt="" class="nsimage">  
        </div>
        </div>


        <footer>
            <div class="footerleft">
                <div class="footermenu">
                    <h1 class="fmtitle">About Us</h1>
                    <ul class="fmlist">
                        <li class="footerlistitem">Company</li>
                        <li class="footerlistitem">Contact</li>
                    </ul>
                </div>
                <div class="footermenu">
                    <h1 class="fmtitle">Useful Links</h1>
                    <ul class="fmlist">
                        <li class="footerlistitem">Refunds</li>
                        <li class="footerlistitem">FeedBack</li>
                    </ul>
                </div>
                <div class="footermenu">
                    <h1 class="fmtitle">Products</h1>
                    <ul class="fmlist">
                        <li class="footerlistitem">Purses</li>
                        <li class="footerlistitem">Clutches</li>
                        <li class="footerlistitem">Designer Bags</li>
                        <li class="footerlistitem">Cross Body Bags</li>
                        <li class="footerlistitem">Tote Bags</li>
                    </ul>
                </div>
            </div>
        </footer>
    </div>
     <script src="app.js"></script>
</body>
</html>
    
    
    
    
    
    
    
    
//The JavaScript Used Behind This site >>>>>>>>>>>> Copy and paste onto IDE:
    
const wrapper = document.querySelector(".sliderwrapper")
const menuitem = document.querySelectorAll(".menuitem")

const products = [
    {
        id: 1,
        title: "Purses",
        price: 34.99
        colors: [
            {
                code: "red",
                image: "./image/purses.png",
            },
            {
                code: "#fbdfdf",
                image: "./image/purses.png",
            },
        ],
    },
    {
        id: 2
        title: "Clutches"
        price: 45.00
        colors: [
            {
                code: "Black"
                image: "./image/clutches.png",
            },
        ],
    },
    {
        id: 3,
        title: "Designer Bags",
        price: 350.00,
    },
{
    id: 4,
    title: "CrossBody Bags",
    price: 78.00
    colors: [
        {
            code: "black",
            image: "./image/cross_body_bags-removebg-preview.png",
        },
        {
            code: "darkblue",
            image: "./image/cross_body_bags-removebg-preview.png"
        },
    ],
},
{
    id: 5,
    title: "Tote bags",
    price: 129.00
    colors: [
        {
            code: "black",
            image: "./image/tote_bags-removebg-preview.png",
        },
        {
            code: "silver",
            image: "./image/tote_bags-removebg-preview.png"
        },
    ],
},
];

 let chosenProduct = products[0]

 const currentProductimg = document.querySelector(".productimage");
 const currentProductTitle = document.querySelector(".producttitles");
 const currentProductPrice = document.querySelector(".productprices");
 const currentProductColors = document.querySelectorAll(".colors");


menuitem.forEach((item, index) => {
    item.addEventListener("click", () => {
        //change the current slide

        wrapper.style.transform = 'translateX(${-100 * index}vw)';
        //change the chosen product

        chosenProduct = products[index]
        //change texts of currentProduct
        currentProductTitle.textContent = chosenProduct.title;
        currentProductPrice.textContent = "£" + chosenProduct.price;
        currentProductimg.src = chosenProduct.colors[0].image;

        //assinging new colors
        currentProductColors.forEach((color, index) => {
            color.style.backroundColor = chosenProduct.colors[index].code;

        });
    
    });
});


currentProductColors.forEach((color, index) => {
    color.addEventListener("click", () => {
        currentProductimg.src = chosenProduct.colors[index].image;

    });
});

const productButton = document.querySelector(".productButton");
const payment = document.querySelector(".payment");
const close = document.querySelector(".close");

productButton.addEventListener("click", () => {
    payment.style.display = "flex";
});

close.addEventListener("click", () => {
    payment.style.display = "none";
});
    
    
    
    
    
    
    
    

    
 //The CSS Code Behind The Site>>>>>>>>>>> Copy and paste onto IDE:
    
 html{
    scroll-behavior: smooth;
}


body{
    font-family: 'Roboto Slab', serif;
    padding: 0;
    margin: 0;
}

nav{
    background-color: #474747;
    color: white;
    padding: 20px 50px;
}

.navTop{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.search{
    display: flex;
    align-items: center;
    padding: 10px 20px;
    border-radius: 10px;
}

.limitedOffer {
    font-size: 20px;
    cursor: pointer;
}

.navbottom{
    display: flex;
    align-items: center;
    justify-content: center;

}

.menuitem{
    margin-right: 50px;
    cursor: pointer;

}

.slider{
    background-color: white;
    
}

.sliderwrapper{
    display: flex;
    width: 500vw;
    transition: all 1s ease-in-out;
}

.slideritem{
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}




.slidertitle{
    position: absolute;
    top: 10%;
    right: 10%;
    color:white;
    font-size: 35px;

}

.sliderprice{
    position: absolute;
    top: 10%;
    left: 10%;
    font-weight: 300;
    color: white;
    font-size: 40px;
    border: 1px solid white;

}

.buybutton{
    position: absolute;
    top: 50%;
    right: 10%;
    font-weight: 900;
    color: white;
    cursor: pointer;
    background-color: red;
    font-size: 30px;
    border: 1px solid red;
}

.buybutton:hover{
    background-color: #fa7a7a;
    color: white;
    border-color: #fa7a7a;
}

.slideritem:nth-child(1){
    background-color: #9a9797;
}

.slideritem:nth-child(3){
    background-color: #9a9797;
}

.slideritem:nth-child(5){
    background-color: #9a9797;
}

.features{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 50px;
}

.features{
    align-items: center;
    text-align: center;
    display: flex;
}

.featuresimage{
    width: 50px;
    height: 50px;
}

.featuretitle{
    color: #474747;
    font-size: 20px;
    font-weight: 600;
    margin: 20px;
}

.featuredes{
    flex-direction: column;
    width: 50%;
}

.product{
    height: 100vh;
    background-color: #9a9797;
    position: relative;
}

.payment{
    width: 500px;
    height: 500px;
    background-color: white;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    padding: 10px 50px;
    display: none;
    flex-direction: column;
    -webkit-box-shadow: -5px 4px 13px 2px black;
    -moz-box-shadow: -5px 4px 13px 2px black;
    box-shadow: -5px 4px 13px 2px rgba(12, 12, 12, 0.65);
}

.paytitle{
    font-size: 20px;
    color: rgb(99, 99, 99);
}

label{
    font-size: 15px;
    font-weight: 300;
}

.payinput{
    padding: 10px;
    margin: 10px 0px;
    border: none;
    border-bottom: 1px solid gray;
}

.payinput::placeholder{
    color: rgb(126, 125, 125);
}

.cardicons{
    display: flex;
}

.cardicons{
    margin-right: 10px;
}

.cardinfo{
    display: flex;
    justify-content: space-between;

}

.sm{
    width: 30px;
}

.payButton{
    position: absolute;
    height: 40px;
    bottom: -40px;
    width: 100%;
    left: 0;
    -webkit-box-shadow: -5px 4px 13px 2px black;
    -moz-box-shadow: -5px 4px 13px 2px black;
    box-shadow: -5px 4px 13px 2px rgba(12, 12, 12, 0.65);
    background-color: green;
    color: white;
    border: none;
    cursor: pointer;
}

.payButton:hover{
    background-color: rgb(13, 172, 13);
}

.close{
    width: 20px;
    height: 20px;
    position: absolute;
    background-color: gray;
    color: white;
    top: 10px;
    right: 10px;
    display: flex;
    justify-content: center;
    text-align: center;
    cursor: pointer;
    padding: 2px;
}

.productimage{
    width: 50%;
}

.productdetails{
    position: absolute;
    top: 10%;
    right: 0;
    width: 40%;
    padding: 50px;
    color: white;
}

.producttitles{
    font-size: 75px;
    font-weight: 900;
}

.productdesc{
    font-style: 24px;
    color: white;
}

.colors,.sizes{
    display: flex;
}

.color{
    width: 32px;
    height: 32px;
    border-radius: 5px;
    background-color: red;
    margin-right: 10px;
    cursor: pointer;
}

.color:last-child{
    background-color: #fbdfdf;
}

.productButton{
    float: right;
    padding: 10px 20px;
    background-color: red;
    color: white;
    border-color: red;
    font-weight: 600;
    cursor: pointer;
}

.productButton:hover{
    background-color: #fa7a7a;
    color: white;
    border-color: #fa7a7a;
}

.gallery{
    padding: 50px;
    display: flex;
}

.galleryimage{
    width: 100%;
}

.galleryitem{
    flex: 1;
    padding: 50px;
}

.newseason{
    display: flex;
}

.nsitem{
    flex: 1;
    background-color: rgb(50, 49, 49);
    color: white;
    align-items: center;
    justify-content: center;
    text-align: center;
    flex-direction: column;
}

.nstitle{
    font-size: 40px;
}

.nsbutton{
    padding: 15px;
    font-weight: 600;
    cursor: pointer;
}

.fmtitle{
    font-size: 16px;
    color: white;
}

.footerlistitem{
    margin-bottom: 10px;
    color: rgb(180, 158, 158);
    cursor: pointer;

}

footer{
    background-color: #474747;
}
@media screen and (max-width:480px) {
    nav{
        padding: 20px;
    }

    .search{
        display: none;
    }
    
    .navbottom{
        flex-wrap: wrap;
    }

    .sliderimage{
        width: 80%;
    }

    .sliderBG{
        width: 100%;
        height: 100%;
    }

    .slidertitle{
        display: none;

    }

    .sliderprice{
        top: unset;
        bottom: 0;
        left: 0;
        background-color: #ffffff;
        color: #ef8c8c;
    }

    .menuitem{
        margin: 20px;
        font-weight: 700;
        font-size: 20px;
    }

    .buybutton{
        right: 0;
        top: 0;
    }

    .features{
        flex-direction: column;
    }

    .product{
        display: flex;
        flex-direction: column;
        align-items: center;
        
    }

    .productdetails{
        width: 100%;
        padding: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        position: relative;
        top: 0;
    }

    .producttitles{
        font-size: 50px;
        margin: 0;
    }

    .newseason{
        flex-direction: column;
    }

    .nsitem{
        text-align: center;
    }

    .nstitlesm{
        text-align: center;
    }

    footer{
        display: none;
    }

    .payment{
        width: 90%;
        padding: 20px;
    }

}
    


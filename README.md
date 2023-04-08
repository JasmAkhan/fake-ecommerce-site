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


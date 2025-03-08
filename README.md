# Sample Pet Shop Site

### HTML

```html
﻿<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="utf-8" />
    <title>Pet Shop</title>
    <link rel="icon" type="image/png"
     href="images/favicon.png" />
    <link href="global.css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Anton,Open+Sans" rel="stylesheet" />
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <script src=""C:\Users\nshan\source\repos\PetShop\app.js""></script>
    <script src=""C:\Users\nshan\source\repos\PetShop\home.js""></script>
</head>
<body>
    <div id="promo" >
        <div>Free shipping</div>
        <div style="display:none;">New toys for puppies</div>
        <div style="display:none;">Buy 5 toys and save 30%</div>
        <div style="display:none;">Same day dispatch</div>
    </div>
    <div id="topMenu" >
        <div class="wrap">
            <div id="topLinks">
                <ul>
                    <li>
                        <a href="/">Home</a>
                    </li>
                    <li>
                        <a href="/">About</a>
                    </li>
                    <li>
                        <a href="/">Shop</a>
                    </li>
                    <li>
                        <a href="/">Contact</a>
                    </li>
                </ul>
            </div>
            <a class="logo" href="/">PET SHOP</a>
        </div>
    </div>
    <div>
        <div class="wrap">
            <div id="banner">
                <h1 class="logo">PET SHOP</h1>
                <div id="action">
                    <a href="/Shop">SHOP NOW</a>
                </div>
            </div>
        </div>
    </div>
    <div class="clear spacer v80"></div>
    <div id="fishFeature" class="feature">
        <div class="leftColumn">
            <div class="text">
                <h2>LOVE FISH</h2>
                <div class="subHeading">THE WIDEST RANGE OF FISH</div>
                <hr />
                <p>Indoor and outdoor, we've got them all!</p>
                <div class="spacer v40"></div>
                <a href="">CLICK FOR FISH</a>
            </div>
        </div>
        <div class="rightColumn">
            <a class="featureInage" src="/Fish">
                <img src="images/fish_feature_1.jpg"/>
            </a>
        </div>
    </div>
    <div class="clear spacer v20"></div>
    <div id="fishImage" class="middleImage">
        <img src="images/fish_feature_2.jpg"/>
    </div>
    <div class="spacer v80"></div>
    <div id="dogFeature" class="feature">
        <div class="leftColumn">
            <a class="featureImage">
                <img src="images/dog_feature_1.jpg"/>
            </a>
        </div>
        <div class="rightColumn">
            <div class="text">
                <h2>HAPPY DOGS</h2>
                <div class="subHeading">EVERYTHING YOUR DOG
                NEEDS</div>
                <hr />
                <p>Make sure your pooch eats well and feels good
                with our range of doggie treats.</p>
                <div class="spacer v40"></div>
                <a href="">CLICK FOR DOGS</a>
            </div>
        </div>
        <div class="clear"></div>
        <div id="dogImage" class="middleImage">
            <img src="images/dog_feature_2.jpg" />
        </div>
    <div class="spacer v80"></div>
    </div>
    <div id="birdFeature" class="feature">
        <div class="leftColumn">
            <div class="text">
                <h2>BIRDY NUM NUMS</h2>
                <div class="subHeading">KEEP YOUR BIRDS
                CHIPPER</div>
                <hr />
                <p>Yummy snacks and feeders for every kind of bird.</p>
                <div class="spacer v40"></div>
                <a href="">CLICK FOR BIRDS</a>
            </div>
        </div>
        <div class="rightColumn">
            <a class="featureImage" src="/Bird">
                <img src="images/bird_feature.jpg" />
            </a>
        </div>
    </div>
    <div class="clear"></div>
    <div id="birdImage" class="middleImage">
        <img src="images/bird_feeder.jpg" />
    </div>
    <div id="scrollToTop" title="Scroll to top">
        <span>&uarr;</span>
    </div>
    <div class="clear spacer v40"></div>
    <div id="contacts" class="feature">
        <div class="leftColumn">
            <div class="text">
                <h2>CONTACT US</h2>
                <hr />
                <p>
                    TEL : 012-345-6789
                </p>
                <p>
                    EMAIL : <a href="mailto:INFO@PETSHOP.COM"
                    class="emailLink">INFO@PETSHOP.COM</a>
                </p>
                <p>
                    PET SHOP<br />
                    1450 Broadway<br />
                    NEW YORK, NY<br />
                    10018
                </p>
            </div>
        </div>
    </div>
        <div class="rightColumn">
        <iframe src="https://www.google.com/maps/place/1450+Broadway,+New+York,+NY+10018/@40.754695,-73.9889361,17z/data=!3m1!4b1!4m6!3m5!1s0x89c259ab2419ed09:0xb9f7694124a811f0!8m2!3d40.754691!4d-73.9863612!16s%2Fg%2F11b8yhy_p1?entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D"></iframe>
    </div>
    <div class="clear spacer v80"></div>
    <div id="subscribe">
        <h2>SUBSCRIBE TO OUR MAILING LIST</h2>
        <form action="/subscribe" method="post">
            <input name="email" type="text" placeholder="Enter your email address" />
            <input type="submit" value="Join Now" />
        </form>
    </div>
    <div id="footer">
        <ul>
            <li>
                <a href="/storeFinder">Store Finder</a>
            </li>
            <li>
                <a href="/shipping">Shipping</a>
            </li>
            <li>
                <a href="/FAQ">FAQ</a>
            </li>
        </ul>
    </div>
    <div id="copyright">
        <div>&copy; 2020 <span class="logo>"PET SHOP"></span>
        </div>
    </div>
</body>
</html>
```

### CSS

```css
﻿/*
    font-family:"Anton", cursive;
    font-family:"Open Sans", sans-serif;

    Text color : #333;
    
    Dark blue : #345995

    Light blue : #4392F1

    Red : #D72630;

    Yellow : #EAC435;

    Orange : #F46036;

*/
body {
    margin: 0;
    padding: 0;
    font-family: "Open Sans", sans-serif;
    font-size: 15px;
    background-color: white;
    color: #333;
}
.wrap {
    margin: 0 auto;
    padding: 0;
    width: 1000px;
}
h1, h2 {
    margin: 0;
    padding: 0;
    font-family: "Anton", cursive;
    font-weight: normal;
}
h1 {
    font-size: 110px;
}
h2 {
    font-size: 30px;
}
.spacer.v20 {
    height: 20px;
}
.spacer.v40 {
    height: 40px;
}
.spacer.v80 {
    height: 80px;
}
.clear {
    clear: both;
}
#promo,
#subscribe,
#footer {
    text-align: center;
    color: #fff;
    min-width: 1000px;
}
#promo {
    background-color: #F46036;
}
#promo > div {
    padding: 15px;
}
#topMenu {
    height: 60px;
}
#topLinks {
    float: right;
    padding-top: 20px;
}
#topLinks ul, 
#footer ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}
#topLinks li {
    float: left;
}
#topLinks li a {
    color: #333;
    text-align: center;
    padding: 16px;
    text-decoration: none;
    -webkit-transition: all 250ms ease-out;
    transition: all 250ms ease-out;
}
        #topLinks li a:hover {
            color: #4392F1;
            -webkit-transition: all 250ms ease-out;
            transition: all 250ms ease-out;
            text-decoration: underline;
        }
#topMenu .logo {
    float: left;
    padding-top: 13px;
    font-size: 24px;
    color: #333;
    text-decoration: none;
}
    #topMenu .logo:hover {
        color: #4392F1;
    }
.logo {
    font-family: "Anton", cursive;
}
#banner {
    background-image: url("./images/banner.jpg");
    background-repeat: no-repeat;
    background-position: center top;
    width: 100%;
    text-align: center;
    padding-top: 300px;
    color: #333;
}
#banner .logo {
    margin-top: 20px;
}
#banner #action {
    font-weight: bold;
    width: 200px;
    margin: 20px auto 0 auto;
}
    #banner #action a {
        -webkit-transition: all 250ms ease-out;
        transition: all 250ms ease-out;
        padding: 20px;
        color: white;
        text-decoration: none;
        border-radius: 30px;
        background-color: #4392F1
}
    #banner #action a:hover {
        -webkit-transition: all 250ms ease-out;
        transition: all 250ms ease-out;
        background-color: #F46036;
        padding: 20px 40px;
    }
.feature .leftColumn {
    width: 50%;
    float: left;
    text-align: center;
    }
.feature .rightColumn {
    margin-left: 50%;
    width: 50%;
    text-align: center;
    }
.feature .leftColumn .text,
.feature .rightColumn .text {
    padding: 80px 20px 20px 20px;
    min-height: 260px;
    }
.feature .leftColumn .text a,
.feature .rightColumn .text a {
   -webkit-transition: all 250ms ease-out;
    transition: all 250ms ease-out;
    padding: 20px;
    background-color: #4392F1;
    color: white;
    text-decoration: none;
    border-radius: 30px;
    }
        .feature .leftColumn .text a:hover,
        .feature .rightColumn .text a:hover {
            -webkit-transition: all 250ms ease-out;
            transition: all 250ms ease-out;
            background-color: #F46036;
            text-decoration: none;
            padding: 20px 40px;
    }
.feature hr {
    background-color: #333;
    height: 1px;
    border: 0;
    width: 50px;
    }
.featureImage img {
    width: 500px;
   }
.feature .leftColumn .text a.emailLink,
.feature .rightColumn .text a.emailLink {
    color: white;
    text-decoration: none;
    transition: none;
    padding: 10px;
    border: 0;
    background-color: #4392F1;
    }
        .feature .leftColumn .text a.emailLink:hover,
        .feature .rightColumn .text a.emailLink:hover {
            -webkit-transition: all 250ms ease-out;
            transition: all 250ms ease-out;
            background-color: #F46036;
            }
.middleImage {
    text-align: center;
}
    .middleImage img {
        max-width: 1000px;
    }
#scrollToTop {
    display: none;
    opacity: .5;
    background-color: #F46036;
    padding: 0 20px;
    color: white;
    width: 26px;
    font-size: 40px;
    line-height: 48px;
    position: fixed;
    right: 10px;
    bottom: 10px;
    border: 1px solid white;
    border-radius: 30px;
}
    #scrollToTop:hover {
        opacity: 1;
        -webkit-transition: all 250ms linear;
        transition: all 250ms linear;
        cursor: pointer;
    }
.contactMap {
    width: 100%;
    height: 400px;
}
#subscribe {
    background-color: #4392F1;
    height: 160px;
    padding-top: 40px;
}
    #subscribe h2 {
        margin: 15px 0 20px 0;
        color: white;
        font-size: 24px;
        font-family: "Open Sans", sans-serif;
        font-weight: bold;
    }
#subscribe input[type=text] {
    border: 0;
    width: 250px;
    height: 28px;
    font-size: 14px;
    padding: 0 10px;
    border-radius: 30px;
}
#subscribe input[type=submit] {
    border: 0;
    width: 80px;
    height: 30px;
    font-size: 14px;
    background-color: #345995;
    color: white;
    border-radius: 30px;
    -webkit-transition: all 500ms ease-out;
    transition: all 500ms ease-out;
    cursor: pointer;
}
    #subscribe input[type=submit]:hover {
        background-color: #F46036;
        -webkit-transition: all 250ms ease-out;
        transition: all 250ms ease-out;
    }
#footer {
    background-color: #F46036;
    height: 80px;
}
#footer ul {
    list-style-type: none;
    margin: 28px 0 0 0;
    padding: 0;
    overflow: hidden;
    display: inline-block;
}
  #footer li {
    float: left;
    }
#footer li a {
    color: white;
    text-align: center;
    padding: 20px;
    text-decoration: none;
    font-size: 18px;
    -webkit-transition: all 250ms linear;
    transition: all 250ms linear;
}
     #footer li a:hover {
         color: #333;
         -webkit-transition: all 250ms linear;
         transition: all 250ms linear;
     }
#copyright {
    text-align: center;
    background-color: #345995;
    color: white;
    height: 40px;
    padding-top: 18px;
    font-size: 16px;
}
    #copyright .logo {
        font-family: "Open Sans", sans-serif;
        font-weight: bold;
    }
```

### Javascript (Home)

```javascript
// JavaScript source code

function HomeIndex() {
    /* Properties */
    const heightFromTop = 300;
    /* Methods */
    this.initialiseScrollToTopButton = function () {
        /* Window Scroll Event Handler */
        $(window).scroll(function () {
            /* Show or Hide Scroll to Top button 
            based on scroll distsance */
            let verticalHeight = $(this).scrollTop();
            if (verticalHeight > heightFromTop) {
                $("#scrollToTop").fadeIn();
            } else {
                $("#scrollToTop").fadeOut();
            }
        }
    )};
    /* Scroll to Top Click Handler */
    $("#scrollToTop").click(function () {
        $("html, body").animate({ scrollTop: 0 }, "slow");
    });
}
$(document).ready(function () {
    /* Instantiate new Home class */
    app.homeIndex = new HomeIndex();
    /* Initialize the Scroll To Top Button */
    app.homeIndex.initialiseScrollToTopButton();
});
```

### Javascript (App)

```javascript
// JavaScript source code

let app = (function () {
    /* Properties */
    let websiteName = "Petshop";
    /* Methods */
    return {
        getWebsiteName: function () {
            return websiteName;
        }
    }
})();
```

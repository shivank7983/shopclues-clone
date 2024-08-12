# shopclues-clone
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shopclues</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    "
    <link rel="stylesheet" href="website1.css" />
  </head>
  <body>
    <header>
      <div class="menu">
        <a href="#" class="menu-item">Sell With Us</a>
        <span class="separator">|</span>
        <a href="#" class="menu-item">Contact Us</a>
      </div>
      <div id="head">
        <div class="logo">
          <a href="#"
            ><img src="Shopclues_logo.png" width="140" height="50" alt="Logo"
          /></a>
        </div>
        <div class="searchbar">
          <input type="text" placeholder="What is on your Mind today?" />
          <div class="btn1">Search</div>
        </div>
        <div class="Location1">
          <span>Share</span><a style="display: block" href="#">Location</a>
        </div>
        <div class="bell">
          <a href="#"><img src="Location_icon.png" alt="Location" /></a>
          <a href="#"><img src="Bell_Icon.png" alt="Bell" /></a>
          <a href="#"><img src="Favourties_icon.png" alt="Favourties" /></a>
          <a href="#"><img src="Cart_icon.png" alt="cart" /></a>
          <div>Sign In</div>
        </div>
      </div>
      <div id="head2">
        <img src="Blue_Icon.png" alt="Made in India" />
        <div class="nav-list">
          <ul class="list">
            <li>Mobile & More</li>
            <li>Men</li>
            <li>Women</li>
            <li>Home & Kitchen</li>
            <li>Appliances</li>
            <li>Sports & More</li>
            <li>Essentials</li>
            <li>Offers</li>
            <li>Global Shopping</li>
          </ul>
        </div>
      </div>
      <div class="bottom-menu">
        <ul>
          <li claas="one">Jaw Dropping Deals</li>
          <li>Refurbished Mobile</li>
          <li>Express Shopping</li>
          <li>Men's Clothing</li>
          <li>Women's Fashion</li>
          <li>Footwear</li>
          <li>Kitchen Dinning</li>
          <li>Audio & Headphones</li>
          <li>Bags & Luggage</li>
        </ul>
      </div>
    </header>

    <div class="promo-banner">
      <div class="promo-content">
        <div class="promo-left"></div>
        <div class="img"></div>
      </div>
      <div class="categories">
        <div class="categories-list">
          <div class="anchor-list">
            <a href="#" class="one">Independence Day Sale</a>
            <a href="#" class="two">Automotive Sale</a>
            <a href="#" class="three">Hyper Deals</a>
            <a href="#" class="four">Refurbished Smart Phones</a>
            <a href="#" class="five">Intel</a>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

**CSS code**
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

#head {
    height: 80px;
    display: flex;
    }

#head2 {
    height: 50px;
    background-color: #24A3B5;
}

.logo {
    padding-top: 17px;
    padding-left: 40px;
}

.searchbar {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 20px;
    padding-top: 10px;
    padding-left: 60px;
}

input {
    width: 530px;
    padding: 14px 70px;
    border: 1px solid #ddd;
    border-radius: 5px 0 0 5px;
    flex: 1;
    background-color: #e8f3f8;
}

input[type="text"]::placeholder {
    font-size: 18px;
}

input:focus {
    background-color: white;
    box-shadow: 0 4px 8px black
}

.btn1 {
    padding: 11px 25px;
    background-color: #f07f3e;
    border: none;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: white;
    font-size: 1.2rem;
    font-weight: bold;
}

.btn1:hover {
    background-color: #FF8E4D;
    cursor: pointer;
}
/* 
p {
    display: inline;
    padding-left: 20px;
} */

.Location1 {
    padding-left: 50px;
    padding-top: 25px;
}

.bell {
    padding-top: 25px;
}

.bell img {
    padding-left: 20px;
}

.bell div {
    display: inline;
    position: absolute;
    padding-top: 10px;
    padding-left: 20px;
}

.bell div:hover {
    cursor: pointer;
    text-decoration: underline;
}

.Location1 a {
    color: #24A3B5;
    text-decoration: none;
}

span {
    color: #000000;
}

.Location1 a:hover {
    text-decoration: underline #24a3b5;
}

.menu a {
    text-decoration: none;
    color: black;
    font-size: small;
}

.menu {
    padding-left: 1150px;
}

.menu a:hover {
    text-decoration: underline;
}

#head2 {
    display: flex;
    justify-content: center;
    align-items: center;
}

#head2 img {
    margin-right: 10px;
}

.list {
    list-style-type: none;
    display: flex;
    gap: 15px;
    padding: 0px;
    margin-top: 15px;
}

.list li {
    color: white;
    padding: 17px 13px;
}

.nav-list .list li:hover {
    background-color: #FFFFFF;
    color: #24A3B5;
    cursor: pointer;
}

.head3 {
    height: 40px;
    background-color: white;
    padding-top: 0%;
}

.bottom-menu {
    background-color: white;
}

.bottom-menu li {
    list-style-type: none;
    display: inline;
    margin-left: 35px;
    font-size: small;
    color: lightgrey;
    font-weight: bold;
}

.bottom-menu li:hover {
    color: #24A3B5;
    cursor: pointer;
}

.promo-banner {
    width: 1100px;
    height: 320px;
    padding-left: 65px;
}

.promo-content {
    height: 350px;
    width: 900px;
}

.promo-left {
    background-image: url("Fashion.jpg");
    background-size: cover;
    height: 350px;
    width: 1100px;  
}

.categories {
    display: flex;
    align-items: center;
    height: 64px;
    width: 1100x;
    border: 1px solid transparent;
    background-color: white;
    box-shadow: 0px 1px rgb(131, 126, 126);
}

.anchor-list a {
    padding-left: 80px;
    margin-top: 20px;
    text-decoration: none;
    color: #555555;
}

.anchor-list a:hover {
    color: #24A3B5;
    font-weight: bold;
}

.categories:hover {
    box-shadow: 0px 1px #24A3B5;
}

.container {
    display: flex;
}

.img {
    background-image: url("DIV.png");
    background-size: cover;
    height: 425px;
    width: 250px;
    position: relative;
    left: 1150px;
    bottom: 361px;
    padding: 1px 4px;
    box-shadow: 0px 1px #555555;
}

.promo-left:hover {
    background-image: url("Home_Essential.jpg");
    background-image: url("RefurbSmartphones.jpg");
}

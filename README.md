# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
<<<<<<< HEAD
Layout.css:
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}
=======
HOME PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/design.jpg" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY:E.DHARANI
      </div>
    </div>
  </body>
</html>
PRODUCT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/ajax.png" alt="product image">
                  </div>
                  <div class="itemname">AJAX</div>
                  <div class="itemprice">Price: Rs.25000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/angular.png"  alt="product image">
                  </div>
                  <div class="itemname">ANGULAR</div>
                  <div class="itemprice">Price: Rs.30000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/bootstrap.png"  alt="product image">
                </div>
                <div class="itemname">BOOTSTRAP</div>
                <div class="itemprice">Price: Rs.52500.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/ionic.png"  alt="product image">
            </div>
            <div class="itemname">IONIC</div>
            <div class="itemprice">Price: Rs.60000.00 </div>
          </div>  
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/joomla.png"  alt="product image">
            </div>
            <div class="itemname">JOOMLA</div>
            <div class="itemprice">Price: Rs.100.00 </div>      
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/js.png"  alt="product image">
        </div>
        <div class="itemname">JS</div>
        <div class="itemprice">Price: Rs.50000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/mysql.png"  alt="product image">
          </div>
          <div class="itemname">MYSQL</div>
          <div class="itemprice">Price: Rs.80000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/php.pngg"  alt="product image">
            </div>
            <div class="itemname">PHP</div>
            <div class="itemprice">Price: Rs.55000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/react.png"  alt="product image">
              </div>
              <div class="itemname">REACT</div>
              <div class="itemprice">Price: Rs.67000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/shopify.png"  alt="product image">
                </div>
                <div class="itemname">SHOPIFY</div>
                <div class="itemprice">Price: Rs.43000.00 </div>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/sqlite.png"  alt="product image">
                    </div>
                    <div class="itemname">SQLITE</div>
                    <div class="itemprice">Price: Rs.57000.00 </div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/wordpress.png"  alt="product image">
                      </div>
                      <div class="itemname">WORDPRESS</div>
                      <div class="itemprice">Price: Rs.60000.00 </div>
                      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E
      </div>
    </div>
  </body>
</html>
 PEOPLE PAGE:
    
      <!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>BEST COMPANIES IN INDIA </h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/b.png" alt="product image">
                    </div>
                    <div class="itemname">MR.JORDAN WALKE</div>
                    <div class="itemprice">CEO OF REACT</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/d.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.SCOTT LAKE</div>
                    <div class="itemprice">CEO OF SHOPIFY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/j.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.MATT MULLENWEG</div>
                    <div class="itemprice">CEO OF WORDPRESS</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/m.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.DWAYNE RICHARD HIPP</div>
                    <div class="itemprice">CEO OF SQLITE</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/r.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.RASMUS LERDORF</div>
                    <div class="itemprice">CEO OF PHP</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/s.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.BEN SPERRY</div>
                    <div class="itemprice">CEO OF IONIC</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E
      </div>
    </div>
  </body>
</html>
 CONTACT US:
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: BENGALURU <br></li>
              <li>Contact:7871232666;<br></li>
              <li>worldwidesoftwares@gmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E 
      </div>
    </div>
  </body>
</html>
>>>>>>> 78ecda1b81f2f1da520c9576a2155e97c74ec293

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/background.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

<<<<<<< HEAD
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
=======

>>>>>>> 78ecda1b81f2f1da520c9576a2155e97c74ec293

```
Home Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/design.jpg" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY:E.DHARANI
      </div>
    </div>
  </body>
</html>

```
Product Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/ajax.png" alt="product image">
                  </div>
                  <div class="itemname">AJAX</div>
                  <div class="itemprice">Price: Rs.25000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/angular.png"  alt="product image">
                  </div>
                  <div class="itemname">ANGULAR</div>
                  <div class="itemprice">Price: Rs.30000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/bootstrap.png"  alt="product image">
                </div>
                <div class="itemname">BOOTSTRAP</div>
                <div class="itemprice">Price: Rs.52500.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/ionic.png"  alt="product image">
            </div>
            <div class="itemname">IONIC</div>
            <div class="itemprice">Price: Rs.60000.00 </div>
          </div>  
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/joomla.png"  alt="product image">
            </div>
            <div class="itemname">JOOMLA</div>
            <div class="itemprice">Price: Rs.100.00 </div>      
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/js.png"  alt="product image">
        </div>
        <div class="itemname">JS</div>
        <div class="itemprice">Price: Rs.50000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/mysql.png"  alt="product image">
          </div>
          <div class="itemname">MYSQL</div>
          <div class="itemprice">Price: Rs.80000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/php.pngg"  alt="product image">
            </div>
            <div class="itemname">PHP</div>
            <div class="itemprice">Price: Rs.55000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/react.png"  alt="product image">
              </div>
              <div class="itemname">REACT</div>
              <div class="itemprice">Price: Rs.67000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/shopify.png"  alt="product image">
                </div>
                <div class="itemname">SHOPIFY</div>
                <div class="itemprice">Price: Rs.43000.00 </div>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/sqlite.png"  alt="product image">
                    </div>
                    <div class="itemname">SQLITE</div>
                    <div class="itemprice">Price: Rs.57000.00 </div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/wordpress.png"  alt="product image">
                      </div>
                      <div class="itemname">WORDPRESS</div>
                      <div class="itemprice">Price: Rs.60000.00 </div>
                      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E
      </div>
    </div>
  </body>
</html>

```
People Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>BEST COMPANIES IN INDIA </h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/b.png" alt="product image">
                    </div>
                    <div class="itemname">MR.JORDAN WALKE</div>
                    <div class="itemprice">CEO OF REACT</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/d.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.SCOTT LAKE</div>
                    <div class="itemprice">CEO OF SHOPIFY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/j.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.MATT MULLENWEG</div>
                    <div class="itemprice">CEO OF WORDPRESS</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/m.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.DWAYNE RICHARD HIPP</div>
                    <div class="itemprice">CEO OF SQLITE</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/r.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.RASMUS LERDORF</div>
                    <div class="itemprice">CEO OF PHP</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Elango/Documents/web/productcompanywebsite/companywebsite/static/img/s.png"  alt="product image">
                    </div>
                    <div class="itemname">MR.BEN SPERRY</div>
                    <div class="itemprice">CEO OF IONIC</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E
      </div>
    </div>
  </body>
</html>

```
Contact Us Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WORLD WIDE SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WORLD WIDE SOFTWARES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: BENGALURU <br></li>
              <li>Contact:7871232666;<br></li>
              <li>worldwidesoftwares@gmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 WORLD WIDE SOFTWARES DEVELOPED BY DHARANI.E 
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:

### Home Page:
![output](./ss1.png)
### Product Page:
![output](./ss2.png)
### People Page:
![output](./ss3.png)
### Contact Us Page:
![output](./ss4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

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

### CSS:
~~~
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

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("https://static.vecteezy.com/system/resources/thumbnails/003/471/376/small/nature-green-background-free-vector.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #bd28b0;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #dacd1c;
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
  color: #ddd013;
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
  font-size: larger;
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
  background-color: #c5c225;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Akrutha Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Akrutha Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
            At Akrutha Private Limited, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />

            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Akrutha products which make it simpler than ever
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
    </div>
      
      <div class="footer">
        Copyright &#169; 2021 Akrutha Private Limited, Developed by Vivekreddy.
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Akrutha Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Akrutha Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://www.reliancedigital.in/medias/Kelvinator-KWT-A800SG-Washing-Machines-491604437-i-1-1200Wx1200H?context=bWFzdGVyfGltYWdlc3w5NTYzMXxpbWFnZS9qcGVnfGltYWdlcy9oNjkvaGIyLzkzMzUxNDAzODQ3OTguanBnfGRmN2MyYzI5ZTYxZjgwYTNjYTczMjk5ODgxNzNkYjVhZDY3MjRkYTkyOGUxYTFkYjNmOTIxYzZhYzIwMzM4ODM" alt="product image">
                  </div>
                  <div class="itemname">kelvinator</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://www.lg.com/in/images/washing-machines/md07515049/gallery/FHM1208ZDL-Washing-Machines-Front-View-D-01.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Sliverfont</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.reliancedigital.in/medias/Samsung-WA70T4262BS-Washing-Machine-491891854-i-1-1200Wx1200H-300Wx300H?context=bWFzdGVyfGltYWdlc3wzNDg3OXxpbWFnZS9qcGVnfGltYWdlcy9oNTkvaDgwLzkzOTc1MDM0MjY1OTAuanBnfDllMDlkNTg4MjhlM2YzMzY0ZmI2YTc3ZWExOTI5ZDQxM2U0NTE0MTM3MGZjYThjN2RjMjYwOTI5Zjg4NTMzOWE"  alt="product image">
                </div>
                <div class="itemname">Samsung</div>
                <div class="itemprice">Price: Rs.20,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://5.imimg.com/data5/ER/RK/IX/SELLER-50856731/bosch-8-kg-washing-machine-500x500.jpg"  alt="product image">
              </div>
              <div class="itemname">Bosch</div>
              <div class="itemprice">Price: Rs.35,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQK3bh-F3Q8ZqRTJNKsCaegqnplvXvGQrh7uQ&usqp=CAU"  alt="product image">
            </div>
            <div class="itemname">IILOYD</div>
            <div class="itemprice">Price: Rs.15,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://adecuado.in/wp-content/uploads/2021/09/washing-machine.jpg"  alt="product image">
          </div>
          <div class="itemname">Sansui</div>
          <div class="itemprice">Price: Rs.25,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://www.sargam.in/media/catalog/product/cache/52c3474c27fbdcab744f9fdf13af4c52/1/_/1_4390.jpg"  alt="product image">
        </div>
        <div class="itemname">Haier</div>
        <div class="itemprice">Price: Rs.23000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://www.lg.com/in/images/washing-machines/md07518468/gallery/FHV1207ZWB-Washing-Machines-Right-View-D-06.jpg"  alt="product image">
      </div>
      <div class="itemname">IFB</div>
      <div class="itemprice">Price: Rs.55,000.00 </div>
  </div><div class="productitem"> 
    <div class="itemimage">
    <img src="https://s3.ap-south-1.amazonaws.com/brandbuddiez.com//10/img/product/5/291/Webp.net-resizeimage%20(3).jpg"  alt="product image">
    </div>
    <div class="itemname">ONIDA</div>
    <div class="itemprice">Price: Rs.40,000.00 </div>
</div><div class="productitem"> 
  <div class="itemimage">
  <img src="https://www.smeg.com/binaries/content/gallery/smeg/categories/washing_machines_smeg_wht1114lsin_4.jpg/washing_machines_smeg_wht1114lsin_4.jpg/brx%3AsquareMobile"  alt="product image">
  </div>
  <div class="itemname">Bluestar</div>
  <div class="itemprice">Price: Rs.25,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://images.thdstatic.com/productImages/7ded176b-b894-4567-a6bc-5444715ffcac/svn/white-frigidaire-top-load-washers-fftw4120sw-64_600.jpg"  alt="product image">
  </div>
  <div class="itemname">Whirlpool</div>
  <div class="itemprice">Price: Rs.23,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://s3.ap-south-1.amazonaws.com/brandbuddiez.com//10/img/product/9/193/WS_EDGE_CLASSIC-01.jpg"  alt="product image">
  </div>
  <div class="itemname">LG</div>
  <div class="itemprice">Price: Rs.20,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Akrutha Private Limited, Developed by Vivekreddy.
      </div>
    </div>
  </body>
</html>
~~~

### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Akrutha Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Akrutha Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Founders</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://pbs.twimg.com/profile_images/1189494401359208448/AwbXHtpn_400x400.jpg" alt="product image">
                  </div>
                  <div class="itemname">Ratan Tata</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://www.wired.com/wp-content/uploads/2019/01/Culture_GeeksGuide_Bezos.jpg"  alt="product image">
                  </div>
                  <div class="itemname">JEFF BEZOS</div>
                  <div class="itemprice">Manager</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://image.cnbcfm.com/api/v1/image/104225995-_95A5004.jpg?v=1540458420&w=929&h=523"  alt="product image">
                </div>
                <div class="itemname">Jack Ma</div>
                <div class="itemprice">Technical lead</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="https://d2wpuh174c3iwv.cloudfront.net/resize?url=https%3A%2F%2Fs3.amazonaws.com%2Fcco-avatars%2Fcfd92dc8-ab27-497d-852a-39298fb56fff.png&width=340&height=340"  alt="product image">
                    </div>
                    <div class="itemname">Manan Shah</div>
                    <div class="itemprice">CTO</div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="https://media.architecturaldigest.com/photos/60e71db5ab269c67afc7e283/3:4/w_1500,h_2000,c_limit/GettyImages-1215628293.jpg"  alt="product image">
                        </div>
                        <div class="itemname">Elon musk</div>
                        <div class="itemprice">CIO</div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Mark_Zuckerberg_F8_2019_Keynote_%2832830578717%29_%28cropped%29.jpg"  alt="product image">
                            </div>
                            <div class="itemname">Mark Zuckerberg</div>
                            <div class="itemprice">VP of Marketing</div>
                            </div>
                
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Akrutha Private Limited, Developed by Vivekreddy.
      </div>
    </div>
  </body>
</html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Akrutha Private Limited</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Akrutha Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>CONTACT US</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
           
            <ul>
              <li>You can contact us online using our customer care.</li>
              <li>you can contact us through online by using our gmail id-Akuruthatechnical@gmail.com for technical support.</li>
              <li>You can contact us by call to the number +1468634823 </li>
              <li>Contact us at Hi-mark road,gandhi nagar,Vizag.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Akrutha Private Limited, Developed by Vivekreddy.
      </div>
    </div>
  </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./home.png)

### Product Page:

![output](./product1.png)
![output](./product2.png)

### People Page:

![output](./people.png)

### Contact Us Page:

![output](./contactus.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

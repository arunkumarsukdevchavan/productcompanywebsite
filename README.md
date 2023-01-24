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
### home.html:
```python
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("https://www.slideegg.com/image/header.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  background-image: url(https://png.pngtree.com/thumb_back/fh260/background/20200714/pngtree-modern-double-color-futuristic-neon-background-image_351866.jpg);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>




<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="https://cdn1.vectorstock.com/i/1000x1000/63/95/modern-letter-wf-logo-design-wf-logo-design-vector-37446395.jpg" border-color="yellow" alt="logo" />
          <div class="contenttext">
            Wind Free Technologies, (known as WINDFREE) is an Indian multinational cybersecurity software company, 
            headquartered in Pune, Maharashtra, India. The company was formerly known as CAT Computer Services (P) Ltd and was started as a computer service centre in 1995. 
            The company was renamed as WindFree Technologies Pvt. Ltd. in 2007.
            The company develops security software for consumers, servers, cloud computing environments and small and medium enterprises and sells products directly to customers or through its partner channel.
            Its enterprise product offerings operate under the brand name Seqrite.
            The companies products are regularly tested with features and abilities compared against other similar products.
            Wind Free develops its own security suite and leverages a combination of signature-based and signatureless detection technologies to detect and block known and unknown threats in real-time.

            <br />
            <ul>
              <li>Wind Gives Security</li>
              <li>Cloud-Based AI-Powered</li>
              <li>Wind Free is a great antivirus. </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By ARUN KUMAR SUKDEV CHAVAN
      </div>
    </div>
  </body>
</html>
```
### products.html:
```python
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  mar
  gin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("https://wallpaperaccess.com/full/1583366.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  background-image: url(https://images.unsplash.com/photo-1598760122223-45f0f18a1bbd?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8Mnx8fGVufDB8fHx8&w=1000&q=80);
  min-height: 480px;
  margin: 0px 0px 0px 0px;
  border-width: 50px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="https://i.pinimg.com/236x/9f/8d/8b/9f8d8b469239ca820151fefb238fbc31.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1 class="hrr">Our Quick Heal Series Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/41zA+vBp6kL.jpg" alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Total Security</div>
                  <div class="itemprice">Price: Rs. 1,499.00  </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://megacompuworldjaipur.com/image/cache/catalog/Product/Software/INTERNET%20SECURITY-800x500.png"  alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Internet Security</div>
                  <div class="itemprice">Price: Rs.1,199.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://e7.pngegg.com/pngimages/1022/699/png-clipart-laptop-antivirus-software-quick-heal-computer-virus-computer-software-laptop-electronics-computer.png"  alt="product image">
                </div>
                <div class="itemname">Quick Heal AntiVirus Pro</div>
                <div class="itemprice">Price:Rs.879.00  </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.muzaffarpureshop.com/wp-content/uploads/2019/03/festival_pack_300x300.png"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security Festive Pack</div>
                <div class="itemprice">Price: Rs.2,009.00</div>
              </div><div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://cdn.shopify.com/s/files/1/0564/3006/7870/products/qucik1_grande.jpg?v=1670233942"  alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Internet Security Essentials</div>
                  <div class="itemprice">Price: Rs.3,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="data:image/jpeg;base64,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"  alt="product image">
                </div>
                <div class="itemname">Quick Heal AntiVirus for Server</div>
                <div class="itemprice">Price: Rs.1,890 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/31vZFwxCCVL._SR600%2C315_PIWhiteStrip%2CBottomLeft%2C0%2C35_SCLZZZZZZZ_FMpng_BG255%2C255%2C255.jpg"  alt="product image">
                </div>
                <div class="itemname">Quick Heal PCTuner 3.0</div>
                <div class="itemprice">Price:Rs.499 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://ittouch.in/wp-content/uploads/2022/01/queak-heal-multy-250x250.jpg"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security Multi-Device</div>
                <div class="itemprice">Price: Rs.2,199 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQSq-mcSm9NA57NxojSFOJXyBEHPfKIjjR3HQ&usqp=CAU"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Mobile Security</div>
                <div class="itemprice">Free </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.quickheal.com/media/catalog/product/cache/1/image/254x315/9df78eab33525d08d6e5fb8d27136e95/q/h/qhtsa-254-315.png"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security for Android</div>
                <div class="itemprice">Price: Rs.199.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://buyantivirus.co.in/wp-content/uploads/2020/03/quickheal-total-security-for-mac.png"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security for Mac</div>
                <div class="itemprice">Price: 1,549.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/51Ctm2GcNcL._SX300_SY300_QL70_ML2_.jpg"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Internet Security</div>
                <div class="itemprice">Price: Rs.2,500</div>
             </div>
          </div>
          </div>        
          
        
      <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By ARUN KUMAR SUKDEV CHAVAN
      </div>
    </div>
  </body>
</html>
```

### people.html:
```python
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("https://s3.envato.com/files/344830.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  background-image: url(https://i.pinimg.com/originals/4f/6d/05/4f6d052bb1b26150115888ea06d4c106.jpg);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="https://s3.envato.com/files/344830.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1>Our Crew Memebers</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://res.cloudinary.com/dt84tw7zr/image/fetch/f_auto,g_auto,q_auto/https://www.gameplan-a.com/wp-content/uploads/fly-images/6856/Rohit-Sharma-adidas-cricket-mindset-captain-Whats-Your-Gameplan-1440x9999.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">Brat Robinson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://i.pinimg.com/originals/6e/9a/e1/6e9ae1845574fef81976c025aa3a7a03.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer9</div>
                            <div class="itemprice">Chandramohan</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://i.pinimg.com/736x/0e/22/62/0e2262935ae2a1bbbee8397da500edcd.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">Tony Willson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://i.pinimg.com/736x/15/ef/27/15ef275514204107818ace85ec6ff8b1.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">Samuel Jackson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://www.csdscricketacademy.org/images/kapildev.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Niharika</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3itZ5nNqwog1oY-_5eWqJfnA-5_LaYuRZeA&usqp=CAU" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">Sam Ketteson</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By ARUN KUMAR SUKDEV CHAVAN
      </div>
    </div>
  </body>
</html>
```
### contactus.html:
```python
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("https://media.istockphoto.com/id/1289085646/vector/holiday-abstract-shiny-color-gold-design-element.jpg?s=612x612&w=0&k=20&c=KxxPq3pjtgny0SHSF8BLyX1RnxHRa3KmW1fVFn9L2xc=");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  background-image: url(https://img.freepik.com/free-vector/gradient-black-backgrounds-with-golden-frames_23-2149150610.jpg);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          <div class="us">
              <h1>
                  <u>Contact Us</u>
                </h1>
                <h2>For Enquiry</h2>
                        <h3>EMAIL : windfreeprivatelimited@gmail.com</h3>
                        <h3>NUMBER: +91 9361199777,+91 8535647625</h3>
                        <h3>ADDRESS: 12B,Windfree,Pune,Maharastra.</h3>
                        <h3>WEBSITE: Windfree.com</h3>
          </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By ARUN KUMAR SUKDEV CHAVAN
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](/hp.png)

### Product Page:
![output](/ph.png)

### People Page:
![output](/pep.png)

### Contactus Page:
![output](/ch.png)

## HTML VALIDATOR:
![output](/htmlv.png)
![output](/htmlv1.png)
![output](/html2.png)
![output](/html3.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

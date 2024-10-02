<!DOCTYPE html>
<!--
Created using JS Bin
http://jsbin.com

Copyright (c) 2024 by molliesmom (http://jsbin.com/fufawab/1/edit)

Released under the MIT license: http://jsbin.mit-license.org
-->
<meta name="robots" content="noindex">
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
<style id="jsbin-css">
body{
  background: #FFFFFF;
  font-family: 'Abel', sans-serif;
  font-size: 20px;
  color: #3B3B3B;
}

h1, h2{
  font-family: "chalkduster";
  font-weight: normal;
  text-transform: uppercase;
  margin: 0;
  padding: 0;
  color: #111111;
}

#logo h1{
  line-height: 150px; 
  letter-spacing: 3px;
  font-size: 3em;
}

#header-page{
  overflow: hidden;
  height = 600px;
    
}

#header{
  overflow: hidden;
  width: 1000px;
  height: 150px;
  margin: 0 auto;
  padding: 0px, 0px
}
#banner{
  margin: 0px auto;
  width: 1000px; 
  height: 450px;
}

#threeColumns{
  overflow:hidden;
  width:  1000px;
  margin: 0px auto;
  padding: 30px 0px;
  
}
img{
  width: 1000px;
}

#threeColumns h2{
  padding: 0px 09px 20 px 0px; 
  font-size: 30px;
}
#threeColumns #column1{
  float: left; 
  width: 300px;
  margin-right: 50px;
}
#threeColumns #column2{
  float: left; 
  width: 300px;
  
}
#threeColumns #column3{
  float: right; 
  width: 300px;
 
}

</style>
</head>
<body>
  <div id="page">
    <div id="header-page">
      <div id="header" class = "container">
        <div id="logo">
          <h1>Tootsie Cat Bakery</h1>
        </div>
      </div>
        <div id = "banner">
        <div class="content">
          <img src="https://as1.ftcdn.net/v2/jpg/01/77/50/84/1000_F_177508414_lbpY3DGDO6meHeEDib2pDrQUJEOJGvyr.jpg"/>
      </div>
      </div>
     </div>
    <div id = "threeColumns">
    <div id= "column1">
      <h2>Small Batch Baking</h2>
      <p>We do small batches of breads and sweets!  Each batch is baked fresh from ingredients you know and can pronounce.</p>
      </div>
      <div id= "column2">
      <h2>Column 2</h2>
      <p>This is a paragraph</p>
      </div>
      <div id= "column3">
      <h2>Column 3</h2>
      <p>This is a paragraph</p>
      </div>
     </div>
  </div>
</body>
</html>

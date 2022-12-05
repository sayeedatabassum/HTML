# HTML
<!DOCTYPE html>
<html>
  <head>
    <title>
      salam
    </title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="https://i.pinimg.com/736x/2c/f6/08/2cf6089a48a31545aca38c9d83e8058d.jpg">
  </head>
  
  <body>
    <p>hey ya</p>

    <h1>hi</h1>
    
    <form action="form.html" method="POST" >

      
      <label for="username">Name</label>
      <input type="text" name="username" id="username">
      <br><br>
      <label for="username2">Suga</label>
      <input type="checkbox" name="username2" id="username2" value="suga">
      <label for="username3">jungkookk</label>
      <input type="radio" name="username3" id="username3" value="jungkook">
      <input type="submit" value="send">
    </form>
    
    <p>hi there &euro; &#9827;</p>

    
    <iframe src="https://google.com" style="border=none;" height="100" width="100"></iframe>
    <div style="color:green; background-color: blue;">
      <h1>first div</h1>
      <b>this is bold</b>
    </div>

      <div style="color:yellow; background-color: purple;">
      <h1>second div</h1>
      <b>this is bold</b>
    </div>
    
    table
    <table>
      <tr>
        <th>
          NAME
        </th>
        <Th>
          Age
        </Th>
        <th>
          Major
        </th>
        <th>
          Color
        </th>
      </tr>
      <tr>
        <td>RM</td>
        <td>28</td>
        <td>Rap Monster</td>
        <td>blue,pink</td>
      </tr>
    </table>
unordered list
    <ul>
      <li>Name 1</li>
      <li>Name 2</li>
      <li>Name 3</li>
    </ul>
  ordered list
     <ol>
      <li>Name 1</li>
      <li>Name 2</li>
      <li>Name 3</li>
    </ol>
name1
    description
    <dl>
      <dt>Leader</dt>
      <dd>this is RM</dd>
        <dt>
          second person
        </dt>
      <dd>j-hope</dd>
        <dd></dd>
    </dl>

    
    <a href="mailto:sayeedatabassum96@gmail.com">send me an email</a><br>
  <a href = "https://google.com" target="_blank">Go to site</a>    <!-- the code below displays heading-->
    <h1 id = welcome style = "color:teal; background-color:yellow">First heading</h1>
    <h2>Second heading</h2>
    <h3>Third heading</h3>
  <!--
    <pre>
      <strong>
        my you
      </strong>
      <hr>
      <i>stay alive</i>
      <hr>
      <em>
        that that i like that
      </em>
      <hr>
      <b>wild flower</b>
      <hr>
      <sup>
        christmas tree
      </sup>
      <hr>
      <mark>my universe</mark>
      <hr>
      don't <del>hate</del> yourself
      <hr>
      always <ins>love</ins> yourself
      <hr>
      be like a <small>diamond</small> in the sky.
      <hr>
      7BTS<sup>1Army</sup>
      <hr>
    </pre>
  -->  
    

    <img src = "https://w0.peakpx.com/wallpaper/147/311/HD-wallpaper-bts-jungkook-bangtan-bangtan-sonyeondan-bts-bulletproof-boys-jeon-jungkook-jeon-jungkook-jungkook-jungkookie-thumbnail.jpg" height="300" width="200">
    
  </body>
</html>

#css
/* changes the background color of body */

/* body {
/*  background-image:url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTaRpospntiwzpP-PFY2iEoPIU1Val0t2s5kWsdLEHcutG9212JW6e2iPzrF25VTlIz_24&usqp=CAUg") */
/*  background-position:right; */


p {
  border-color:purple greenyellow tomato lightgoldenrodyellow;
/*   margin:50px 50px 50px 50px;  */
/*   margin-right: 300px;*/
/*   border-style:solid; */
  border-width: 10px 5px;
  border-style:solid;
/*   border-style:dashed double dotted solid; */
}

h1 {
  border-style:solid orange;
  color:seagreen;
/*   background-color:green; */
  opacity:0.9;
  border-radius:20px;
  border-left:solid;
/*   padding-top:40px;
  padding-bottom:40px; */
/*   padding-left:40px;
  padding-right:40px; */
  height:80px;
  max-width:60px;
  text-align-last:center;
  background-color:purple;
  outline-style:dashed;
  outlinr-offset: 10px;
}

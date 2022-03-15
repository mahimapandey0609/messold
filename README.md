# messold
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <link rel="stylesheet" href="messold.css">
    
    <title>Document</title>
</head>
<body>
    <div class="container">
        <div class="row">
       <h4>DESCRIPTION</h4>
       <p>There`s one simple reason we call this our everyday oxford: we</p>
       <p>wear them pretty much every single day</p>
       <h4>MATERIAL</h4>
            <P>Just the right amount of sturdy for year round wear.Soft to the</P>
            <p>touch but built for a decade of solid wear. Oxford is a perfectly</p>
            <p>versatile fabric that looks just a good pressed as it does pulled</p>
            <p>off the back of chair. While traditional cotton uses 25 percent </p>
            <p>of the world`s pesticides, our organic cotton doesn`t use a drop</p>
            <p>A better shirt, responsibly built for the long haul.</p>
            <h4>GARMENT WEIGHT</h4>
            <P>Your daily driver, Burlier than the average </P>
            <p>bottom up</p>
            <div class="slidecontainer">
                <input type="range" min="1" max="100" value ="50" class="slider" id ="myrange"><br>
                <label>light </label>
                <label for="">&nbsp;&nbsp;medium</label>
                <Label>&nbsp; &nbsp; &nbsp;&nbsp;heavy</Label>
            </div>
            

        </div>
        <div class="row">
            <h4>SPECIFICATIONS</h4>
            <ul>
                <li>6-coc 100% organic cotton.</li>
                <li>Made from our burly rughy oxford.</li>
                <li>Our signature Jack button down collar.</li>
                <li>Single rounded chest pocket.</li>
                <li>Double needle felled construction throughout.</li>
                <li>Natural buttons.</li>
                <li>Lock-stitched buttons and buttonholes.</li>
                <li>Shorter lenght to be worn untacked.</li>
                <li>Tailcord fit and high armhole.</li>
                <li>No pleats for easy ironing and clean lines.</li>
                <li>Wash cold and tumble dry low</li>
               <li>made in china</li> 
            </ul>

        </div>
        <div class="row">
            <h4>ESSENTIAL</h4>
            <P>This product is a Taylor Stitch Essential that we aim to always</P>
            <p>keep in stock.Essential are our tried and true product that we</p>
            <p>wear damn near everyday. If your size is currently out-of-stock, </p>
            <p>please submit your email address to the "Notify me" tab.We</p>
            <p>restock Essentials regularly. In stock sizes are available for</p>
            <p>immediate shipping.</p>


        </div>
    </div>
    <script>
        var slider = document.getElementById("myRange");
var output = document.getElementById("demo");
output.innerHTML = slider.value; 
slider.oninput = function() {
  output.innerHTML = this.value;
}
    </script>
</body>
</html>

#messold.css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    margin-top: 5%;
    margin-left: 5%;
    margin-right: 5%;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-around;

}
.row{
    line-height: 40px;
    flex-basis: 30%;
      
      margin-bottom: 30px;
      min-width: 250px;
      
}
.slider {
    -webkit-appearance: none;
    width: 60%;
    height: 15px;
    border-radius: 5px;  
    background: #d3d3d3;
    outline: none;
    opacity: 0.7;
    -webkit-transition: .2s;
    transition: .2s;
  }
  
  .slider::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 25px;
    height: 25px;
    border-radius: 50%; 
    background: #04AA6D;
    cursor: pointer;
  }
  
  .slider::-moz-range-thumb {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: #04AA6D;
    cursor: pointer;
  }
  label{
      padding: 20px;
  }

#messold2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=V, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="messold2.css">
</head>
<body>
    <div class="container">

        <div class="row">
            <h1>8.4M</h1>
            <br>
            <P>Lorem Ipsum is simply</P>
            <P>Lorem Ipsum is simply </P>
            <P>Lorem Ipsum is simply </P>

        </div>
        <div class="row">
            <h1>7.9M</h1>
            <br>
            <P>Lorem Ipsum is simply </P>
            <P>Lorem Ipsum is simply </P>
            <P>Lorem Ipsum is simply</P>
            <P>Lorem Ipsum is simply </P>

        </div>
        <div class="row">
            <hr>
            <div class="slidecontainer">
                <input type="range" min="1" max="100" value ="50" class="slider" id ="myrange"><br>
            </div>

        </div>

    </div>
    <div class="midcontainer">
        <h1>33.6M</h1>
        <p>Lorem Ipsum is simply dummy</p>
        <p>Lorem Ipsum is simply dummy</p>
        <p>Lorem Ipsum is simply </p>

    </div>

    <div class="footcontainer">
        <div class="row">
        <h3>Our Footprints</h3>
            <br>
            Lorem Ipsum is simply dummy text 
            of the printing and typesetting 
            industry. Lorem Ipsum has been the 
            industry's standard dummy text ever since the 1500s
        
             when an unknown.
             <br>
            <br>
             when an unknown printer took a galley 
             of type and scrambled it to make a 
             type specimen book. It has survived not
              only five centuries, but also the 
              leap into electronic typesetting.
              <br>
             <br>
              remaining essentially unchanged,
              It was popularised in the 1960s with
              the release of Letraset sheets containing 
              Lorem Ipsum passages, and more recently
               with desktop publishing software like
                Aldus PageMaker including versions of 
                Lorem Ipsum.

        </div>
        <div class="row">
            <h1>8,679</h1>
            <br>
            <p>Aldus PageMaker including versions of  </p>
            <br>
            <h1>373.73</h1>
            <br>
            Aldus PageMaker including versions
               
            

        </div>
    </div>
</body>
</html>

#messold.css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container{
    margin-top: 5%;
    margin-left: 15%;
    margin-right: 5%;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: center;

}

.row{
    line-height: 20px;
    flex-basis: 30%;
      
      margin-bottom: 30px;
      min-width: 250px;
      padding:40px;
      
}
hr{
 transform: rotate(90deg);
     width: 70%;
     
}
.slider {
    -webkit-appearance: none;
    width: 100%;
    height: 10px;
    border-radius: 5px;  
    background: #d3d3d3;
    outline: none;
    opacity: 0.7;
    -webkit-transition: .2s;
    transition: .2s;
    -webkit-transform:rotate(180deg);
    -moz-transform:rotate(180deg);
    -o-transform:rotate(180deg);
    -ms-transform:rotate(180deg);
    transform:rotate(90deg);
    
  }
  
  .slider::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 25px;
    height: 25px;
    border-radius: 50%; 
    background: #04AA6D;
    cursor: pointer;
    
  }
  
  .slider::-moz-range-thumb {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: #04AA6D;
    cursor: pointer;
  }

  .midcontainer{
      margin-left: 30%;
      align-items: center;
      line-height: 20px;
      margin-top: 5%;
  }
  .footcontainer{
    margin-top: 5%;
    margin-left: 15%;
    margin-right: 5;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    
    
  }
  h1{
      color: brown;
      font-family: Georgia, sans-serif;
  font-size: 5em;
  letter-spacing: -2px;
  margin-bottom: 10%;
  }
  
  

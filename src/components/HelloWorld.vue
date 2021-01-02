<style>
        
        *{
            margin: 0;
            padding: 0;
        }
         @media screen and (max-width:700px) {
         .box{
           display: none;
         }
       }
       @media screen and (min-width:701px) {
         .mob{
           display: none;
         }
       }
        .box{
            width: 100%;
            height: 700px;
            background: #FFA17F;  /* fallback for old browsers */
            background: -webkit-linear-gradient(to right, #00223E, #FFA17F);  /* Chrome 10-25, Safari 5.1-6 */
            background: linear-gradient(to right, #00223E, #FFA17F); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */


            background-size: 200%;
            background-position: top left;
            margin: 0 auto;
            transition: background-position 1s;
        }
        .box:hover{
            background-position: top right;
        }
        .box:hover h1{
            color: #00223E;
        }
        .box h1{
          
            
            font-size: 2em;
            color: #FFA17F;
            text-shadow: 0px 2px 5px rgba(0,0,0,0.1);
            transition: color 1s;
            font-family: 'Poiret One', cursive;
        }
        .sce{
          margin-right:600px;
        }
        .hil{
           max-width: 900px;
          margin: auto;
        }
      
        ul{
            display: flex;
            justify-content: flex-end;
            margin-top:-40px;
            
        }
       
        li{
            list-style-type:none;
            padding: 10px;
            margin: 5px;
            color: #FFA17F;
        }
        li:hover{
            background:#FFA17F;
            color: white;
            border-radius:5px ;
        }
        .box:hover li{
            color: #00223E;}
            button{
              padding:15px;
              background: #e1eec3;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #f05053, #e1eec3);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #f05053, #e1eec3); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
transition: background .3s ease;
              border: none;
              border-radius: 5px;
            }
            button:hover{
              background:#f05053;
              cursor:pointer;
            }
          .con{
            background: #EB5757;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #000000, #EB5757);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #000000, #EB5757); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

          }
          .can{
            background: #C33764;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #1D2671, #C33764);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #1D2671, #C33764); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

          }
          .cin{
            background: #2C3E50;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #FD746C, #2C3E50);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #FD746C, #2C3E50); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

          }
        @media screen and (min-width:700px){
            .jio ,.sidenav{
                display: none;
            }
        }
        @media screen and (max-width:700px) {
            
       
        .sidenav {
    height: 50%; /* 100% Full-height */
    width: 0; /* 0 width - change this with JavaScript */
    position: fixed; /* Stay in place */
    z-index: 1; /* Stay on top */
    top: 0;
    left: 0;
    background-color: #111; /* Black*/
    overflow-x: hidden; /* Disable horizontal scroll */
    padding-top: 60px; /* Place content 60px from the top */
    transition: 0.5s; /* 0.5 second transition effect to slide in the sidenav */
}

/* The navigation menu links */
.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
    transition: 0.3s
}

/* When you mouse over the navigation links, change their color */
.sidenav a:hover, .offcanvas a:focus{
    color: #FFA17F;
}

/* Position and style the close button (top right corner) */
.closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px !important;
    margin-left: 50px;
}
#main {
    transition: margin-left .5s;
    padding: 20px;
}
ul{
    display: none;
}
        }
        /* fallback for old browsers */
 /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

        
        .con:hover{
         background: #30E8BF;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #FF8235, #30E8BF);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #FF8235, #30E8BF); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
transition: .4s ease;
        }
      .con .text{
            text-align: center;
            width: 100%;
            height: 250px;
            margin: auto;
            padding-top: 150px;
            background-color: rgba(0,0,0,.7);
            color: #fff;
            transition: opacity 0.6s;
        }
         .con:hover .text{
            opacity: 1;
        }
        .text{
            opacity: 0;
        }
        .text h2{
            font-size: 3em;
            margin-bottom: 20px;
        }
        .text p{
            width: 70%;
            font-size: 1.2em;
            margin: auto;
        }
        .can:hover{
        background: #200122;  /* fallback for old browsers */
background: -webkit-linear-gradient(to bottom, #6f0000, #200122);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to bottom, #6f0000, #200122); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

        }
      .can .text{
            text-align: center;
            width: 100%;
            height: 250px;
            margin: auto;
            padding-top: 150px;
            background-color: rgba(0,0,0,.7);
            color: #fff;
            transition: opacity 0.6s;
        }
         .can:hover .text{
            opacity: 1;
        }
        .text{
            opacity: 0;
        }
        .text h2{
            font-size: 3em;
            margin-bottom: 20px;
        }
        .text p{
            width: 70%;
            font-size: 1.2em;
            margin: auto;
        }
        .cin:hover{
        background: #fc00ff;  /* fallback for old browsers */
background: -webkit-linear-gradient(to left, #00dbde, #fc00ff);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to left, #00dbde, #fc00ff); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        }
      .cin .text{
            text-align: center;
            width: 100%;
            height: 250px;
            margin: auto;
            padding-top: 150px;
            background-color: rgba(0,0,0,.7);
            color: #fff;
            transition: opacity 0.6s;
        }
         .cin:hover .text{
            opacity: 1;
        }
        .text{
            opacity: 0;
        }
        .text h2{
            font-size: 3em;
            margin-bottom: 20px;
        }
        .text p{
            width: 70%;
            font-size: 1.2em;
            margin: auto;
        }
        .tran{
           transition: transform 0.3s;
        }
        .tran:hover{
          transform: scale(1.1);
        }
        .h1 h2{
          text-transform: capitalize;
        }
    </style>
<template>
  <html>
  <body>
 
   <div class="box">
     <div class="hil">
<h1 class="sce">scenic</h1>
<div class="joy">
    <ul>
        <li>Home</li>
        <li>About</li>
        <li>Service</li>
        <li>Contact</li>
    </ul>
</div> 
<div style="display:flex;">
       <div style="text-align:left; padding-left:100px; margin-top: 300px;">
       <h1 style="padding-left:0px;">Welcome to <br> scenic</h1>
      <button>Discover More</button>
       </div>
       
     </div>
     </div>
     <div  style="display:flex; justify-content:space-around;">
     <div class="con" style="  width:350px; height:400px; margin-top:50px; "> 
             <div class="text">
               <h2>v</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maiores aliquam ipsa eos.</p>
          </div>
     </div>
            <div class="can" style="  width:350px; height:400px; margin-top:50px; "> 
              <div class="text">
               <h2>v</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maiores aliquam ipsa eos.</p>
          </div>
            </div>
            <div class="cin" style="  width:350px; height:400px; margin-top:50px; "> 
               <div class="text">
               <h2>v</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maiores aliquam ipsa eos.</p>
          </div>
            </div>
     </div>
  <div  style=" width:100%; margin-top:50px;">
    <div style="max-width:1200px; margin:auto;">
<div style="width:50%; text-align:center; margin:auto;"><h2>Welcome to my gradient website</h2>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. <br> Aut quos deleniti animi et eveniet unde mollitia delectus laudantium ipsum, incidunt <br> consequatur labore cum, optio numquam ea laborum dolorum ducimus.</p>
</div>
<div style="display:flex; margin-top:20px; justify-content:space-around;">
  <div class="tran" style="width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style="color:white; text-align:center;">Gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
  <div class="tran" style="width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style="color:white; text-align:center;">Gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
  <div class="tran" style="width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style="color:white; text-align:center;">Gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
</div>
    </div>
  </div>
   
   <div>
     <video style="width:100%; margin-top:30px; height:800px;" src="../assets/video.mp4" autoplay loop muted>
     
     </video>
     <div class="doc">
     <h1 style="text-align:center;">Thanks for coming </h1>
     <p style="width:30%; text-align:center; margin:auto;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet maiores adipisci dicta, <br> hic numquam nihil ab exercitationem nesciunt harum, suscipit vero repudiandae cum <br> reiciendis aut perspiciatis laudantium! Consequuntur, voluptas nam.</p>
     </div>
   </div>
    </div>
    
</body>
</html>
</template>
<style>
.doc{
  position: relative;
  bottom: 500px;
}

</style>
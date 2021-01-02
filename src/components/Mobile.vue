<template>
    <div class="mob">
   <button style="position:relative; float:left; top:0px;" v-on:click="greet">Open</button>
  
       <h1>My Beautiful Website</h1>
    
    <div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" v-on:click="close">&times;</a>
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">Contact</a>
</div>
<div class="kol" style="width:50%; margin-top:-40px; margin:auto;">
     <div class="con" style="  width:350px; height:400px; margin-top:50px; "> 
             <div class="text">
               <h2>v</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem maiores aliquam ipsa eos.</p>
          </div>
     </div>
            <div class="can" style="   width:350px; height:400px; margin-top:50px; "> 
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
     <div style="width:100%; margin-top:50px;">
<h2 style="text-align:center;">welcome to my gradient website</h2>
<p style="text-align:center;">Lorem, ipsum dolor sit amet consectetur adipisicing elit. <br> Aut quos deleniti animi et eveniet unde mollitia delectus laudantium ipsum, incidunt sequi <br> consequatur labore cum, optio numquam ea laborum dolorum ducimus.</p>
<div style=" margin-top:50px; width:50%; margin:auto;" class="koll" >
  <div class="tran" style="width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style="text-align:center; color:white;">gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
  <div class="tran" style=" margin-top:30px;width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style=" text-align:center;color:white;">gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
  <div class="tran" style="margin-top:30px; width:300px; color:white; height:300px; background:black; border-radius:5px;"> <h2 style="color:white; text-align:center;">gradient</h2>
  <p style="text-align:left; padding-left:80px; padding-top:30px; width:50%;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam quod ipsa eum impedit totam ut rerum optio, nihil ipsum nobis ab voluptate, fugiat qui nisi asperiores aspernatur officia magnam voluptatum.</p>
   </div>
</div>

  </div>
   <div>
     <video style="margin-top:30px; height:500px;" src="../assets/video.mp4" autoplay loop muted>
     
     </video>
     <div class="doc">
     <h1 style="margin-top:-50px;">Thanks for coming </h1>
     <p style="width:60%; position :relative; bottom:200px; left:100px; text-align:center;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet maiores adipisci dicta, <br> hic numquam nihil ab exercitationem nesciunt harum, suscipit vero repudiandae cum <br> reiciendis aut perspiciatis laudantium! Consequuntur, voluptas nam.</p>
     </div>
   </div>
</div> 
</template>
<style  scoped>
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
 .mob{
            width: 100%;
            height: 500px;
            background: #FFA17F;  /* fallback for old browsers */
            background: -webkit-linear-gradient(to right, #00223E, #FFA17F);  /* Chrome 10-25, Safari 5.1-6 */
            background: linear-gradient(to right, #00223E, #FFA17F); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */


            background-size: 200%;
            background-position: top left;
            margin: 0 auto;
            transition: background-position 1s;
        }
        .mob:hover{
            background-position: top right;
        }
        .mob:hover h1{
            color: #00223E;
        }
          .mob h1{
            line-height: 500px;
            text-align: center;
            font-size: 2em;
            color: #FFA17F;
            text-shadow: 0px 2px 5px rgba(0,0,0,0.1);
            transition: color 1s;
            font-family: 'Poiret One', cursive;
        }
/* The Close Button */
.close {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}

.close:hover,
.close:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
}
.sidenav {
    height: 40%; /* 100% Full-height */
    width: 0; /* 0 width - change this with JavaScript */
    position: fixed; /* Stay in place */
    z-index: 1; /* Stay on top */
    top: 0;
    left: 0;
    background-color: #00223E; /* Black*/
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
    color:#FFA17F;
}

/* Position and style the close button (top right corner) */
.closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px !important;
    margin-left: 50px;
}

/* Style page content - use this if you want to push the page content to the right when you open the side navigation */
#main {
    transition: margin-left .5s;
    padding: 20px;
}

/* On smaller screens, where height is less than 450px, change the style of the sidenav (less padding and a smaller font size) */
@media screen and (max-width:550px) {
.kol{
    padding-right:100px;
}
.koll{
    padding-right:50px;
}
}
@media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
    .sidenav a {font-size: 18px;}
}
header{
    max-width: 1200px;
}
nav{
    display: flex;
    justify-content: space-between;
}
ul{
    display: flex;
}
li{
    list-style-type:none;
    padding: 10px;
}
button{
    padding: 10px;
    margin-left: 5px;
}

</style>
<script>
export default {
methods:{
    greet:function() {
       document.getElementById("mySidenav").style.width = "250px";
    },

/* Set the width of the side navigation to 0 and the left margin of the page content to 0 */
  close:function() {
 document.getElementById("mySidenav").style.width = "0";
}
}

}
</script>
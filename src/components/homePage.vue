<template>
    <div>
        <header>
        <img src="kids_logo.jpg" alt="">
        <center><p class="head"><b>KIDS LEARNING SCHOOL</b></p>
        </center>
        <div class="btn">
            <button> <a href="signUp"></a> Enquire Now</button>
        </div>

        <!-- <div>
    <h1>Welcome to my app!</h1>
     <router-link to="/">Home</router-link> 
    <router-link to="/signUp">SU</router-link>
    <router-view></router-view>
  </div> -->
         
    </header>
    <table id="tab">
        <tr>
            <th>
                <button class="ustext" onclick="show_about()">Home </button> 
             </th>
            <th>
                |<button class="ustext" onclick="show_admissions()">Admissions </button>
                <!-- <a  class="ustext" href="signUp" >Admissions </a> -->
            </th>
            <th>
                |<button class="ustext" onclick="show_about()">About School </button> 
             </th>
             <th>
                |<button class="ustext" onclick="show_acadamics()">Acadamics </button>  
             </th>
             <th>
                |<button class="ustext" onclick="about_research()">Research </button> 
             </th>
             <th>
                |<button class="ustext" onclick=" show_ELearning()">E-Learning </button>
             </th>
             <th>
                |<button class="ustext" onclick=" show_award()">Awards </button>
             </th>
             <th>
                |<button class="ustext" onclick=" show_activities()">activities </button>
             </th>
             <th>
                |<button class="ustext" onclick=" show_Sport()">Sport Section </button>
             </th>
             <th>
                 |<button class="ustext" onclick="show_campus()">Campus </button> 
             </th>
             <th >
                |<button class="ustext" onclick="show_usimg()">US </button> 
             </th>
             <th>
                |<button class="ustext" onclick="show_feedback()">Feedback </button> 
             </th>
        </tr>
    </table>
    <br>

    <div class="container">
        <center id="fam">
                <div>
                    <br>
                    <h1>A Family of Learning !</h1><br>
                <img class="img_transation" src="kids_img2.jpg" alt="">
                </div><br>
            <p class="par"> A school is an educational institution designed to provide learning spaces and learning environments for the teaching of students under the direction of teachers and we belive in power of every students future.... </p>
    
        </center>
        </div><br><br><br>

        <div class="container">
<center>
        <div>
            <br>
            <h1>Activities</h1><br>
        <img style="width: 900px;" src="activities.jpg" alt="">
        </div>
    <p class="par"> We always try to enhnce therotical as well as practical knowledge of our students. We arrange Student Lead Conferance where our students build practical model on the basis of what they learn in their whole educational year.</p>
</center>
</div><br><br><br>
<div class="container">
    <center>
            <div>
                <br>
                <h1>Heighlights of Student Lead Conferance</h1>
                <video width="900" height="600" controls>
                    <source src="SLC_video.mp4" type="video/mp4">
                  </video>
            </div>
    </center>
    </div><br><br><br>


<div class="container">
    <center>
            <div>
                <br>
                <h1>virtual visit to our campus</h1>
                <video width="900" height="600" controls>
                    <source src="kids_video.mp4" type="video/mp4">
                  </video>
            </div>
    </center>
    </div><br><br><br>
    <div class="container">
  
  <div>
      <br>
      <h1 style="margin-left: 200px;">FOUNDER</h1><br>
  <img style="height: 500px; width: 500px; margin-left: -700px;" src="founder.jpg" alt="">
  
  </div>
<center>
<p style="float: right; height: 300px; width: 500px; margin-top: -350px; margin-right: 300px;"> <b style="font-size: larger;">Mrs. Suchita Promod Raundal</b> <br> <br>
   Motivation behind starting Kisd Learning Family is to provide quality educatin to the rural area students. Our founder personally visits each class daily and take daily repots of students and teachers also. She always says future of every student is important ! </p>

</center>
</div><br>

      
    <footer>
    <div  class="leftft">
    <div>
        <b>
            Our branches
        <ul>
            <li>Shree. T N Raundal Junior College of School</li>
            <li>Siddhi-Vinayak Semi-English School</li>
            <li>Kids Learning School, Kalwan</li>
            <li>Kids Learning School, Bhendi</li>
            <li>Kids Learning CBSE School, Bhendi</li>
        </ul>
        </b>
    </div> 
</div>
    <div class=" midft">
        <b>
            Contact Us <br>
       </b>
    Help Desk Phone Numbers- <br> +91 9921787826 <br>
    +91 9423478535 <br>
    <b>
        Email Us <br>
   </b>
   kidslearningschool@gmil.com

    </div> 

    <div class="footimg">
        <img   src="" alt=""/>
        <img class="fimg" src="face_logo.jpeg" alt="">
        <img class="fimg" src="mail.logo.jpeg" alt="">
        <img class="fimg" src="wp_logo.jpg" alt="">
        <img class="fimg" src="yt_logo.webp" alt="">
        <img class="fimg" src="insta_logo.jpeg" alt="">
    </div>   
</footer>
</div> 
</template>

<script>
export default {
  name: 'App',
}
</script> 

<style>
*{
        font-family: cursive;
        margin: 0px;
    }
    body{
        /* background-color: black; */
        color:rgb(252, 104, 24);
        background-image: url(C:\Users\Admin\Desktop\FYND\vue\project\src\assets\kids_img3.jpg);
        background-repeat: no-repeat;
        background-size: 100%;
    }
    header{
        background-image: linear-gradient(to right, rgb(237, 214, 34),rgb(252, 104, 24));
        color: black;
        height: 150px;
        font-size: 40px;
        }
        .head{
        padding: 40px;
    }
    header img{
        margin-top: 10px;
        margin-left: 10px;
        border-radius: 50%;
        height: 120px;
        width: 120px;
        float: left;
    }
    .btn{
        /* 
        padding: 5px; 
        height: 5px;*/
        margin: -100px;
        margin-right: 25px;
        color: black;
        float: right;
        /* background-color: white; */  
    }
    .btn:hover{
        background-color: gray;
    }
    
    th:hover{
        background-color: gray; 
    }

    table{
        /* margin-top: -0px;
        margin-bottom: 700px; */
        margin-left: 1px;
        border: 2px solid rgb(252, 104, 24);
        font-size: larger;
        width: 100%;
        background-image: linear-gradient(to right, rgb(237, 214, 34),rgb(252, 104, 24));
        /* color: black; */
    }
    th{
        padding: 4px;
        /* color: black; */
    }
    footer{
        background-image: linear-gradient(to right, rgb(237, 214, 34),rgb(179, 67, 6));
        color: black;
        height: 200px;
        font-size: 20px;
        margin-top: 0px;

        }
        .fimg{
        margin-top: 170px;
        height: 30px;
        width: 30px;
        margin-left: 30px;
        border-radius: 30%;
    }
    .leftft{
        float: left;
    }
    .footimg{
        margin-top: -250px;
        float: right;
        
    }
    .par{
        width: 700px;
        font-size: 20px;
    }
    .container{
        /* border: 1px solid white; */
        margin: 10px;
        padding: 10px;}
        #fam{
            margin-top: 650px;
        }
    .img_transation:hover{
        min-zoom: 5%;
    }
    .fimg{
        margin-top: 170px;
        height: 30px;
        width: 30px;
        margin-left: 30px;
        border-radius: 30%;
    }
</style>
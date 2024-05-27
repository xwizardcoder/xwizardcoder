<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
*{
    padding: 0;
    margin: 0;
} 

:root{
    --body-color:rgb(74, 64, 64);
    --text-color:rgb(193, 180, 180);
    --button-color:rgb(243, 188, 106);
    --hover-color-button:rgb(227, 118, 35);
    --nav-color:rgb(56, 48, 48);
}
header{
    background-color: black;
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: space-between;
    position:fixed;

}
.right ul{
    display: flex;
    gap: 20px;
  

}
nav{
    display: flex;
    justify-content:space-around;
    background-color:var(--nav-color);
    width: 100%;
    align-items: center;
    
    

}
.logo img{
    cursor: pointer;

}


.right ul li {
    list-style-type: none;
    padding: 15px;
}
.right ul li:hover{
    background-color: rgb(116, 198, 116);
}
.right ul li a{
    text-decoration: none;
    color:white;
}
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 190px;
    background-color: var(--body-color);
    height: 30vw;
    
   
}
.box{
    width: 400px;
    height: 300px;
    background-color: var(--body-color);
    box-sizing: border-box;
    
}
.box1{
    display: flex;
    flex-direction: column;
    
    justify-content: center;
   padding: 10px;
   gap: 10px;
   color:var(--text-color);


}
.box1 span{
    background-color: var(--body-color);
    height: 30px;
    margin-top: 30px;
    width: 90px;


}
.box1 span button{
    background-color: var(--button-color);
    border: none;
    width: 90px;
    height: 30px;
    border-radius: 5px;
}
.box1 span button:hover{
    background-color:var(--hover-color-button);
}


.box2{
    display: flex;
    padding-left: 20px;
    align-items: center;
    
}
.box2 .image{
    background-color:var(--body-color);
    border-radius: 15px;
    overflow: hidden;
    height: 250px;
    transition: 1s;

}
.box2 .image:hover{
    transform:scale(1.05);
    box-shadow: 1px 2px 10px;
}
footer{
    background-color:red;
    width: 100%;
    height:100%;
    display: flex;
    flex-direction: column;

    }
.section{
    width: 100%;
    height:20vh;
    background-color: black;
}
.section1{
    background-color:black;
    display: flex;
    justify-content: center;
    align-items: center;
    

}
.section2{
   height: 70px;
   color: white;
   display: flex;
   justify-content: center;
   align-items:end;


}

.contact{
    width: 410px;
    height: 60px;
    background-color:black;
   
    display: flex;
    flex-direction: column;
    padding: 20px;
}
.contact ul li a{
    text-decoration: none;
    color:var(--text-color);
}
.contact ul li{
    list-style-type: none;
}    </style>
</head>
<body>

   <header>
 
        <nav>
            <div class="logo">
                <img src="https://devforum-uploads.s3.dualstack.us-east-2.amazonaws.com/uploads/original/4X/b/0/f/b0f071884d053ffdc6d806571bcd5fedfb6f9f74.png" alt="logo here .." width="100px" height="50px">

            </div>
            <div class="right">
               
                    <ul>
                        <li><a href="3">About me </a></li>
                        <li><a href="https://drive.google.com/file/d/1VavvQhRHEsMDsV-dONoh20DD1sjvIruO/view?usp=drive_link">Resume</a></li>
                        <li><a href="3">blog </a></li>
                        <li><a href="3">projects </a></li>
                    </ul>
    
               
            </div>
            
        </nav>
        
    </div>
   </header>
    <main>
        <div class="container">
            <div class="box box1">
                <p style="color: yellow;">hello , welcome </p>
              
               <h1>hii i am saurabh</h1>
               <p>i am frontend Developer and workd on lots of projects , if you want your own website feel free to contact ..</p>
               <span><button>contact</button></span>


            </div>
            <div class="box box2">
                <div class="image">
                    <img src="https://vegamovies.ist/wp-content/uploads/2024/05/ATLAS-2024-Hindi-English-Vegamovies.To_.png" width="200px" height="250px">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="box box1">
                <p style="color: yellow;">hello , welcome </p>
              
               <h1>hii i am saurabh</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate, nesciunt!</p>
               <span><button> click me</button></span>


            </div>
            <div class="box box2">
                <div class="image">
                    <img src="https://vegamovies.ist/wp-content/uploads/2024/05/ATLAS-2024-Hindi-English-Vegamovies.To_.png" width="200px" height="250px">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="box box1">
                <p style="color: yellow;">hello , welcome </p>
              
               <h1>hii i am saurabh</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate, nesciunt!</p>
               <span><button> click me</button></span>


            </div>
            <div class="box box2">
                <div class="image">
                    <img src="https://vegamovies.ist/wp-content/uploads/2024/05/ATLAS-2024-Hindi-English-Vegamovies.To_.png" width="200px" height="250px">
                </div>
            </div>
        </div>
        
    </main>
    <footer>
        <div class="section section1">
            <div class="contact">
                <ul>
                    <li><a href="#">contact</a></li>
                    <li><a href="#">about me </a></li>
                    <li><a href="#">hello</a></li>
                    <li><a href="#">map</a></li>
                </ul>
            </div>
            <div class="contact">
                <ul>
                    <li><a href="#">data</a></li>
                    <li><a href="#">xyz</a></li>
                    <li><a href="#">test</a></li>
                    <li><a href="#">xyz</a></li>
                </ul>
            </div>
            <div class="contact">
                <ul>
                    <li><a href="#">xyz</a></li>
                    <li><a href="#">masa</a></li>
                    <li><a href="#">lol</a></li>
                    <li><a href="#">test</a></li>
                </ul>
            </div>
        </div>
        <div class="section section2">
          
            <p>Copyright  &copy   made with <img src="heart_833472.png" width="20px" height="20px" > by xwizardcoder</p>
        </div>

    </footer>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/main.css">
</head>
<body>
    <div class="overlay" id="overlay">
        <h3>searching now...</h3>
    </div>
        

    <div class="hero-bg">
        <section class="top">
            <header>
                <a href="#">yummy.eat</a>
            </header>

            <h1><span> The Healthy</span> eating element</h1>
               <p> Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                    Numquam, nobis eaque eveniet inventore fugit, labore,
                    quidem vel assumenda cum magnam reprehenderit.
                    Harum doloremque omnis optio reprehenderit asperiores consectetur totam quas!

               </p>
               <div class="form-container">
                   <form action="">
                       <div class="formleft">

                       <label for="city">Enter your city</label>
                       <input type="text" name="city" id="city">
                       <p> Example: San Diego</p>
                    </div>

                       <input type="button" value="Find Food Now" id='cta-btn'>
                   </form>
               </div>
        </section>

        
    </div>

    <section class="authentic">
       <div class="right-col">
           <h2> Authentic.Awesome.</h2>
           
           <p> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Numquam, nobis eaque eveniet inventore fugit, labore, quidem vel assumenda cum magnam reprehenderit. Harum doloremque omnis optio reprehenderit asperiores consectetur totam quas!

       </div> 
       <img src="images/food.jpg" alt="picture of asante">
    </section>

     <script>

     let btn = document.getElementById("cta-btn")
     let overlay = document.getElementById("overlay")

     btn.addEventListener("click",()=> {
        overlay.style.display="grid"; 
         overlay.classList.add("animate-overlay")
     })
     </script>
</body>
</html>

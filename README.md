
<html lang="en">
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Document</title>
     <link rel="stylesheet" href="cssfile.css">

     <style>
          *{
               margin: 0;
               padding: 0;
               box-sizing: border-box;
          }
          html{
               scroll-behavior: smooth;
          }
          body{
               font-family: 'popins',sans-serif;
               margin: 0;
               padding: 0;
          }
          header{
               
               /* background-image: url('websitephots/bgpic.jpg'); */
               background-image: url('https://assets-global.website-files.com/63fef929dc32cb28d93d6c87/642422d8082082150827ba3f_6334a1fbbb381157cb984988_The%2520Importance%2520of%2520Employee%2520Background%2520Checks%2520for%2520Big%2520Companies.jpeg');
               background-size: cover;
               background-position: center;
               color: #fff;
               display: flex;
               flex-direction: column;
               align-items: center;
               justify-content: center;
               height: 100vh;
               text-align: center;
          }
          header h1{
               font-size:85px;
               margin-top: 150px;
               
          }
          header p{
               font-size:20px;
               margin: 0.5rem 0;
          }
          header a.cta{
              background-color: #fff;
              border: 1px solid #333;
              color: #333; 
              padding: 1rem 2rem;
              text-decoration: none;
              border-radius: 50px;
              margin-top: 1rem;
              transition: all 0.2s;
          }
          header a.cta:hover{
               background-color: #333;
               color: #fff;
               cursor: pointer;
          }
          nav{
               display: flex;
               justify-content: space-between;
               align-items: center;
               margin-bottom: 2rem;
               position: absolute;
               top: 0;
               width: 100%;
               padding: 20px 7%;
          }
          nav img{
               height: 100px;
          }
          nav ul{
               display: flex;
               list-style: none;
               margin: 0;
               padding: 0;
          }
          nav a{
               color: #fff;
               margin: 0 1rem;
               text-decoration: none;
               font-size: 1.6rem;
          }
          main{
               display: flex;
               flex-wrap: wrap;
               justify-content: center;
               padding: 3rem 0;
          }
          section{
               width: 80%;
               text-align: center;
               margin: 2rem;
          }
          section h2{
               font-size: 2rem;
               margin-bottom: 1rem;
          }
          section form{
               max-width: 600px;
               display: flex;
               flex-direction: column;
               align-items: center;
               margin-top: 4rem;
               margin-left: auto;
               margin-right: auto;
          }
          section input[type="text"],
          section input[type="email"],
          section textarea{
               width: 100%;
               padding: 1rem;
               font-size: 1.1rem;
               margin-bottom: 1rem;
               border-radius: 5px;
               border: none;
               outline: none;
               background: #f2f2f2;
          }
          section button[type="submit"]{
               background-color: #333;
               color: #fff;
               padding: 1rem;
               border: none;
               border-radius: 40px;
               cursor: pointer;
               transition: all 0.2s;
               width: 100%;
          }
         
          footer{
               background-color: #333;
               color: #fff;
               display: flex;
               justify-content: center;
               padding: 1rem 0;
               text-align: center;
          }
          footer p{
               font-size: 1.5rem;  
               margin: 0;   
          }


          footer a{
               color: #fff;
               margin-left: 1rem;
               text-decoration: none;
          }
          @media only screen and (max-width:600px){
               header{
                 flex-direction: column;   
               }
               nav{
                    flex-direction: column;
               }
               main{
                  flex-direction: column;  
               }
               section{
                    width: 100%;
               }
          }


       #services{
          padding: 1rem 0;
          text-align: center;
       }  
       #services h2{
          margin-bottom: 5rem;
       } 
       .service{
          width: 30%;
          display: inline-block;
          padding: 0 1rem;
          text-align:center;
       }
       .service img{
          width: 250px;
          margin-bottom: 1rem;
          border-radius: 50%;
       }
      .service h3{
          margin-bottom: 1rem;
      }  

       @media only screen and (max-width:600px){
            .service{
               width: 100%;
               margin: 2rem 0;
            }
       }

       #about{
          padding: 50px 8%;
          line-height: 30px;
       }
       #about img{
          margin-top: 50px;
       }
      #contact{
          padding: 50px 7%;
          line-height: 30px;
      }
      #contact h2{
          margin-bottom: 2rem;
      }

  ul li a:hover{
    
     
     color: sienna;
     text-decoration: none;
  }
  ul li a{
     color: black;
  }
      


     </style>
</head>
<body>
     <header>
          <nav>
              
               <img src="https://justcreative.com/wp-content/uploads/2023/05/Best-Social-Media-Logos-11.png.webp" alt="">
               
     
               <ul>
                    <li><a href="#top">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
               
                    <li><a href="#contact">Contact</a></li>
               </ul>
          </nav>
          <h1 style="color:black;">Social Media Agency</h1>
          <p style="color: black;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam<br>
               euismod sapien vel tincidunt aliquam.Nam</p>
          <a href="#contact" class="cta">Get in Touch</a>
     </header>

     <main>   
          <section id="services">
               <h2>Our Services</h2>
               <div class="service">
                  <!-- <img src="websitephots/pic1.jpg" alt="service 1"> -->
                  <img src="https://cdn3.vectorstock.com/i/1000x1000/00/82/clockwork-or-puppet-toy-business-employee-female-vector-46890082.jpg" alt="service 1">
                  <h3>Social Media Marketing</h3>
                  <p>Our social media agency is dedicated to helping business and organization in the 
                    world </p>
               </div>
               <div class="service">
                    <!-- <img src="websitephots/pic4.jpg" alt="service 2"> -->
                    <img src="https://img.freepik.com/premium-vector/girl-with-laptop-table_641360-73.jpg?w=2000" alt="service 2">
                    <h3>Influencer Marketing</h3>
                    <p>Our social media agency is dedicated to helping business and organization in the 
                         world </p>
                 </div>
                 <div class="service">
                    <!-- <img src="websitephots/pic3.jpg" alt="service 3"> -->
                    <img src="https://img.freepik.com/premium-vector/woman-sitting-table-with-laptop-working-computer-freelance-online-education-social-media-concept-freelance-studying-concept-flat-style-illustration-isolated-white_186332-72.jpg" alt="service 3">
                    <h3>Brand Awareness</h3>
                    <p>Our social media agency is dedicated to helping business and organization in the 
                         world </p>
                 </div>
          </section>

          <section id="about">
               <h2>About us</h2>
               <p>our social media agency is dedicated to helping business and organization establish a 
                    strong online presence through innovative and effetive social media strategies. our team of
                    experts understands the importance of the creating a personlized apporch for each of our
                    clients to maximize their reach and engagement on social media platform. 
               </p>
               <!-- <img src="websitephots/pic5.jpg" alt="" width="100%"> -->
               <img src="https://img.freepik.com/free-photo/people-business-meeting-high-angle_23-2148911819.jpg?w=2000" alt="" width="100%">
            </section>

        

          <section id="contact">
               <h2>Get in Touch</h2>
               <p>Get in touch with us today! our team is  hear to answer any questions you may and help
                    you with social media needs. simply fill out the form below with your name,email,and 
                    message, and we'll be in touch shortly. we're excited to hear from you and help you achive
                    your social media goals!
               </p>
               <form action="submit-form.php" method="post">
                   <input type="text" name="name" placeholder="Your Name">
                   <input type="email" name="email" placeholder="Your Email">
                   <textarea name="message" placeholder="your message"></textarea>
                   
                   <button type="submit">Submit</button>
               </form>
          </section>    
     </main>

     <footer>
          <p>Copyright &copf; startup companey 2023</p>
     </footer>
         
</body>
</html>

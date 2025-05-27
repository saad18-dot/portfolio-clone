PORTFOLIO-CLONE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PORTFOLIO</title>
  <link rel="stylesheet" href="portfolio type 2.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
   <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      margin: 0;
      padding: 0;
   
      
    }

    header {
      background-color: #0a0c4d;
      color: yellow;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    
    .skill-card i { 
        color: #0a0c4d;
        max-height: 130px;
    }

    header h1 {
      margin: 0;
      text-transform: capitalize;
      text-decoration: solid; 
      text-shadow: #000000;
      text-decoration-style: double;
      text-size-adjust: 20px;
     font-style:italic;
     font-family: 'Times New Roman', Times, serif;
      
    }

    nav a {
      color: yellow;
      margin: 0 10px;
      text-decoration: none;
      font-style: italic;
      font-family: 'Times New Roman', Times, serif;
    font-weight: bold; 
    }

    .intro {
      padding: 40px 20px;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
    }

    .intro-text {
      max-width: 500px;
      justify-content: center;
    }

    .intro-text h2 {
      font-size: 28px;
      color: #0a0c4d;
      justify-content: center;
    }

    .intro-text p {
      font-size: 16px;
      margin-top: 10px;
      justify-content: center;
    }

    .btn {
      background-color: #0a0c4d;
      color:yellow;
      padding: 10px 20px;
      margin-top: 15px;
      border: none;
      border-radius: 20px;
      text-decoration: none;
      padding-right: 30px;
      
    }
    .btn:hover {
        color: #ff0000;
    }

    .intro-img {
        flex: 1;
        display: flex;
        justify-content: flex-end;
    }

    
    

    section {
      text-align: center;
      padding: 30px 20px;
    }

    h3 {
      color: #0a0c4d;
      font-size: 24px;
      justify-content: center;
    }
   
     
    .portfolio-section {
      display: flex;
      justify-content: space-around;
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: linear-gradient(to right, #ffffff, #9b9cf0);
      border-radius: 8px;
      width: 300px;
      padding: 15px;
      box-shadow: 50px 54px 58px rgba(0,0,0,0.1);
      transition: all 1sec;
    }

    .card img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }

    .card h3 {
      margin-top: 10px;
      color: #003300;
    }

    .card p {
      font-size: 14px;
      color: #0a0c4d;
    }

    .buttons {
      margin-top: 10px;
      color: yellow;
    }

    .buttons button {
      background-color: #0a0c4d;
      color: yellow;
      border: none;
      padding: 8px 12px;
      margin: 5px;
      border-radius: 30px;
      cursor: pointer;

    }
    .buttons :hover{
        color: hsl(0, 100%, 50%);
    }

    .contact-section {
     padding: 50px 30px;
     margin: 60px auto;
     max-width: 900px;
     background: linear-gradient(to right, #ffffff, #9b9cf0);
     border-radius: 20px;
     box-shadow: 0 12px 30px rgba(0, 0, 0, 0.1);
}

.contact-section h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 40px;
  color: #0a0c4d;
}

.contact-section h2 span {
  color: yellow;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.row {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.form-group {
  flex: 1;
  display: flex;
  flex-direction: column;
}

.full-width {
  width: 100%;
}

label {
  font-weight: 600;
  margin-bottom: 6px;
  color: #0a0c4d;
}

input,
select,
textarea {
  padding: 12px;
  border-radius: 10px;
  border: 1px solid #000000;
  font-size: 1rem;
  color: #ffffff;
  background-color: #0a0c4d;
  transition: border 0.3s ease;
}

input:focus,
select:focus,
textarea:focus {
  border: 1px solid #0a0c4d;
  outline: none;
}
input ::placeholder{
    color: #ffffff
}
.gender{
    display: flex;
    align-items: center;
}

.gender-options {
  display: flex;
  gap: 15px;
  margin-top: 8px;
 
}


.gender-options label {
  display: flex;
  align-items: center;
  gap: 6px;
  font-weight: 500;
}

.submit-btn {
  padding: 14px;
  background-color: #0a0c4d;
  color: rgb(255, 255, 255);
  border: none;
  border-radius: 10px;
  font-size: 1rem;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.submit-btn:hover {
  color: yellow;
}



    
   </style>
</head>
<body>

  <header>
    <h1>MSN</h1>
    <nav>
        <div class="navbar">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Expertise</a>
      <a href="#">Skiils</a>
      <a href="#">Contact</a>
    </nav>
   </div>
  </header>

  <div class="intro">
    <div class="intro-text">
      <h2>Hey M.SAAD NASIR here!<br>Learning Full Stack Development at <span style="color: rgb(76, 226, 16);">SMIT</span></h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam magnam laborum distinctio. Itaque enim illum perferendis consequuntur totam laudantium, obcaecati eaque, aliquid possimus quibusdam voluptas facilis, impedit iusto! Eaque, odit.</p>
       <br/>
       <br/>
       <br/>
       <br/>
      <div class="skill-card">
        <i class="fa-brands fa-linkedin"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-whatsapp"></i>
        <i class="fa-brands fa-github"></i>
      




       </div>
      <button class="btn">Hire Me!</button>
     </div>
  <div class="intro-img">
    <img src="./image/Adobe Express - file.png" alt="M.Saad Nasir">
  </div>
  </div>
    <hr/>
    
  </div>

  <section>
    <h3>ABOUT <span style="color: yellow">ME!</span> </h3>
    <p>I am a passionate <strong><span style="color: #0a0c4d;" >Graphic Designer</span></strong> with a strong eye for detail and a love for visual storytelling. Over the past few years, I’ve developed brand identities, marketing materials, and digital assets that communicate messages with clarity and impact. While design is my primary focus, I also bring foundational web development skills—creating responsive websites using <strong><span style="color: #0a0c4d;" >HTML and CSS</span></strong>. My goal is always to merge aesthetics with functionality to deliver meaningful user experiences.</p>
    <button class="btn">About ME!</button>
    <hr/>
  </section>
  <section>
  <h2> <span style="color: #0a0c4d;"> EXPERTISE! 👁️</span></h2>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate in quaerat labore obcaecati reprehenderit ratione cupiditate, totam natus, aspernatur mollitia quasi delectus consectetur voluptatem excepturi nemo eum error? At, eum!</p>
  </section>

    <div class="portfolio-section">
    <div class="card">
      <img src="./image/istockphoto-1371339413-612x612.jpg" alt="Portfolio Image">
      <h3>Personal Portfolio</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ex magni qui.</p>
      <div class="buttons">
        <button>Preview</button>
        <button>View Source</button>
      </div>
    </div>
    
    <div class="card">
      <img src="./image/portfolio image.jpg" alt="Portfolio Image">
      <h3>Personal Portfolio</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ex magni qui.</p>
      <div class="buttons">
        <button>Preview</button>
        <button>View Source</button>
      </div>
    </div>

    <div class="card">
      <img src="./image/portfoliooo (1).jpg" alt="Portfolio Image">
      <h3>Personal Portfolio</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos ex magni qui.</p>
      <div class="buttons">
        <button>Preview</button>
        <button>View Source</button>
      </div>
    </div>
  </div>

  <hr/>

  <section class="contact-section">
  <h2>📬 Contact <span>Me</span></h2>
  <form class="contact-form">
    <div class="row">
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" placeholder="Enter your full name" required>
      </div>
      <div class="form-group">
        <label for="email">Email Address</label>
        <input type="email" id="email" placeholder="example@mail.com" required>
      </div>
      <div class="form-group">
        <label for="phone">Phone Number</label>
        <input type="tel" id="phone" placeholder="+123 456 7890">
      </div>
    </div>

    <div class="row">
      <div class="form-group">
        <div class="gender">
        <label>Gender</label>
        </div>
        <div class="gender-options">
          <label><input type="radio" name="gender" value="male"> Male</label>
          <label><input type="radio" name="gender" value="female"> Female</label>
          <label><input type="radio" name="gender" value="other"> Other</label>
        </div>
      </div>

      <div class="form-group">
        <label for="eyeType">Eye Contact Type</label>
        <select id="eyeType" required>
          <option value="">Select type</option>
          <option value="friendly">Friendly</option>
          <option value="intense">Intense</option>
          <option value="brief">Brief</option>
          <option value="nervous">Avoidant</option>
        </select>
      </div>
    </div>

    <div class="form-group full-width">
      <label for="message">Your Message</label>
      <textarea id="message" rows="4" placeholder="Say something..." required></textarea>
    </div>

    <button type="submit" class="submit-btn">Send Message</button>
  </form>
</section>


  
</body>
</html>
  
  


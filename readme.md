<!-- <!-- <!DOCTYPE html>
<html lang="en">

<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Document</title>
</head>

<body>
 <header>
  <h1>My Profile</h1>
  <nav>
   <ul>
    <li><a href="#about-me">About Me</a></li>
    <li><a href="#hobbies">Hobbies</a></li>
    <li><a href="#contact">Contact</a></li>
   </ul>
  </nav>
 </header>
 <section>
  <p>My name is Agun Akindele. I am a software developer with a passion for coding and technology. I enjoy learning new
   programming languages and frameworks to enhance my skills</p>
  <img src="image/myself.jpeg" alt="image of myself">
  <h2>Hobbies</h2>
  <ol>
   <li>Reading</li>
   <li>Traveling</li>
   <li>Coding</li>
   <li>Gaming</li>
  </ol>
 </section>
 <footer>
  <p>Contact me at: <a href="mailto:aguntoroti10@gmail.com">Send me an email </a></p>
 </footer>
</body>
<!-- dont copy my personal project -->

</html>

<!DOCTYPE html>
<html lang="en">

<head>
 <meta charset="UTF-8" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <title>Product Landing Page</title>
 <link rel="stylesheet" href="style.css" />
</head>

<body>
 <header class="hero">
  <h1>Your Amazing Product</h1>
  <p>Make your life easier with our awesome solution.</p>
  <a href="#" class="cta-button">Sign Up Now</a>
 </header>

 <main>
  <section class="features">
   <div class="feature">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
     <path fill="currentColor" fill-rule="evenodd"
      d="M12 3a1 1 0 0 1 .832.445l3.471 5.207l4.182-2.51a1 1 0 0 1 1.503 1.01l-2 13A1 1 0 0 1 19 21H5a1 1 0 0 1-.988-.848l-2-13a1 1 0 0 1 1.503-1.01l4.182 2.51l3.471-5.207A1 1 0 0 1 12 3m-1 11a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6"
      clip-rule="evenodd" />
    </svg>
    <h3>Feature One</h3>
    <p>Short description of the first feature.</p>
   </div>
   <div class="feature">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
     <path fill="currentColor" fill-rule="evenodd"
      d="M12 3a1 1 0 0 1 .832.445l3.471 5.207l4.182-2.51a1 1 0 0 1 1.503 1.01l-2 13A1 1 0 0 1 19 21H5a1 1 0 0 1-.988-.848l-2-13a1 1 0 0 1 1.503-1.01l4.182 2.51l3.471-5.207A1 1 0 0 1 12 3m-1 11a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6"
      clip-rule="evenodd" />
    </svg>
    <h3>Feature Two</h3>
    <p>Short description of the second feature.</p>
   </div>
   <div class="feature">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
     <path fill="currentColor" fill-rule="evenodd"
      d="M12 3a1 1 0 0 1 .832.445l3.471 5.207l4.182-2.51a1 1 0 0 1 1.503 1.01l-2 13A1 1 0 0 1 19 21H5a1 1 0 0 1-.988-.848l-2-13a1 1 0 0 1 1.503-1.01l4.182 2.51l3.471-5.207A1 1 0 0 1 12 3m-1 11a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6"
      clip-rule="evenodd" />
    </svg>
    <h3>Feature Three</h3>
    <p>Short description of the third feature.</p>
   </div>
  </section>
 </main>

 <footer class="footer">
  <p>Contact us: email@example.com | +123 456 7890</p>
  <p>&copy; 2025 Your Company. All rights reserved.</p>
 </footer>
</body>

</html> 
-->
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
html, body {
  height: 100%;
  display: flex;
  flex-direction: column;
}

main {
flex: 1;
}

body {
font-family: 'Segoe UI', sans-serif;
line-height: 1.6;
color: #333;
background-color: #f9f9f9;
}

.hero {
background-color: #4a90e2;
color: #fff;
text-align: center;
padding: 4rem 2rem;
}

.hero h1 {
font-size: 2.5rem;
margin-bottom: 1rem;
}

.hero p {
font-size: 1.2rem;
margin-bottom: 1.5rem;
}

.cta-button {
background-color: #fff;
color: #4a90e2;
padding: 0.75rem 1.5rem;
border-radius: 5px;
text-decoration: none;
font-weight: bold;
transition: background 0.3s;
}

.cta-button:hover {
background-color: #e6e6e6;
}

.features {
display: flex;
flex-wrap: wrap;
gap: 2rem;
padding: 4rem 2rem;
justify-content: center;
background-color: #fff;
}

.feature {
background-color: #f0f0f0;
padding: 2rem;
border-radius: 10px;
text-align: center;
flex: 1 1 300px;
max-width: 300px;
}

.feature img {
margin-bottom: 1rem;
}

.feature h3 {
margin-bottom: 0.5rem;
}

.footer {
background-color: #333;
color: #fff;
text-align: center;
padding: 2rem;
font-size: 0.9rem;
} \*/ -->

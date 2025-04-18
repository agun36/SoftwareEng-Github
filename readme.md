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

<!DOCTYPE html>
<html lang="en">

<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Calculator App</title>
 <style>
  .calculator {
   width: 300px;
   background-color: #f0f0f0;
   padding: 20px;
   border-radius: 10px;
   margin: 20px auto;
  }

.display {
background-color: #ffffff;
padding: 15px;
margin-bottom: 15px;
text-align: right;
font-size: 24px;
border: 1px solid #cccccc;
border-radius: 5px;
}

.buttons {
display: grid;
grid-template-columns: repeat(4, 1fr);
gap: 10px;
}

button {
padding: 15px;
font-size: 18px;
border: none;
border-radius: 5px;
cursor: pointer;
transition: opacity 0.2s;
}

button:hover {
opacity: 0.8;
}

.clear {
background-color: #ff4444;
color: white;
}

.operator {
background-color: #4CAF50;
color: white;
}

.equals {
background-color: #2196F3;
color: white;
}

.number {
background-color: #e0e0e0;
}

.zero {
grid-column: span 2;
}
</style>

</head>

<body>
 <div class="calculator">
  <div class="display">0</div>
  <div class="buttons">
   <button class="clear">C</button>
   <button class="operator">/</button>
   <button class="operator">*</button>
   <button class="operator">-</button>
   <button class="number">7</button>
   <button class="number">8</button>
   <button class="number">9</button>
   <button class="operator">+</button>
   <button class="number">4</button>
   <button class="number">5</button>
   <button class="number">6</button>
   <button class="equals">=</button>
   <button class="number">1</button>
   <button class="number">2</button>
   <button class="number">3</button>
   <button class="number zero">0</button>
  </div>
 </div>

 <script>
  const display = document.querySelector('.display');
  let currentOperand = '';
  let previousOperand = '';
  let operation = null;

  // Number buttons
  document.querySelectorAll('.number').forEach(button => {
   button.addEventListener('click', () => {
    if (currentOperand === 'Error') currentOperand = '';
    currentOperand += button.textContent;
    updateDisplay();
   });
  });

  // Operator buttons
  document.querySelectorAll('.operator').forEach(button => {
   button.addEventListener('click', () => {
    if (currentOperand === 'Error') return;

    if (currentOperand === '' && previousOperand !== '') {
     operation = button.textContent;
     return;
    }

    if (currentOperand === '') return;

    if (previousOperand !== '') {
     compute();
    }

    operation = button.textContent;
    previousOperand = currentOperand;
    currentOperand = '';
    updateDisplay();
   });
  });

  // Equals button
  document.querySelector('.equals').addEventListener('click', () => {
   if (previousOperand === '' || currentOperand === '' || !operation) return;
   compute();
  });

  // Clear button
  document.querySelector('.clear').addEventListener('click', () => {
   currentOperand = '';
   previousOperand = '';
   operation = null;
   updateDisplay();
  });

  function compute() {
   let computation;
   const prev = parseFloat(previousOperand);
   const current = parseFloat(currentOperand);

   if (isNaN(prev) || isNaN(current)) return;

   switch (operation) {
    case '+':
     computation = prev + current;
     break;
    case '-':
     computation = prev - current;
     break;
    case '*':
     computation = prev * current;
     break;
    case '/':
     if (current === 0) {
      currentOperand = 'Error';
      previousOperand = '';
      operation = null;
      updateDisplay();
      return;
     }
     computation = prev / current;
     break;
    default:
     return;
   }

   currentOperand = computation.toString();
   previousOperand = '';
   operation = null;
   updateDisplay();
  }

  function updateDisplay() {
   display.textContent = currentOperand || '0';
  }
 </script>
</body>

</html>

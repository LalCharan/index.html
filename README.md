<!DOCTYPE html>
<html lang="en">
<head>
  <title>Online Book Store</title>
  
</head>
<body>
</body>  
<body> 
    <h1>Welcome to Our Website!</h1>
    <div class="header-buttons">
      <button id="loginButton" class="btn">Login</button>
      <button id="signupButton" class="btn">Sign Up</button>
   
    </div>
    <script>
        document.getElementById("loginButton").addEventListener("click", function() {
        window.location.href = "loginpage.html";
        });
        document.getElementById("signupButton").addEventListener("click", function() {
        // Redirect to signup page if you have a separate signup.html
        window.location.href = "signpage.html";
        });
        
    </script> 
    <header>
    <h1>Online Book Store</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Books</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    
    
  </header>

  <main>
    <section class="books">
      <div class="book">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-apj-img.png" alt="Book 1">
        <h3>Wings of fire</h3>
        <p>Author: Arun Tiwari</p>
        <button id="buynowbtn" class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-chetan-bhagat-img.png" alt="Book 2">
        <h3>The 3 mistakes of my life</h3>
        <p>Author: Chetan Bhagat</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/harrypotter-img.png" alt="Book 3">
        <h3>Harry Potter and the Sorcerer's Stone</h3>
        <p>Author:J.K.Rowling</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/612/612/xif0q/regionalbooks/j/w/2/ssc-reasoning-7200-tcs-mcq-chapter-wise-4th-edition-english-original-imagz46gyddwfpfu.jpeg?q=70" alt="Book 3">
        <h3>SSC</h3>
        <p>Baljit Dhaka</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/xif0q/book/3/4/v/thoughts-to-inspire-in-english-swami-vivekanand-paperback-original-imafaqvn8krkj4cg.jpeg?q=70" alt="Book 3">
        <h3>Swami Vivekananda</h3>
        <p>Amazing Reads</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/kgqvlow0/book/2/2/5/three-men-in-a-boat-original-imafwwgwxx9ygmqr.jpeg?q=70" alt="Book 3">
        <h3>Three Men In A Boat</h3>
        <p>Jerome Jerome K</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/xif0q/book/n/e/p/be-a-super-learner-original-imagk7xbdsszr8st.jpeg?q=70" alt="Book 3">
        <h3>Be A SuperLearner</h3>
        <p>Jonathan Levi</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/book/9/4/9/written-in-the-stars-original-imae76qybhkszxb4.jpeg?q=70" alt="Book 3">
        <h3>Written In The Stars </h3>
        <p>Anjali</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/k0plpjk0/book/5/5/0/the-dawn-of-character-original-imafkg8ye4xrpvc7.jpeg?q=70" alt="Book 3">
        <h3>The Dawn of Character </h3>
        <p>Peraallon books</p>
        <button class="btn">Buy Now</button>
      </div>
      <div class="book">
        <img src="https://rukminim2.flixcart.com/image/416/416/kgqvlow0/book/9/0/1/1984-original-imafwwgwuzswhadz.jpeg?q=70" alt="Book 3">
        <h3>1984</h3>
        <p>George Orwell</p>
        <button class="btn">Buy Now</button>
      </div>

    </section>
    <section class="hero">
        <h2>Welcome to our Online Book Store!</h2>
        <p>Discover a vast collection of books on various topics.</p>
        <a href="#" class="btn">Explore Now</a>
    </section>
  </main>
</body>

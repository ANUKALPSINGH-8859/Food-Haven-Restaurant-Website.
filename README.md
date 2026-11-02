# Food-Haven-Restaurant-Website.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            margin: 0;
        }
        #div1{
           text-align: center;
           background-color: black;
           color: white;
           padding: 15px;
        }
        a{
            color: white;
            text-decoration: none;
            margin: 15px;
        }
        .div2{
             background-color: #fff0bd;
            text-align: center;
            padding: 40px 15px;
        }
        .card{
            display: inline-block;
            margin: 10px;
            background-color: white;
            border: 2px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            width: 200px;
            height: 200px;
        } 
        .food{
           font-size: 40px;
            text-align: center;
            background-color: #fff0bd;
            padding: 10px;
        }
        select, input, textarea{
             border: 1px solid black;
             padding: 5px;
        }
        .food-item{
             display: flex;
            justify-content: space-between;
            margin: 10px;
        }
        section{
            padding: 15px;
        }
        .offer{
            background-color: #fff0bd;
            padding: 15px;
            border-radius: 10px;
        }
        form{       
            background-color: #ddeaf8;
            padding: 20px;
            border-radius: 10px;
            max-width: 600px;
        }
        button{
            border: 1px ;
            background-color: orange;
            border-radius: 10px;
            padding: 10px ;
            width: 500px;
        }
    </style>

</head>
<body>
    <div id ="div1">
        <h1 >🍴Food Haven</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#Reservation">Reservation</a>
            <a href = "#contact">Contact</a>
        </nav>
    </div>
    <div class="div2" id="home">
        <h1 style="color: orange;">Welcome to Food Haven</h1>
        <p>Good Food, Good Mood!</p>
        <a href="#Reservation" ><button style="background-color: orange; border-radius: 5px;border: orange;padding: 10px;">Book a Table</button></a>
    </div>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="card">
               <div class="food">🥖</div>
                    <h3>Starters</h3>
                <div class="food-item">
                    <span>Garlic Bread</span>
                    <b>₹60</b>
                </div>
                     <div class="food-item">
                    <span>spring rolls</span>
                    <b>₹60</b>
                </div>
                <div class="food-item">
                    <span>French Fries</span>
                    <b>₹70</b>
                </div>
            </div> 
            <div class="card">
                <div class="food">🍝</div>
                <h3>Main Courses</h3>
                <div class="food-item">
                     <span>Veg Pasta</span>
                    <b>₹120</b>
                </div>
                <div class="food-item">
                    <span>Paneer Masala</span>
                    <b>₹150</b>
                </div>
                <div class="food-item">
                    <span>Veg Biryani</span>
                    <b>₹130</b>
                </div>
                </div>
                <div class="card">
                    <div class="food">🍰</div>
                    <h3>Desserts</h3>
                    <div class="food-item">
                         <span>Brownie</span>
                    <b>₹80</b>
                </div>
                <div class="food-item">
                    <span>Ice Cream</span>
                    <b>₹60</b>
                </div>
                <div class="food-item">
                    <span>Gulab Jamun</span>
                    <b>₹50</b>
                </div>
            </div>
               <div class="card">
                    <div class="food">🍹</div>
                    <h3>Drinks</h3>
                     <div class="food-item">
                    <span>Lemonade</span>
                    <b>₹40</b>
                </div>
                <div class="food-item">
                    <span>Cold Coffee</span>
                    <b>₹70</b>
                </div>
                <div class="food-item">
                    <span>Masala Chai</span>
                    <b>₹30</b>
                </div>
        </div>
    </section>
    <section id="about">
        <h2>Special Offer</h2>
        <div class="offer" >
            <h3>Get 20% OFF on your first order!</h3>
            <p>Use Code: FOOD20</p>
        </div>
        <h2>About Us</h2>
        <p >
            Food Haven is a friendly restaurant serving
            fresh and tasty food. We believe in good food,
            great taste and happy customers.
        </p>
    </section>
    <section id="Reservation">
        <h2>BOOK A TABLE</h2>
        <form id="bookingform">   
            <label for="name">Full Name* : </label> 
            <input type="text" id="name" placeholder="Enter Your Name" required>
             <br><br>
            <label for="Email">Email* : </label>
            <input type="email" id="email" placeholder="enter your email" required>
            <br><br>
            <label for="phone">Phone Number* : </label>
            <input type="tel" id="phone" placeholder="10-digit phone number" required>
            <br><br>
            <label for="guest">Number of Guests* : </label>
            <select id="guest" required>
                <option value="">Select guests</option>
                <option value="1">1 Guest</option>
                <option value="2">2 Guests</option>
                <option value="3">3 Guests</option>
                <option value="4">4 Guests</option>
                <option value="5">5 Guests</option>
                <option value="6">6 Guests</option>
                <option value="7">7 Guests</option>
                <option value="8">8 Guests</option>
            </select>
              <br><br>
            <label for="date">Reservation date*: </label>
            <input type="date" id="date" required>
              <br><br>
            <label for="time">Reservation Time* : </label>
            <select id="time" required>
                <option value="">Select Time</option>
                <option>11:00 AM</option>
                <option>12:00 PM</option>
                <option>1:00 PM</option>
                <option>2:00 PM</option>
                <option>5:00 PM</option>
                <option>6:00 PM</option>
                <option>7:00 PM</option>
                <option>8:00 PM</option>
                <option>9:00 PM</option>
                <option>10:00 PM</option>
            </select>
              <br><br>
            <label for="text">Special Request : </label><br>
            <textarea id="text" placeholder="Any special Request" ></textarea>
             <br><br>
             <button type="submit">Confirm Reservation</button> 
             <p id="message" role="status"></p>
        </form>
    </section>
     <section id="contact">  
        <h1>Contact Us</h1>
        <p>Address: 123 Food Street, New Delhi</p>
        <p>Phone: +91 98765 43210</p>
        <p>Email: info@foodhaven.example</p>
        <h3>Opening Hours</h3>
        <p>Monday - Friday: 10 AM - 11 PM</p>
        <p>Saturday - Sunday: 9 AM - 11 PM</p>
     </section>
      <div style="background-color: black; height: 80px; padding: 10px;">
        <p style="color: white; text-align: center;">© 2026 Food Haven Restaurant</p>
        <p style="color: white;text-align: center;">Student Project</p>
      </div>
      <script>
        const dateInput = document.getElementById("date");
        const today = new Date();
        const year = today.getFullYear();
        const month = String(today.getMonth()+1).padStart(2,"0");
        const day = String(today.getDate()).padStart(2,"0");
        dateInput.min = year + "-" + month + "-" + day ;    
        // check the reservation food
        const form = document.getElementById("bookingform");
        form.addEventListener("submit" , function(event){
            event.preventDefault();
            const name = document.getElementById("name").value.trim();
            const email = document.getElementById("email").value.trim();
            const phone = document.getElementById("phone").value.trim();
             const guest = Number(document.getElementById("guest").value);
             const date = dateInput.value;
             const time = document.getElementById("time").value;
             const message = document.getElementById("message");
             if(name.length< 2){
                message.style.color= "red";
                message.textContent = "Please enter your name";
             }
             else if(!email.includes("@") || !email.includes(".")){
                message.style.color = "red";
                message.textContent = "Please enter valid email";
             }
             else if(!/^\d{10}$/.test(phone)){ 
                message.style.color = "red";
                message.textContent = "Please enter 10 digits number";
             }
             else if (guest < 1 || guest > 8) {
                message.style.color = "red";
                message.textContent = "Select 1 to 8 guests.";
             }
            else if( date === "" || date < dateInput.min){
                message.style.color="red";
                message.textContent = "Select today or a future date.";
            }
            else if (time === "") {
                message.style.color = "red";
                message.textContent = "Please select a time.";
            }
            else {
                message.style.color = "green";
                message.textContent = "Table booked successfully! Thank you, " + name + ".";
        form.reset();
            }
        })
      </script>
</body>
</html>

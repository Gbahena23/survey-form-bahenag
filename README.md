# Survey-form-Bahenag
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Top 5 Best Shoe Brand</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <h1>Top 5 Best Shoe Brand Survey</h1>
    <p id="description" class="description text-center">Helps us understand what brand of shoes are the best in the world!</p>
    <form id="survey form">
      <label for="first-name">
        <p>Name <br><input type="text" id="name" name="name" placeholder="Enter your name" required>
      </label>
      <label for="email-label">
        <p>Email<br><input type="text" id="email" name="email" placeholder="Enter your email" required>
      </label>
      <label id="number-label">
        <p>Age<br><input class="form-control" type="text" id="number" min="1" max="100" name="age" placeholder="Enter your age" required>
      </label>
      <label>
        <p> Which shoe brand do you prefer?</p>
        <select id="referrer">
          <option value="">
            (Select one)</option>
          <option value="1">Nike</option>
          <option value="2">New Balance</option>
          <option value="3">Adidas</option>
          <option value="4">Vans</option>
          <option value="5">Puma</option>
        </select>
      </label>
      <label>
        <p>What factors mostly influence your shoe purchasing decision? (select all that apply)</p>
      </label>
      <div class="check-group">
        <input type="checkbox" value="option1">Comfort<br>
        <input for="price" type="checkbox" value="option2">Price<br>
        <input for="style/design" type="checkbox" value="option3">Style/Design<br>
        <input for="brand and reputation" type="checkbox" value="option4">Brand reputation<br>
        <input type="checkbox" for="performance" value="option5">Performance (e.g., running, training)<br>
      </div>
      <label>
        <p>How often do you purchase shoes?</p>
      </label>
      <div class="radio-group">
        <input type="radio" name="radio-group" value="1">Once a year<br>
        <input type="radio" name="radio-group" value="2">2-3 times year<br>
        <input type="radio" name="radio-group" value="3">Less than once a year<br>
        <input type="radio" name="radio-group" value="4">4 or more times a year<br>
      </div>
      <label>
        <p>Any comments or suggestions here:
          <textarea rows="4" cols="50" placeholder="Enter your comments here..."></textarea>
      </label>
     <div class="form-group">
      <button id="submit" class="submit-button" type="submit">Submit</button>
    </form>
  </div>
</body>
<style>
body {
  font-family: Montserrat, sans-serif;
  background-color: #c0a083;
}
.container {
  background-color: rgba(161, 104, 51, 0.5);
  padding: 20px;
  border-radius: 70px;
  width: 900px;
  height: 1300px;
  margin: 0 auto;
}
h1, description {
  text-align: center;
}
.description{
font-family: "Roboto Serif";
font-size: 24px;
font-style: normal;
font-weight: 500;
line-height: normal;
margin-left: 140px
}
p  {
  font-size: 20px;
 margin-left: 220px;
}
div[class="radio-group"]{
font-family: Fira, sans serif;
font-size: 20px;
font-weight: 400;
height: 30;
width: 24;
line-height: nomral;
}
div[class="check-group"]{font-family: Fira, sans serif;
font-size: 20px;
font-weight: 400;
height: 30;
width: 24;
line-height: nomral;}
input[type="text"],
select, textarea
 {
  font-size: 16px ;
  font-family: Fira, Sans ;
  opacity: 0.3;
  background-color: #000;
  color: white;
  width: 465px;
  height: 35px;
  border: none}
select{
margin-left: 220px;
}
input[type="checkbox"], input[type="radio"]{height: 30px;
width: 24px; 
margin-left: 220px;
}
textarea{
 width: 465px;
 height: 170px;
 line-height: 1.3;
 border: none}
.submit-button{
  display: block;
  width: 30%;
background-color: #C0A083;
line-height: 40px;
 margin-left: 320px;
 font-size: 20px;
  border: none;
  font-family: inter }
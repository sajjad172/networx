<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

 {
  box-sizing: border-box;
}


input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: gray;
}


.container {
  border-radius: 5px;
  background-color: pink;
  padding: 10px;
}


.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
</head>
<body>



<div class="container">
  <div style="text-align:center">
    <h2>Contact Us</h2>
    <p><em>Have a concern about the website or need help message us :</em></p>
  </div>
  <div class="row">
    <div class="column">
      <img src="https://user-images.githubusercontent.com/78987191/109760700-0396ce80-7ba4-11eb-8d51-894ecd9bbb7a.jpg" style="width:100%">
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="fname"> Name</label>
        <input type="text" id="fname" name="Name" placeholder="Your name...">
       
<label for="lsname">Email</label>
        <input type="text" id="lsname" name="Email" placeholder="Your email...">
        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="australia">USA</option>
          <option value="canada">Canada</option>
          <option value="usa">Australia</option>
          <option value="usa">Europe</option>
</select>
        <label for="subject">Message</label>
<textarea id="subject" name="subject" placeholder="Write us...
        style="height:170px"></textarea>
<input type="submit" value="Submit">
</form>
</div>
  </div>
</div>

</body>
</html>



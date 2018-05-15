# skeelasaurus.github.io
<!-- Skylla -->
<!DOCTYPE html>
<html>
  <head>
    <h1> Contact Stik-Soft </h1>
    <link rel="stylesheet"
          href="style.css">
  </head>
  <body>
    <div class="topnav">
      <a  href="index.html">Home</a>
      <a href="Members.html">Members</a>
      <a class="active" href="Contact.html">Contact</a>
      <div class="search-container">
        <form action="/action_page.php">
          <input type="text" placeholder="Search.." name="search">
          <button type="submit"><i class="fa fa-search"></i></button>
        </form>
      </div>
    </div>
    <br>
    <div class="container">
      <form action="action_page.php">

        <label for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your name..">

        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">

        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="australia">Australia</option>
          <option value="canada">Canada</option>
          <option value="usa">USA</option>
          <option value="other">Othe</option>
        </select>

        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

        <input type="submit" value="Submit">

      </form>
    </div>
    
  </body>
</html>

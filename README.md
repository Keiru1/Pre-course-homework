# Pre-course-homework
D2 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muziekly Registrattion</title>
</head>
<body>
    <h1>Muziekly Registration Form</h1>
    <form>
    <div>
          <input type="text" placeholder="Insert your name here">
    </div>
    <div>
<input type="text" placeholder="Insert Your surname">
    </div>
    <div>
<input type="email" placeholder=" Your email address">
</div>
 <div>
    <input type="password" placeholder="Your password"/>
 </div>
 <div>
    <input type="date" placeholder="Date of birth"
 </div>

  <div>
 <input type="Number" placeholder=" Your number">
  </div>
  <div>
    <h2> What music genres do you listen to?</h2>
    <input id ="RnB" type="checkbox">
    <label for="RnB">RnB</label>
    <div>
    <input id ="Hip Hop" type="checkbox">
    <label for="Hip Hop">Hip Hop</label>
  </div>
  <div>
    <input id ="Rap" type="checkbox">
    <label for="Rap">Rap</label>
  </div>
  <div>
  <input id ="Rock" type="checkbox">
    <label for="Rock">Rock</label>
    </div>
    <div>
        <input id ="Pop" type="checkbox">
        <label for="Pop">Pop</label> 
    </div>
    <div>
        <input id ="other" type="checkbox">
        <label for="other">Other( please state below )</label> 
    </div>
    <div>
        <input type=" text" placeholder=" Please state"
    </div>
  <div>
    <button onclick="alert('Registration Sent')">Send registration</button>
  </div>
    </form onsubmit= "alert('Registration sent!')">
    <div>
        <button onclick="alert('Success')">Click Me</button>
    </div>
</body>
</html>

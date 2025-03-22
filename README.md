# assignment-two-index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
div{
backface-visibility: visible;
background-color: rgb(64, 64, 88);
}


    </style>
</head>
<body>
<header>
<h1 style="background-color: chocolate;">WELCOME TO GLF BOOKSHOP</h1>
<h2 style="background-color: coral;">ONE STOP BOOKING SHOP FOR ALL OF YUR BOOKS</h2>


</header>


<main>
    
<p>SOME OF THE POPULAR CATEGORIES WE OFFER ARE LISTED BELOW</p>
<div style="background-color: green;">
<ol type="I">
    <li>Study Bibles.</li>
   <li>Tea & Coffee Mugs.</li> 
   <li> Bible Bags / Book Covers.</li>
    <li>Stationery.</li>
    <li>Creative Products.</li>
    <li>New Releases.</li>
</ol>
</div>

<div>
 <h2 style="background-color: blueviolet;">ENCOURAGE ONE ANOTHER IN FAITH WITH SONGS AND PRAYER</h2>
 <img src="https://images.pexels.com/photos/6860380/pexels-photo-6860380.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" height="400px">
    <img src="https://media.istockphoto.com/id/1505865534/photo/open-bible-on-a-wooden-board-near-the-river.jpg?b=1&s=612x612&w=0&k=20&c=j6yALTSXlSgC2SxcTXaN0ZLhmPPfEx_DBS0qJdM4wug=" alt="bible cov er image">
<img src="https://images.pexels.com/photos/2258252/pexels-photo-2258252.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
</div>
<div style="background-color: lawngreen;">
    <h3 style="background-color: cyan;">PLEASE FEEL FREE TO CONTACT THE BELOW PERSONEL INCASE OF ANY QUERIES</h3>
  
<table border="2">
    <thead>
        <tr style="background-color: darkviolet;">
        <td> NAME  </td>
        <td>ADRESS</td>
        <td>MOBILE</td>
        <td>EMAIL</td>
    </tr>
    </thead>

    <tbody>
        <tr>
            <td>KWAME NKRUMAH</td>
            <td>156 SUNTOWN STREET</td>
            <td>+2546788886663</td>
            <td>kennhnkhrumah@gmail.com</td>
        </tr>
    </tbody>

    <tbody>
        <tr>
            <td> JAMES SULLIVAN</td>
            <td>544 nairobi road</td>
            <td>+25678886644</td>
            <td>jameshgg@gmail.com</td>
        </tr>
    </tbody>

    <tbody>
<tr>
<td>KINGSLEY COMAN</td>
<td>765 KINSHANSHA</td>
<td>+45678888888</td>
<td>kingsley@gmail.com</td>

</tr>
    </tbody>
    <tbody>
<tr>
<td> JAMES OMWAMI</td>
<td>6655 MAPUTO STREET</td>
<td>+56665444444</td>
<td>james@gmail.com</td>


</tr>
    </tbody>

    <tbody>
        <tr>
            <td> HUNI BAJUI</td>
            <td>678888 KAMPALA BUJI</td>
            <td>+567777766663</td>
            <td>huni@gmail.com</td>
        </tr>
    </tbody>

</table>

</div>
 <h3 style="text-align: center; ">REGISTRATION FORM </h3>
<h4 style="background-color: brown; text-align: center;">PLEASE REGISTER YOUR DETAILS HERE</h4>
<form action="#" method="post"></form>
<!-- input for Name field, email, password, and date fields. -->
 <label for="name">NAME:</label> 
<input placeholder="first name, last name" type="text" id="name" name="name" required>
<label for="email">EMAIL:</label>
<input placeholder="j@gmail.com" type="e-mail" id="email" required>
<label for="password">PASSWORD:</label>
<input type="password" name="password" placeholder="enter a password" minlength="8" id="password" required >
<label for="dob">BIRTH DATE:</label>
<input placeholder="DD/MM/YY" type="date" id="dob" required><br>
<!-- gender dropdown -->
<div>
    <label for="gender">GENDER: </label>
<select name="gender" id="gender" required>
    <option value="" disabled selected>SELECT YOUR GENDER</option>
<option value="M">MALE</option>
<option value="F">FEMALE</option>
<option value="other">PREFER NOT TO SAY</option>
</select>
</div>

<!-- country dropdown -->
 <div>
<label for="country">SELECT YOUR COUNTRY:</label>
<select name="country" id="country">
<option value="country" disable selected>SELECT YOUR COUNTRY</option>
<option value="country">KENYA</option>
<option value="country">USA</option>
<option value="country">UGANDA</option>
<option value="country">TANZANIA</option>
<option value="country">MADAGASCAR</option>
<option value="country">CAMEROON</option>
<option value="country">BOTSWANA</option>
<option value="country">NETHERLANDS</option>


</select>


 </div>
<!-- radio buttons for subscription -->

<div>
<label for="">SUBSCRIBE TO OUR NEWSLETTERS:</label>
<input type="radio" id="subscribe-yes" name="subscribe" value="yes" required>
<label for="subscribe-yes">YES</label>
<input type="radio" name="subscribee" id="subscribe-no" value="no" required>
<label for="subscribe-no">NO</label>

</div>

<!-- CHECK BOXES FOR INTERESTS -->

<div style=" text-align:center;" >
    <h4 style="text-align: center;">PLEASE PICK YOUR INTERESTS FROM THE BELOW</h4>
<label for="Interests">Interests:</label>
<input type="checkbox" id="technology" name="Interests" value="tech">
<label for="technology">TECHNOLOGY</label>
<input type="checkbox" id="christian music" name="Interests" value="christian music">
<label for="christian music">CHRISTIAN MUSIC</label>
<input type="checkbox" id="christian movies" name="Interests" value="movies"> 
<label for="christian movies">CHRISTIAN MOVIES</label>
<input type= "checkbox" id="sports" name="Interests" value="sports">
<label for="sports">SPORTS</label>
</div>

</main>



<!-- submit button -->
<footer>
 <div style="font-size: medium;">
    <button type="submit"> SUBMIT REGISTRATION </button>
    <button type="submit">CANCEL REGISTRATION </button>
 </div>

 <!-- social media links -->
 <h5 style="text-align: center;color: rgb(15, 15, 15);">PLEASE FEEL FREE TO REACH US THROUGH THE BELOW SOCIAL MEDIA PLATFORMS</h5>
  <div class="social media">
    <a href="#">TWITTER</a>
    <a href="#">LINKED IN</a>
    <a href="#">FACEBOOK</a>
    <a href="#">TIKTOK</a>
    <a href="#">INSTAGRAM</a>

</div>
<!-- copyright notice -->
 <div class="footer-bottom">
    &copy: 2023 MY WEBSITE. ALL RIGHTS RESERVED.


 </div>
</footer>
</form>
</body>
</html>

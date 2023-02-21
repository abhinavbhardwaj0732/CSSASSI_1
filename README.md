HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Assignment2.css">


    <div class="header">
      <a href="#default" class="logo">ABHINAV'S PAGE</a>
      <div class="header-right">
        <a class="active" href="#home">Home</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      </div>
    </div>
   
</head>
<body>
    <h3>Student Registration Form</h3>
    <form action="" method="post">
        <label>Name:</label>
        <input type="text" name="YourName" id="YourName" value="">
        <br>
        <br>
        <label>Phone No:</label>
        <input type="text" name="Yourno" value="">
        <br>
        <br>
        <label>Date of Birth:</label>
        <input type="date" name="ydate" id="ydate">
        <br>
        <br>
        <label>Address:</label>
        <textarea name="Your Message" id="" cols="20" rows="10"></textarea>
        <br>
        <br>
        <label>Gender:</label>
        <input type="radio" name="one" id="" value="male">
        <input type="radio" name="one" id="" value="female">
        <br>
        <br>
        <label>City</label>
        <select name="city">
        <option value="none">Select City</option>
        <option value="Delhi">Delhi</option>
        <option value="Noida">Noida</option>
        <option value="Bengaluru">Bengaluru</option>
        </select>
        <br>
        <br>
        <label >Hobbies</label>
        <input type="checkbox"  name="hobby1" value="Music">
        <label for="hobby1"> Music</label><br>
        <input type="checkbox" name="hobby2" value="Sports">
        <label for="hobby2"> Sports</label><br>
        <input type="checkbox" name="hobby3" value="Reading">
        <label for="hobby3"> Reading</label><br>
        <input type="checkbox" name="hobby4" value="Cooking">
        <label for="hobby4"> Cooking</label><br>
        <input type="checkbox" name="hobby5" value="Dancing">
        <label for="hobby5"> Dancing</label><br>
        
        <br><input type="submit" name="yregister" value="submit">   
        <input type="submit" name="yregister" value="cancel">
</form>
<h3>
  Student Records
</h3>

        <table class="center">
            <tr>
              <th >S.No.</th>
              <th >Name</th>
              <th >Phone No.</th>
              <th >Gender</th>
              <th >DOB</th>
              <th >Interests</th>
            </tr>
            <tr>
              <td rowspan="3">1</td>
              <td rowspan="3">Akash</td>
              <td rowspan="3">123-456-7</td>
              <td rowspan="3">Male</td>
              <td rowspan="3">12/12/1996</td>
              <td>Music</td>
              </tr>
              <tr>
                <td>Dance</td>
              </tr>
              <tr>
                 <td>Cooking</td>
              </tr>
             
              
            </tr>
            <tr>
              <td rowspan="2">1</td>
              <td rowspan="2">Akash</td>
              <td rowspan="2">123-456-7</td>
              <td rowspan="2">Male</td>
              <td rowspan="2">12/12/1996</td>
              <td>Dance</td>
              </tr>
              <tr>
                <td>Travel</td>
              </tr>
             
              
            </tr>
          </table>
    
</body>
</html>


CSS_CODE


body{
     text-align: center;
     }

input[type=text] {
        width: 50%;
        padding: 2px 20px;
        margin: 3px 0;
        box-sizing: border-box;
        background-color: #3CBC8D;
        color: black;
      }
      select {
        
        padding: 16px 20px;
        border: none;
        border-radius: 4px;
        background-color: goldenrod;
      }
      textarea {
        width: 75%;
        height: 50px;
        padding: 12px 20px;
        box-sizing: border-box;
        border: 2px solid #ccc;
        border-radius: 2px;
        background-color: greenyellow;
        font-size: 16px;
        resize: none;
      }
        
      
      
      
        table{
        
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
border-collapse: collapse;
        }




        .header {
            overflow: hidden;
            background-color: pink;
            padding: 8px 10px;
            visibility: visible;
          }
          
          
          .header a {
            float: left;
            color: black;
            text-align: center;
            padding: 12px;
            text-decoration: none;
            font-size: 18px;
            line-height: 25px;
            border-radius: 4px;
          }
          .header a.logo {
            font-size: 25px;
            font-weight: bold;
          }
          
          
          .header a:hover {
            background-color: #ddd;
            color: black;
          }
          
          
          .header a.active {
            background-color: rgb(30, 255, 150);
            color: rgb(255, 255, 255);
          }
          
         
          .header-right {
            float: right;
          }
          
          
          @media screen and (max-width: 500px) {
            .header a {
              float: none;
              display: block;
              text-align: left;
            }
            .header-right {
              float: none;
            }
          }

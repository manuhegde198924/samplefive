<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        
        </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table>
    <h3 style="border:orange; border-width:5px; border-style:solid;">Personal details</h3>
    <form>
    <label for="fname">First name</label>
    <input type="text" name="fname" >
    <br>
    <br>
    <label for="mname">Middle Name<label></label>
    <input type="text" name="mname" >
    <br>
    <br>
    <label for="lname">Last Name<label></label>
    <input type="text" name="lname">
    <br>
    <br>
    <label>course</label>
    <select name="course" id="cars">
        <option value="BCA">BCA</option>
        <option value="MBBS">MBBS</option>
        <option value="B.TECH">B TECH</option>
        <option value="MCA">MCA</option>
      </select>
      <BR>
    <h5>gender:</h5>
    <input type="radio"  name="Male" /> 
    <h5>male</h5>
    <input type="radio"  name="Female" />  
    <h5>female</h5>
    <input type="radio"  name="Other" /> 
    <h5>other</h5>
    <label>  
        DOB:   
        </label>
    <input type="datetime-local" value="2023-11-10T12:00:00"/>
    <br>
    <label>  
        phone:   
        </label>
        <input type="tel "  pattern="[0-9]"/>
        <br>
        <label for="add">Address</label>
    <input type="text" name="add" id="add">
    <br>
    <label>  
        email:   
        </label>
        <input type="text" name="email"/>
        <br>
        <label>  
            password:   
            </label>
            
            <input type="text" name="password"/>
            <br>
            <label>  
                retype password:   
                </label>
                <input type="text" name="retype password"/>
                <br>
                <br>
                <br>
<input type="checkbox"  >
<p>Agree to terms and conditions</p>
<br>
<label>choose file:</label>
<input type="file"/>
<br>
<label for="colorpicker">Color Picker:</label>
<input type="color" id="colorpicker" value="#0000ff">
<br>
<br>
<input type="button" value="Reset" >
<input type="button" value="Submit" >

</form>
  </table>
</body>
</html>

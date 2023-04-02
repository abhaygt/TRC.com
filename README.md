
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <title>Login | TRC </title>
    <link rel="icon" href="https://media-exp3.licdn.com/dms/image/C4D0BAQHPN-1GO2RukQ/company-logo_200_200/0/1618399166964?e=2159024400&v=beta&t=pxORN5dGNZQKe882WzMmVNMyq3z_O2zs-ZkRIux9AVY" type="image/x-icon"> 
    <link rel="stylesheet" href="knowledgecycle.css">

</head>
<body >
    
    
    <H1>CHECK YOUR LOAN ELIGIBILITY</H1>
     
    <style> h1{
    color: brown;background-color: aquamarine;
}
  body{background-color: seagreen;}
        body{font-size: medium;font-style: italic;}

  < type ="text/css">
Img_deg
{ Float:right;
Width:40%;
} 
<Img class ="img_deg" src="https://th.bing.com/th/id/OIP.0RRZkj8CHLzO_E_JRQTzswHaE8?pid=ImgDet&rs=1 ">
 </style>



  
   
    <form action="backend.php">
        <div>
            
      <br>
        <label for="first name" > First Name: </label>
        <input type="text" name="myName" id="First Name">
        <label for="first name"> Middle Name: </label>
        <input type="text" name="myName" id="First Name">
        <label for="first name"> Last Name: </label>
        <input type="text" name="myName" id="Last Name">
    </div>
    <br>
          Company Name: <input type="text">
          Monthly Salary: <input type="text">
          <div><br>
          Location: <input type="text">
          PinCode: <input type="text">
          </div><br>
         <div></div> Loan Amount: <input type="text">
          Tenure: <input type="text"></div>
          <div><br> 
          Pan Card No: <input type="text">
          DOB: <input type="date" name="myDate">
        </div><br>
    <div> E-mail: <input type="text" name="myEmail">
          Contact No: <input type="number" name="myContact"></div><br>
    <div>Gender: Male <input type="radio" name="myGender"> Female <input type="radio" name="myGender">Other <input type="radio" name="myGender"></div>
    <div><br>
        Write about Your EMI obliqations:<br><textarea name="myText" id="" cols="0" rows="10"></textarea>></div>
    <div> <br><br>
        <label for="NBFC">NBFC</label>
        <select name="myNBFC" id="NBFC">
            <option value="Bajaj Finserv">Bajaj Finserv</option>
            <option value="Tata Capital">Tata Capital</option>
            <option value="Axis Finance">Axis Finance</option>
            <option value="Paysense">Paysense</option>
            <option value="Fullerton India">Fullerton India</option>
            <option value="Kotak">Kotak</option>
        </select> OR 
        <label for="BANK">BANK</label>
        <select name="myBANK" id="BANK">
            <option value="HDFC">HDFC</option>
            <option value="SBI">SBI</option>
            <option value="Axis">Axis</option>
            <option value="YES BANK">YES BANK</option>
            <option value="ICICI">ICICI</option>
            <option value="IDFC">IDFC</option>
        </select><br><br>
        Are you eligible?:<input type="checkbox" name="myEligibility">
    </div><br>
    <div><input type="Submit" value="Submit Now hi">
         <input type="Reset" value="Reset Now"></div>
 </form>
    </body>
</html>

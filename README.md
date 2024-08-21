<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration form</title>
    <style>
        div{
            background-color: #339988;
            display: flex;
            flex-direction: row;
            text-align: center;
            justify-content: center;
            width: 400px;
            border-radius: 10px;
        }
        form{
            padding: 15px;
        }
    </style>
</head>
<body>
    <div>
      <center>
        <h1>Registration form</h1>
        <div class="2">
             <form action="">
                <label for="name">Name : </label>
                <input type="text" id="name" placeholder="Name" name="name"><br><br>
                <label for="mobile">Mobile : </label>
                <input type="tel" id="mobile" placeholder="mobile" name="mobile"><br><br>
                <label for="gender">Gender : </label>
                <input type="radio" name="gender">
                <label for="gender">male</label>
                <input type="radio" name="gender">
                <label for="gender">female</label><br><br>
                <label for="dob">Date of birth : </label>
                <input type="date" name="dob"><br><br>
                <label for="course">Course : </label>
                <input type="radio" name="course">
                <label for="course">B-tech</label>
                <input type="radio" name="course">
                <label for="course">M-tech</label>
                <input type="radio" name="course">
                <label for="course">MBA</label><br><br>
                <label for="branch">Branch : </label>
                <input type="text" name="branch">

             </form>
        </div>
    </div>
    </center>
</body>
</html>

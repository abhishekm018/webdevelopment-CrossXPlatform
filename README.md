                                                                  BASIC HTML LOGIN PAGE AS HTML FORM
<!--STEP 1: BOILER PLATE-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>html web development</title>
</head>
<body>
    <h1> HTML CRITERIA 1</h1> <!--HEADER-->
    <form action="backend.php">
    <label for="name">name</label>
    <br>
    <div>
    <input type="text" name="my name" id="name">
</div>
<label for="empoloye id"> employee id</label> <!--HTML FORMS-->
    <br>
    <div>
  <input type="text" name="id" id="empoloye id">
    </div>
    <label for="my email">email</label>
    <br>
    <div>
        <input type="email" name="email" id="my email">
    </div>
    <label for="date">date of birth</label>
    <div>
        <input type="date" name="working days" id="date">
    </div>
    <br>
    <div>
       elgibility: <input type="checkbox" name="elibility" id="my eliibility">
    </div>
    <br>
    <div>
        male:<input type="radio" name="gender" id="my gender">
        female:<input type="radio" name="gender" id="my gender">
        others:<input type="radio" name="gender" id="my gender">
    </div>
    <br>
<div>
    <input type="submit" value="submit now">
</div>
<br>
<div>
    <input type="reset" value="reset now">
</form>
</div>
</body>
</html>

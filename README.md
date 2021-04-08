# GoITeens-frontend5-Fedorenko
<!DOCTYPE html>
<html lang="en">
    <style>
        p {
    color: white;
    }
  body {
      background-color: rgb(8, 8, 8);
    }
    </style>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form>
        <p>Ім'я:</p>
         <input type="text" name="firstname"> <br> <br>
         <p>Яка у вас освіта?</p>
        <p>Садочок <input type="radio" name="sex" value="male" checked> <br> <br></p>
        <p>Школа <input type="radio" name="sex" value="female"> <br> <br></p>
        <p>Університет <input type="radio" name="sex" value="female"> <br> <br></p>
        <p>Напишіть про себе:<Br>
            <textarea name="comment" cols="40" rows="3"></textarea>
        </p>
        <p>Введіть секретне слово<Br>
        <input type="password" cols="40" rows="3"></textarea>
        </p>
        <p><input type="submit" value="Відправити">
            <input type="reset" value="Очистити">
        </p>
    </form>
</body>

</html>

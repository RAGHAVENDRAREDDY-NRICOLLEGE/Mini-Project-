<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create</title>
    <style>
        body {
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: sans-serif;
    line-height: 0.5;
    min-height: 100vb;
    background:whitesmoke;
    flex-direction: column;
    margin: 5px;
    }
    input {
    display: block;
    width: 100%;
    margin-bottom: 15px;
    padding: 10px;
    box-sizing: border-box;
    border: 1px solid #0a0a0a;
    border-radius: 5px;
    }

    .wrap {
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    background-color:  #4CAF50;
    padding: 10px;
    border-radius: 5px;
    }



    </style>
</head>
<body>
    <form>

        <input type="name" placeholder="enter your name"/><br><br>

        <input type="number" placeholder="Enter your number"/><br><br>

        <input type="number" placeholder="OTP"/><br><br>

        <input type="password" placeholder="create new password"/><br><br>

        <div class="wrap">
            <a href="index.html">SUBMIT</a>
        </div>

    </form>
</body>
</html>

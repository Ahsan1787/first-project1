# first-project1
this is my first GIT Repository.
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="form.css">
    </head>
    <body>
        <div class="div">
        <div class="form1">
        <form action="#" method="post">
            <h1 class="header">Payment Form</h1><hr>
            <h2>Contact Information</h2>
            <p>Name:<input type="text" name="name" required></p>
            <fieldset>
                <legend>Gender</legend>
            <p>
                Male<input type="radio" name="gender" id="male">Female<input type="radio" name="gender" id="fmale">
            </p>
        </fieldset>
        <p>
            Address:<textarea name="address" id="address" cols="30" rows="5" required></textarea>
        </p>
        <p>
            Email:<input type="email" name="email" id="email" required>
        </p>
        <p>
            Pincode:<input type="number" name="pincode" id="pincode" required>
        </p>
        <h2>Payment Information</h2>
        <p>Card type:
         <select name="card type" id="card type" required>
            <option value="">--Select a card type--</option>
            <option value="visa">Visa</option>
            <option value="rupay">Rupay</option>
            <option value="mastercard">Master Card</option>
         </select>
        </p>
        <p>
            Card number:<input type="number" name="card_number" id="card_number" required>
        </p>
        <p>
            Expiration date:<input type="date" name="exd" id="exd">
        </p>
        <p>
            CVV:<input type="password" name="CVV" id="cvv" required>

        </p>
        <input type="submit" value="Pay Now">
        <input type="reset" value="Reset">
        </form>
    </div>
</div>
    </body>
</html>

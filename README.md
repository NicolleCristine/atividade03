# index.html3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>forms</title>
</head>
<body>
    <h1>Travel Reservation Form</h1>
    <br>
    <h2>*denotes mandotory</h2>
    <br>
    <form action="action">
    <p>Full Name* <br><input type="text" name="nome_usuario" placeholder="FristName LastName" required></p>
    <p>Email address* <br><input type="email" name="email_usuario" placeholder="EMAIL_ADDRESS" required></p>
    <p>Select you packpage* <br>
        <select name="seleçao" >
        <option value="goa">Goa</option>
        <option value="andra">Andra Pradesh</option>
        <option value="haryana">Haryana</option>
        <option value="assam">Assam</option>
        </select>
    <p>arrival date* <br><input type="date"  placeholder="m/d/y" required></p>
    <p>number of persons*</p><input type="number" min="1" max="9" placeholder="UNKNOWN_TYPE"> <br>
    <p>What would you want to avail?*</p>
        Boarding<input type="checkbox"> </input><br>
        Fooding <input type="checkbox"> </input><br>
        Sight seeing <input type="checkbox"> </input><br>
    <p>Discout Coupon code :</p> <input type="text"  placeholder="UNKNOWN_TYPE" pattern="[a-zA-Z]{6}">
    <p>terms and  condtions*</p>
    <input type="checkbox"> I agree </input> <input type="checkbox"> I disagree </input> <br>
    <input type="submit"> <input type="reset"></input>
    </form>
</body>
</html>

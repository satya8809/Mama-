<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ATM Interface</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="atm-container">
        <h2>ATM</h2>
        <div class="screen">
            <div id="message">Welcome! Please insert your card.</div>
        </div>
        <div class="buttons">
            <button onclick="insertCard()">Insert Card</button>
            <button onclick="checkBalance()">Check Balance</button>
            <button onclick="withdraw()">Withdraw</button>
            <button onclick="deposit()">Deposit</button>
            <button onclick="ejectCard()">Eject Card</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

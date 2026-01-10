<!--
  REAL_ALGEBRA_MATH_PROBLEMS: index
  Description: REAL MATH GAMES NOT FAKE :D
-->
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>PREMIUM | Algebra Math Problems</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- Your HTML Here -->
    <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Login Overlay</title>

<style>
/* ===== LOGIN OVERLAY STYLE ===== */
#loginOverlay {
    position: fixed;
    inset: 0;
    background: linear-gradient(135deg, #0f0f1a, #1b1b2f);
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 999999;
    font-family: Arial, sans-serif;
}

#loginBox {
    background: #121225;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 0 25px rgba(0,0,0,0.6);
    width: 300px;
    text-align: center;
    color: white;
}

#loginBox h2 {
    margin-bottom: 20px;
}

#loginBox input {
    width: 90%;
    padding: 10px;
    margin: 8px 0;
    border-radius: 6px;
    border: none;
    outline: none;
}

#loginBox button {
    margin-top: 10px;
    width: 95%;
    padding: 10px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    background: #4f46e5;
    color: white;
    font-size: 16px;
}

#loginBox button:hover {
    background: #6366f1;
}

#errorMsg {
    color: #ff4d4d;
    margin-top: 10px;
    font-size: 14px;
}
</style>
</head>

<body>

<!-- ===== LOGIN OVERLAY ===== -->
<div id="loginOverlay">
    <div id="loginBox">
        <h2>Login</h2>
        <input id="user" placeholder="Username">
        <input id="pass" type="password" placeholder="Password">
        <button onclick="login()">Login</button>
        Why do you need a login? We have premium math problems, and you got your account from our premium website.
        <div id="errorMsg"></div>
    </div>
</div>

<script>
/* ===== SET YOUR ACCOUNTS HERE ===== */
const accounts = {
    admin: "admin12345",
    guest: "guest1",
    user: "mypassword",
    games: "realgamesin2026",
};

function login() {
    const u = document.getElementById("user").value;
    const p = document.getElementById("pass").value;

    if (accounts[u] && accounts[u] === p) {
        document.getElementById("loginOverlay").style.display = "none";
    } else {
        document.getElementById("errorMsg").innerText = "Invalid login credientials.";
    }
}
</script>

<html>
<body>

    <!-- Main Content -->
    <div class="main-content">
        <h1>Epic Games!</h1>
    <h2 style="color: white; text-align: center; margin-bottom: 30px; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); font-weight: normal; font-size: 18px;">
    Go to the games website (use same password as here):
    <a href="https://aqplemine.github.io/xtrememath.github.io/" 
        target="_blank" 
        style="display: inline; color: #79aadb; text-decoration: none; font-size: 18px; text-shadow: 1px 1px 2px rgba(0,0,0,0.2);">
        Here!
    </a>
    </h2>
    <h2 style="color: white; text-align: center; margin-bottom: 30px; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); font-weight: normal; font-size: 18px;">
    [IN FIXING] Get my Games Kit!
    <a href="https://google.com/IN_FIXING" 
        target="_blank" 
        style="display: inline; color: #79aadb; text-decoration: none; font-size: 18px; text-shadow: 1px 1px 2px rgba(0,0,0,0.2);">
        [SOON]
    </a>
    </h2>

this is for educational purposes only.
SCROLL DOWN FOR MORE STUFF!
COMING SOON: Embedded games, right in this website.
contact me if u wanna see the games kit (:
Also, you need a way to actually access the game stash, so this is a good unblocked way to access it.
if any of these files needs a password, its the same one in here. aka, realgamesin2026 is the password.
</body>
</html>

<a href="https://www.google.com/Contact_Me_To_Get_It_(:" target="_blank"><button>[CONTACT ME TO VIEW][USE THE SAMEPASSCODE AS LISTED HERE] View my uploaded games (external, but by me)</button></a>
<button 
        onclick='fetch("https://cdn.jsdelivr.net/gh/bubbls/ugs-singlefile@main/AASINGLEFILE.html?t="+Date.now()).then(response => response.text()).then(text => {const newWin = window.open("about:blank", "_blank");if (newWin) {newWin.document.open();newWin.document.write(text);newWin.document.close();}});' 
        style="width: 100%; height: 100%; font-size: 100;"
        >View other online unblocked games (external, should be always unblocked!)</button>
  </body>
</html>
Wanna view any (visitable on your device) website, but it shows as about:blank? Well: (better version + unblocked i think soon!)

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>about:blank</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #111;
            color: white;
            padding: 20px;
        }
        input, button {
            font-size: 16px;
            padding: 8px;
        }
    </style>
</head>
<body>

<h2>about:blank URL Viewer</h2>
This lets you see any (allowed) page, while it shows as an about:blank page! (IN WIP)
<input id="url" placeholder="https://example.com (saying https is not needed, saying http is needed.)" size="100">
<button onclick="openBlank()">Open</button>

<script>
function openBlank() {
    let url = document.getElementById("url").value.trim();
    if (!url) return;

    if (!url.startsWith("http://") && !url.startsWith("https://")) {
        url = "https://" + url;
    }

    const win = window.open("about:blank", "_blank");

    win.document.open();
    win.document.write(`
        <!DOCTYPE html>
        <html>
        <head>
            <title>about:blank</title>
            <style>
                html, body {
                    margin: 0;
                    height: 100%;
                    background: black;
                }
                iframe {
                    width: 100%;
                    height: 100%;
                    border: none;
                }
            </style>
        </head>
        <body>
            <iframe src="${url}" allowfullscreen></iframe>
        </body>
        </html>
    `);
    win.document.close();
}
</script>

</body>
</html>

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
<html>
<body>

<script>
  // 1. Define your users and passwords here
  const users = {
    "admin": "admin12345",
    "guest": "guest1",
    "mathpro": "algebra2026isgood"
  };

  alert("Note, you are accessing our premium math problems, so it requires a login.");

  if (confirm("Would you like to sign in, or leave our website?")) {
    let userEntry = prompt("Please enter your Username:");
    let passEntry = prompt("Please enter your Password:");

    // 2. Check if the username exists AND if the password matches
    if (users[userEntry] && users[userEntry] === passEntry) {
      alert("Access Granted! Welcome, " + userEntry + ".");
    } else {
      alert("Invalid login credentials.");
      window.location.href = "https://www.google.com/Access_Denied";
    }
  } else {
    window.location.href = "https://www.google.com/Access_Denied";
  }
</script>

</script>
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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Venux - Home</title>
  <style>
    body {
      margin: 0;
      background-color: #d4d4d4;
      font-family: Arial, sans-serif;
      font-size: 13px;
      color: #222;
    }

    #main-header {
      background: linear-gradient(to bottom, #1a4a84 0%, #0b2c5a 100%);
      padding: 10px 20px;
      border-bottom: 2px solid #071b36;
      display: flex;
      align-items: center;
    }

    #main-header img {
      height: 52px;
      object-fit: contain;
    }

    #sub-header {
      background: linear-gradient(to bottom, #1a4a84 0%, #0b2c5a 100%);
      padding: 8px 15px;
      border-bottom: 1px solid #000000;
    }

    #sub-header a {
      color: white;
      text-decoration: none;
      margin-right: 20px;
      font-weight: bold;
    }

    #sub-header a:hover {
      text-decoration: underline;
    }

    #notice {
      background: linear-gradient(to bottom, #ffa200 0%, #cc7a00 100%);
      color: white;
      padding: 10px 20px;
      font-weight: bold;
      text-align: center;
      border-bottom: 2px solid #a85f00;
    }

    #notice button {
      margin-left: 15px;
      padding: 3px 8px;
      font-size: 12px;
      border: none;
      border-radius: 3px;
      background: white;
      color: #cc7a00;
      cursor: pointer;
      font-weight: bold;
    }

    #notice button:hover {
      background: #ffe0b2;
    }

    #page-content {
      padding: 20px;
    }

    h2 {
      font-size: 15px;
      margin-bottom: 15px;
      color: #1a1a1a;
      border-bottom: 1px solid #aaa;
      padding-bottom: 5px;
    }

    .news-box {
      background: linear-gradient(to bottom, #ffffff 0%, #e2e2e2 100%);
      border: 2px solid #999;
      padding: 12px;
      margin-bottom: 15px;
      width: 600px;
      box-shadow: 2px 2px 0px #aaa;
    }

    .news-title {
      font-weight: bold;
      font-size: 14px;
      margin-bottom: 6px;
    }

    .news-date {
      font-size: 11px;
      color: #666;
      margin-bottom: 10px;
    }

    .news-body {
      font-size: 13px;
    }

    #footer {
      text-align: center;
      font-size: 12px;
      color: #444;
      padding: 10px;
      border-top: 2px solid #999;
      background: linear-gradient(to bottom, #f3f3f3 0%, #d8d8d8 100%);
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <div id="main-header">
    <img src="https://raw.githubusercontent.com/ayytrix/ventest1/refs/heads/main/venux.png" alt="Venux">
  </div>

  <div id="sub-header">
    <a href="Home.html">Home</a>
    <a href="unfinished.html">Games</a>
    <a href="unfinished.html">Catalog</a>
    <a href="unfinished.html">Users</a>
    <a href="unfinished.html">Forum</a>
    <a href="unfinished.html">Clans</a>
    <a href="unfinished.html">Help</a>
    <a href="unfinished.html">Downloads</a>
    <a href="Create.html">Create</a>
  </div>

  <!-- Notice bar -->
  <div id="notice">Loading...</div>

  <!-- Dynamic notice text loader -->
  <script>
    const textLink = "https://raw.githubusercontent.com/ayytrix/ventest1/refs/heads/main/anc";
    const notice = document.getElementById("notice");

    fetch(textLink)
      .then(response => response.ok ? response.text() : "Failed to load message.")
      .then(data => {
        notice.textContent = data;
      })
      .catch(() => {
        notice.textContent = "Failed to load message.";
      });
  </script>

  <!-- Content -->
  <div id="page-content">
    <h2>Latest News</h2>

    <div class="news-box">
      <div class="news-title">Welcome to Venux!</div>
      <div class="news-date">Posted: 8th October, 2025</div>
      <div class="news-body">
        This is for news happening in Venux!
      </div>
    </div>

    <div class="news-box">
      <div class="news-title">Update Log</div>
      <div class="news-date">Posted: 8th October, 2025</div>
      <div class="news-body">
        - Added more pages<br>
        - Greatblox is also great! https://greatblox.com/<br>
        - Our website is live!
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div id="footer">
    © 2025, Venux All rights reserved
  </div>

  <!-- Firebase user welcome script -->
  <script type="module">
    import { initializeApp } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-app.js";
    import { getAuth, onAuthStateChanged, signOut } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-auth.js";
    import { getFirestore, doc, getDoc } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-firestore.js";

    const firebaseConfig = {
      apiKey: "AIzaSyBPmJ-QYXZ41gx-4PjCpUPuw7DLnDq0JFg",
      authDomain: "venux1.firebaseapp.com",
      projectId: "venux1",
      storageBucket: "venux1.firebasestorage.app",
      messagingSenderId: "231055963335",
      appId: "1:231055963335:web:34c2f52fca2191b3d0bae2",
      measurementId: "G-N36RRV95SW"
    };

    const app = initializeApp(firebaseConfig);
    const auth = getAuth(app);
    const db = getFirestore(app);
    const noticeBar = document.getElementById("notice");

    onAuthStateChanged(auth, async (user) => {
      if (user) {
        const userDoc = await getDoc(doc(db, "users", user.uid));
        const username = userDoc.exists() ? userDoc.data().username : "User";
        noticeBar.textContent = `Welcome, ${username}!`;

        // Create a logout button
        const logoutBtn = document.createElement("button");
        logoutBtn.textContent = "Log Out";
        logoutBtn.onclick = async () => {
          await signOut(auth);
          window.location.reload();
        };
        noticeBar.appendChild(logoutBtn);
      } else {
        noticeBar.textContent = "You are not logged in.";
      }
    });
  </script>

</body>
</html>

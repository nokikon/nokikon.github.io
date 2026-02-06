<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Fakebook</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f0f2f5;
    }

    /* Top navbar */
    .navbar {
      background: #1877f2;
      color: white;
      padding: 12px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .navbar h1 {
      font-size: 24px;
    }

    .navbar input {
      width: 300px;
      padding: 8px;
      border-radius: 20px;
      border: none;
      outline: none;
    }

    /* Layout */
    .container {
      display: flex;
      max-width: 1200px;
      margin: 20px auto;
      gap: 20px;
    }

    .sidebar {
      width: 250px;
    }

    .sidebar div {
      background: white;
      padding: 12px;
      border-radius: 8px;
      margin-bottom: 10px;
      cursor: pointer;
    }

    .feed {
      flex: 1;
    }

    .post-box {
      background: white;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 20px;
    }

    .post-box textarea {
      width: 100%;
      border: none;
      resize: none;
      outline: none;
      font-size: 16px;
    }

    .post {
      background: white;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .post h3 {
      margin-bottom: 5px;
    }

    .post p {
      margin: 10px 0;
    }

    .post-actions {
      display: flex;
      justify-content: space-around;
      border-top: 1px solid #ddd;
      padding-top: 10px;
      color: #555;
      cursor: pointer;
    }

    .rightbar {
      width: 250px;
    }

    .rightbar div {
      background: white;
      padding: 12px;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #777;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <div class="navbar">
    <h1>Fakebook</h1>
    <input type="text" placeholder="Search Fakebook">
  </div>

  <!-- Main layout -->
  <div class="container">

    <!-- Left sidebar -->
    <div class="sidebar">
      <div>👤 Profile</div>
      <div>📰 Feed</div>
      <div>👥 Friends</div>
      <div>📸 Photos</div>
      <div>⚙️ Settings</div>
    </div>

    <!-- Feed -->
    <div class="feed">

      <div class="post-box">
        <textarea rows="3" placeholder="What's on your mind?"></textarea>
      </div>

      <div class="post">
        <h3>Your Name</h3>
        <p>This is my first Fakebook post 😎</p>
        <div class="post-actions">
          <span>👍 Like</span>
          <span>💬 Comment</span>
          <span>↗ Share</span>
        </div>
      </div>

      <div class="post">
        <h3>Friend Name</h3>
        <p>GitHub Pages is actually pretty cool.</p>
        <div class="post-actions">
          <span>👍 Like</span>
          <span>💬 Comment</span>
          <span>↗ Share</span>
        </div>
      </div>

    </div>

    <!-- Right sidebar -->
    <div class="rightbar">
      <div>
        <strong>Contacts</strong>
        <p>• Alice</p>
        <p>• Bob</p>
        <p>• Charlie</p>
      </div>

      <div>
        <strong>Sponsored</strong>
        <p>Build websites for free 🚀</p>
      </div>
    </div>

  </div>

  <footer>
    © 2026 Fakebook • This is a demo UI only
  </footer>

</body>
</html>

  </div>

</body>
</html>

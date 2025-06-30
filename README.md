<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Video Streaming App</title>
  <link rel="stylesheet" href="css/style.css">
  <script src="js/app.js" defer></script>
</head>
<body>
  <header>
    <h1>Video Streaming</h1>
    <form id="searchForm">
      <input type="text" id="searchInput" placeholder="Search videos...">
      <button type="submit">Search</button>
    </form>
    <nav>
      <a href="login.html">Login</a>
      <a href="register.html">Register</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>
  <section id="categories"></section>
  <section id="videos" class="video-grid"></section>
</body>
</html>

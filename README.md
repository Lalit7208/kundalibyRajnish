<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kundali by Acharya Rajnish Dubey</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>कुंडली जनरेटर - Acharya Rajnish Dubey</h1>
  <form id="kundaliForm">
    <input type="text" id="name" placeholder="नाम" required />
    <input type="date" id="dob" required />
    <input type="time" id="tob" required />
    <input type="text" id="pob" placeholder="जन्म स्थान" required />
    <button type="submit">कुंडली बनाएं</button>
  </form>

  <div id="result"></div>

  <footer>
    Powered by Rajnish Dubey & Pattu
  </footer>

  <script src="script.js"></script>
</body>
</html>

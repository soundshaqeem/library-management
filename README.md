# library-management
<!DOCTYPE html>
<html>
<head>
  <title>Library Management System</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <h1>Library Management System</h1>

  <div class="book-form">
    <input type="text" id="book-title" placeholder="Title" />
    <input type="text" id="book-author" placeholder="Author" />
    <button onclick="addBook()">Add Book</button>
  </div>

  <table id="book-table">
    <tr>
      <th>Title</th>
      <th>Author</th>
      <th>Action</th>
    </tr>
  </table>

  <script src="script.js"></script>
</body>
</html>




---------------------------------------------------------------------------------------------------------


body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  margin: 0;
  padding: 0;
}

h1 {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
  margin: 0;
}

.book-form {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20px;
}

.book-form input[type="text"] {
  padding: 10px;
  margin: 5px;
  width: 200px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

.book-form button {
  padding: 10px 20px;
  margin: 5px;
  background-color: #333;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.book-form button:hover {
  background-color: #444;
}

#book-table {
  width: 80%;
  margin: 20px auto;
  border-collapse: collapse;
  background-color: #fff;
}

#book-table th,
#book-table td {
  padding: 10px;
  text-align: left;
  border-bottom: 1px solid #ddd;
}

#book-table th {
  background-color: #333;
  color: #fff;
}

#book-table tr:hover {
  background-color: #f2f2f2;
}

#book-table td:last-child {
  text-align: center;
}

#book-table button {
  padding: 5px 10px;
  background-color: #dc3545;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

#book-table button:hover {
  background-color: #c82333;
}

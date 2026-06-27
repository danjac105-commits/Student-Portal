<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Student Information Page</title>
   <style>
    /* General Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    text-align: center;
}
/* Navigation Bar */
nav {
    background-color: #2c3e50;
    padding: 15px;
}
nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 20px;
}
nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
}
nav ul li a:hover {
    color: #f1c40f;
}
/* Heading */
h1 {
    color: #2c3e50;
    margin-top: 20px;
}
/* Image */
img {
    width: 70%;
    max-width: 700px;
    border-radius: 10px;
    margin: 20px 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
/* Table Styling */
table {
    width: 80%;
    margin: 20px auto;
    border-collapse: collapse;
    background-color: white;
}
th {
    background-color: #3498db;
    color: white;
    padding: 12px;
}
td {
    padding: 10px;
    border: 1px solid #ddd;
}
tr:nth-child(even) {
    background-color: #f2f2f2;
}
tr:hover {
    background-color: #d6eaf8;
}
  </style>
</head>
<body>
 <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
<!-- Page Heading -->
    <h1>Student Information Portal</h1>
<!-- Image -->
    <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=800"
         alt="Students Studying">
  <!-- Student Data Table -->
    <table>
        <tr>
            <th>Student Name</th>
            <th>Student Class</th>
            <th>Student Grade</th>
         </tr>
         <tr>
            <td>John Doe</td>
            <td>SS2</td>
            <td>A</td>
         </tr>
         <tr>
            <td>Mary Johnson</td>
            <td>SS1</td>
            <td>B+</td>
         </tr>
         <tr>
            <td>David Smith</td>
            <td>JSS3</td>
            <td>A-</td>
         </tr>
         <tr>
            <td>Grace Brown</td>
            <td>SS3</td>
            <td>A+</td>
         </tr>
    </table>
</body>
</html>

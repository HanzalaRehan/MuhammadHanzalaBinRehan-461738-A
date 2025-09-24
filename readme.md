/* Global styles */
body {
    font-family: "Segoe UI", Tahoma, sans-serif;
    margin: 0;
    padding: 0;
    background: #f8f9fb;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background: linear-gradient(to right, #2c3e50, #34495e);
    color: white;
    padding: 25px 10px;
    text-align: center;
    border-bottom: 4px solid #e67e22;
}

header h1 {
    margin: 0;
    font-size: 2.2em;
}

/* Navigation */
nav {
    background: #ecf0f1;
    padding: 10px 0;
    border-bottom: 2px solid #dcdcdc;
    text-align: center;
}

nav a {
    margin: 0 18px;
    text-decoration: none;
    font-weight: bold;
    color: #2c3e50;
    padding: 8px 14px;
    border-radius: 5px;
    transition: background 0.3s;
}

nav a:hover {
    background: #e67e22;
    color: white;
}

/* Container */
.container {
    max-width: 1000px;
    margin: 20px auto;
    padding: 20px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
}

/* Footer */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 12px;
    margin-top: 20px;
    border-top: 4px solid #e67e22;
}

/* Home page image + text */
.profile-img {
    float: left;
    margin: 10px 20px 10px 0;
    border-radius: 50%;
    border: 4px solid #e67e22;
    width: 220px;
    height: 220px;
    object-fit: cover;
}

.bio-text {
    overflow: hidden; /* clears float */
}

/* Lists */
ul {
    list-style-type: square;
    padding-left: 20px;
}

ul li {
    padding: 6px 0;
    border-bottom: 1px dashed #ccc;
}

/* Gallery */
.gallery {
    margin: 20px 0;
}

.gallery img {
    float: left;
    width: 30%;
    margin: 1.66%;
    border-radius: 8px;
    border: 3px solid #ddd;
    transition: transform 0.3s, border-color 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
    border-color: #e67e22;
}

/* Clearfix for floats */
.clearfix::after {
    content: "";
    display: block;
    clear: both;
}

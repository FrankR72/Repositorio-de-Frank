<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cool Repository</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0; /* Light gray background */
        }
        
        #container {
            display: flex;
            width: 100%;
        }
        
        #index {
            flex: 1; /* Take up 1/3 of the container */
            background-color: #333; /* Dark gray background */
            color: #fff; /* White text */
            padding: 20px;
        }
        
        #content {
            flex: 2; /* Take up 2/3 of the container */
            padding: 20px;
        }
        
        h1, h2, h3 {
            color: #333; /* Dark gray text */
        }
        
        a {
            color: #007bff; /* Blue link */
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div id="container">
        <div id="index">
            <h2>Index</h2>
            <ul>
                <li><a href="#section1">Section 1</a></li>
                <li><a href="#section2">Section 2</a></li>
                <li><a href="#section3">Section 3</a></li>
            </ul>
        </div>
        <div id="content">
            <h1>Welcome to the Cool Repository!</h1>
            <p>This is a demo HTML page for the Cool Repository.</p>
            <h2 id="section1">Section 1</h2>
            <p>This is section 1.</p>
            <h2 id="section2">Section 2</h2>
            <p>This is section 2.</p>
            <h2 id="section3">Section 3</h2>
            <p>This is section 3.</p>
        </div>
    </div>
</body>
</html>

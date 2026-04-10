# RoadSafety.github.io
<!DOCTYPE html>
<html>
<head>
    <title>Safer Roads PH</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background-color: #0d0d0d;
            color: white;
        }

        header {
            background-color: #1f1f1f;
            text-align: center;
            padding: 20px;
            border-bottom: 2px solid #00bcd4;
        }

        header h1 {
            margin: 0;
            color: #00bcd4;
        }

        header p {
            margin-top: 5px;
            color: #cccccc;
        }

        .container {
            display: flex;
            height: 90vh;
            background-color: #121212;
        }

        .nav {
            width: 220px;
            background-color: #1a1a1a;
            display: flex;
            flex-direction: column;
            padding: 10px;
        }

        .nav button {
            margin: 6px 0;
            padding: 12px;
            border: none;
            background-color: #2c2c2c;
            color: white;
            cursor: pointer;
            font-weight: bold;
            border-radius: 6px;
        }

        .nav button:hover {
            background-color: #00bcd4;
            color: black;
        }

        .content {
            flex: 1;
        }

        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>

<body>

<header>
    <h1>Road Safety for the Philippines</h1>
    <p>My advocacy for  safer roads for everyone</p>
</header>

<div class="container">
    
    <div class="nav">
        <button onclick="loadPage('home.html')">Home</button>
        <button onclick="loadPage('issues.html')">Road Issues</button>
        <button onclick="loadPage('solutions.html')">Solutions</button>
        <button onclick="loadPage('gallery.html')">Images</button>
    </div>

    <div class="content">
        <iframe id="frame" src="home.html"></iframe>
    </div>

</div>

<script>
    function loadPage(page) {
        document.getElementById("frame").src = page;
    }
</script>

</body>
</html>

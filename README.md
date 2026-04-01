<!DOCTYPE html>
<html>
<head>
    <title>My Awesome Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Arial', sans-serif; 
            line-height: 1.6; 
            color: #333;
        }
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 { font-size: 3em; margin-bottom: 10px; }
        .content { max-width: 800px; margin: 0 auto; padding: 50px 20px; }
        .btn { 
            display: inline-block; 
            background: #ff6b6b; 
            color: white; 
            padding: 15px 30px; 
            text-decoration: none; 
            border-radius: 50px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="hero">
        <h1>🚀 Welcome to My Website!</h1>
        <p>This is LIVE on the internet for FREE</p>
        <a href="#about" class="btn">Learn More</a>
    </div>
    
    <div class="content" id="about">
        <h2>About Me</h2>
        <p>Your website content goes here. Edit index.html anytime!</p>
        <ul>
            <li>✅ Free hosting forever</li>
            <li>✅ Custom domain later</li>
            <li>✅ Mobile responsive</li>
        </ul>
    </div>
</body>
</html>

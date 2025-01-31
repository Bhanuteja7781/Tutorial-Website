<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
           background-color: #f5f5f5;
        }
        .header {
            background-color: #2eaa49;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
        }
        .nav {
            text-align: center;
            padding: 10px 0;
        }
        .nav a {
            text-decoration: none;
            color: white;
            padding: 0 15px;
            font-size: 18px;
        }
        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            padding: 40px;
            max-width: 900px;
            margin: auto;
        }
        .box {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .box h3 {
            color: #2eaa49;
            margin-top: 0;
        }
        .footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
        .footer a {
            color: #2eaa49;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>

    <div class="header">
        Welcome to Your Website Task
        <div class="nav">
            <a href="file:///C:/Users/bhanu/OneDrive/Documents/HTML%20CSS/Website_Activity.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </div>
    </div>

    <div class="content">
        <div class="box">
            <h3>About CSS</h3>
            <p>Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>
        </div>
        <div class="box">
            <h3>Box Model</h3>
            <p>The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>
        </div>
        <div class="box">
            <h3>Responsive Design</h3>
            <p>Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>
        </div>
    </div>

    <div class="footer">
        Created by Bhanu Teja | Follow us on 
        <a href="https://www.instagram.com/bhanuteja_7781/">Instagram</a> |
        <a href="https://x.com/mbhanuteja11">Twitter</a> |
        <a href="https://www.linkedin.com/in/bhanu-teja-moravineni-23634a296/">LinkedIn</a>
    </div>

</body>
</html>
<!--this file about.html is included in the main code-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
       background-color: #f5f5f5;
    }
    </style>
</head>
<body>
    <div style="background-color: #2eaa49;color: white;padding: 15px;text-align: center;font-size: 24px;">About</div>
    <p style="padding: 1%;">This is a tutorial website made for activity 2 of course INT220</p>
</body>
</html>
<!--this file contact.html is included in the main code-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
           background-color: #f5f5f5;
        }
    </style>
</head>
<body>
    <div>
        <h1 style="background-color: #2eaa49;color: white;padding: 15px;text-align: center;font-size: 24px;">Contact</h1>
        <p style="padding: 1%;">Ph no: +91 9030646360</p>
        <p style="padding: 1%;">Email: bhanutejam970@gmail.com</p>
    </div>
</body>
</html>

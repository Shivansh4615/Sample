# 📌 Profile Card

## 🌟 Description
A simple profile card built with **HTML & CSS** that displays a name, title, and a button.

## 🎨 Demo Preview (HTML & CSS)
Here is the code for the **profile card**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ecf0f1;
            font-family: Arial, sans-serif;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-align: center;
            width: 250px;
        }

        .card h2 {
            color: #2c3e50;
        }

        .card p {
            color: #7f8c8d;
        }

        .btn {
            background-color: #3498db;
            color: white;
            padding: 8px 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        .btn:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
    <div class="card">
        <h2>Shivansh</h2>
        <p>Web Developer</p>
        <button class="btn">Follow</button>
    </div>
</body>
</html>

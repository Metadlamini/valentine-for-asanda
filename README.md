<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>For Asanda ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;
            text-align: center;
        }

        .card {
            background: rgba(0, 0, 0, 0.2);
            padding: 40px;
            border-radius: 20px;
            max-width: 400px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        h1 {
            margin-bottom: 20px;
        }

        button {
            background: white;
            color: #ff4f7a;
            border: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.05);
        }

        .hidden {
            display: none;
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>

<div class="card">
    <h1> Asanda ❤️</h1>
    <p> I know its a bit too late but...</p>
    <button onclick="showMessage()">Open</button>

    <div id="message" class="hidden">
        <p>Will you be my Valentine sthandwa sami? 💌</p>
        <p>Forever yours 💖</p>
    </div>
</div>

<script>
    function showMessage() {
        document.getElementById("message").style.display = "block";
    }
</script>

</body>
</html>

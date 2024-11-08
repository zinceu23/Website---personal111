<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Sederhana</title>
    <style>/* Reset basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            padding: 20px;
        }
        
        header {
            background-color: #000000;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        
        h1 {
            margin-bottom: 10px;
        }
        
        section {
            margin-top: 30px;
            text-align: center;
        }
        
        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        
        button:hover {
            background-color: #6f7e8e;
        }
        
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #777;
        }
        </style>
    <link rel="stylesheet" href="styles.css">
    <style>  </style>
</head>
<body>
    <header>
        <h1>Selamat Datang di Website Sederhana</h1>
        <p>yayaya</p>
    </header>

    <section>
        <h2>Tombol Interaktif</h2>
        <button id="clickButton">Klik saya!</button>
        <p id="responseText"></p>
    </section>

    <footer>
        <p>&copy; 2024 Web Sederhana. Semua hak cipta dilindungi.</p>
    </footer>

    <script>document.getElementById("clickButton").addEventListener("click", function() {
        document.getElementById("responseText").innerText = "Terima kasih telah mengklik tombol ini KONTOL!";
    });
    </script>
</body>
</html>


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikasi CI/CD</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #eaf2f8;
            text-align: center;
            padding: 40px;
        }

        .container {
            background: white;
            padding: 30px;
            border-radius: 12px;
            max-width: 500px;
            margin: auto;
            box-shadow: 0 4px 10px #ccc;
        }

        h1 {
            color: #2563eb;
        }

        button {
            background: #2563eb;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            cursor: pointer;
        }

        button:hover {
            background: #1d4ed8;
        }

        #hasil {
            margin-top: 20px;
            color: green;
            font-weight: bold;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>Aplikasi CI/CD</h1>

    <p>
        Implementasi Continuous Integration
        dan Continuous Deployment menggunakan GitHub.
    </p>

    <button onclick="jalankan()">
        Jalankan Aplikasi
    </button>

    <p id="hasil"></p>

</div>

<script>
    function jalankan() {
        document.getElementById("hasil").innerHTML =
        "Aplikasi berhasil dijalankan!";
    }
</script>

</body>
</html>

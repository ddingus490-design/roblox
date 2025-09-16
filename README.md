<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link Disfarçado</title>
    <style>
        a.fake-link {
            text-decoration: underline;
            color: blue;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h2>Clique no link abaixo:</h2>

    <!-- Link disfarçado, sem href real -->
    <a class="fake-link" onclick="window.open('https://www.roblox.com/share?code=be3a653baf20df4892c97345ae75c8e9&type=Server','_blank')">
        https://www.roblox.com/share?code=e234eb6fc27cf14b8cd59cf48488b7a8&type=Server
    </a>

</body>
</html>

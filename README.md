<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sidebar Layout</title>
    <style>
        body {
            display: flex;
            font-family: Arial, sans-serif;
        }
        .sidebar {
            width: 200px;
            background: #f4f4f4;
            padding: 20px;
        }
        .content {
            flex: 1;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>Sidebar</h2>
        <p>Navigation links here</p>
    </div>
    <div class="content">
        <h1>Main Content</h1>
        <p>This is a sidebar layout example.</p>
    </div>
</body>
</html>
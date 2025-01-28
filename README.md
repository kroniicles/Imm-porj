<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD Application</title>
</head>
<body>
    <h1>CRUD Application</h1>
    <form id="itemForm">
        <input type="text" id="itemInput" placeholder="Enter item" required>
        <button type="submit">Add Item</button>
    </form>
    <table id="itemTable">
        <thead>
            <tr>
                <th>Item</th>
                <th>Actions</th>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
    <script src="app.js"></script>
</body>
</html>

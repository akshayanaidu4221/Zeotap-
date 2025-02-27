<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Google Sheets Mimic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="toolbar">
    <button onclick="addRow()">Add Row</button>
    <button onclick="addColumn()">Add Column</button>
    <button onclick="clearSheet()">Clear Sheet</button>
  </div>

  <div id="spreadsheet">
    <table id="sheet">
      <!-- The table rows and columns will be dynamically created here -->
    </table>
  </div>

  <script src="script.js"></script>
</body>
</html>


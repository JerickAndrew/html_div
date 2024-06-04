HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Three Column Layout</title>
    <link rel="stylesheet" href="basic.css">
</head>
<body>
    <div class="container">
        <div class="column" id="column1">Column 1</div>
        <div class="column" id="column2">Column 2</div>
        <div class="column" id="column3">Column 3</div>
    </div>
</body>
</html>


CSS:
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html, body {
    height: 100%;
    font-family: Arial, sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    display: flex;
    width: 100%;
    height: 100%;
}

.column {
    flex: 1;
    text-align: center;
    padding: 20px;
}


#column1 {
    background-color: lightcoral;
}

#column2 {
    background-color: lightgreen;
}

#column3 {
    background-color: lightblue;
}

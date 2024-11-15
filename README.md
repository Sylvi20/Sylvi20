<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #333;
        }
        .calculator {
            display: grid;
            grid-template-columns: repeat(4, 80px);
            grid-template-rows: repeat(5, 80px);
            gap: 5px;
            background-color: #222;
            padding: 10px;
            border-radius: 10px;
        }
        .button {
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            color: white;
            background-color: #444;
            border-radius: 5px;
            cursor: pointer;
            user-select: none;
        }
        .button:active {
            background-color: #666;
        }
        .button.clear { color: #f55; }
        .button.equals { background-color: #08f; }
    </style>
</head>
<body>

    <div class="calculator">
        <div class="button clear">C</div>
        <div class="button">%</div>
        <div class="button">+/-</div>
        <div class="button">/</div>

        <div class="button">7</div>
        <div class="button">8</div>
        <div class="button">9</div>
        <div class="button">*</div>

        <div class="button">4</div>
        <div class="button">5</div>
        <div class="button">6</div>
        <div class="button">-</div>

        <div class="button">1</div>
        <div class="button">2</div>
        <div class="button">3</div>
        <div class="button">+</div>

        <div class="button">.</div>
        <div class="button">0</div>
        <div class="button">{"<"}</div>
        <div class="button equals">=</div>
    </div>

</body>
</html>

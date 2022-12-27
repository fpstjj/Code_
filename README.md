calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <div class="warapper">
        <section class="screen">
            <div class="previous" data-operand-pervious>1</div>
            <div class="current" data-operand-current>0</div>
        </section>
        <section class="calc-btn_row">
            <div class="calc_btn_row">
                <button class="calc_btn double" 
                data-all-clear>C</button>
                <button class="calc_btn" data-delete><--</button>
                <button class="calc_btn" data-operation>÷</
                    button>
            </div>

            <div class="clac_btn_row">
                <button class="calc_btn" data-number>7</button>
                <button class="calc_btn" data-number>8</button>
                <button class="calc_btn" data-number>9</button>
                <button class="calc_btn" data-operation>X</button>
            </div>

            <div class="clac_btn_row">
                <button class="calc_btn" data-number>4</button>
                <button class="calc_btn" data-number>5</button>
                <button class="calc_btn" data-number>6</button>
                <button class="calc_btn" data-operation>-</button>
            </div>

            <div class="clac_btn_row">
                <button class="calc_btn" data-number>1</button>
                <button class="calc_btn" data-number>2</button>
                <button class="calc_btn" data-number>3</button>
                <button class="calc_btn" data-operation>+</button>
            </div>

            <div class="clac_btn_row">
                <button class="calc_btn" data-number>.</button>
                <button class="calc_btn double" data-number>0</button>
                <button class="calc_btn" data-number>=</button>
            </div>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html>

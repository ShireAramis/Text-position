<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TextPosition Demo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .indented-text {
            text-indent: 30px;
        }

        .aligned-text {
            border: 1px solid #ccc;
            padding: 10px;
        }

        .left-align {
            text-align: left;
        }

        .right-align {
            text-align: right;
        }

        .center-align {
            text-align: center;
        }

        .justify-align {
            text-align: justify;
        }

        .vertical-align-demo {
            height: 200px;
            line-height: 200px;
            border: 1px solid #ccc;
        }

        .baseline {
            vertical-align: baseline;
        }

        .sub {
            vertical-align: sub;
        }

        .super {
            vertical-align: super;
        }

        .top {
            vertical-align: top;
        }

        .text-top {
            vertical-align: text-top;
        }

        .middle {
            vertical-align: middle;
        }

        .bottom {
            vertical-align: bottom;
        }

        .text-bottom {
            vertical-align: text-bottom;
        }

        .custom-height {
            vertical-align: 20%;
        }
    </style>
</head>
<body>
    <div class="indented-text">
        <h2>Text with Indentation</h2>
        <p>This paragraph has an indentation of 30 pixels using the text-indent property. It helps to create a visually appealing layout.</p>
    </div>

    <div class="aligned-text left-align">
        <h2>Left Aligned Text</h2>
        <p>This text is aligned to the left using text-align property.</p>
    </div>

    <div class="aligned-text right-align">
        <h2>Right Aligned Text</h2>
        <p>This text is aligned to the right using text-align property.</p>
    </div>

    <div class="aligned-text center-align">
        <h2>Center Aligned Text</h2>
        <p>This text is centered using text-align property.</p>
    </div>

    <div class="aligned-text justify-align">
        <h2>Justified Text</h2>
        <p>This text is justified using text-align property. It creates even spacing between words, giving a clean and professional look.</p>
    </div>

    <div class="vertical-align-demo">
        <h2>Vertical Align Demo</h2>
        <span class="baseline">Baseline</span>
        <span class="sub">Sub</span>
        <span class="super">Super</span>
        <span class="top">Top</span>
        <span class="text-top">Text Top</span>
        <span class="middle">Middle</span>
        <span class="bottom">Bottom</span>
        <span class="text-bottom">Text Bottom</span>
        <span class="custom-height">Custom Height (20%)</span>
    </div>
</body>
</html>

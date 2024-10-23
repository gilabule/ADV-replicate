<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stack Operations</title>
    <style>
        body {
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
        }
        input {
            margin-bottom: 1rem;
            padding: 0.5rem;
            border-radius: 0.25rem;
        }
        .buttons {
            margin-bottom: 1rem;
        }
        .buttons button {
            background-color: #e5e7eb;
            color: black;
            padding: 0.5rem 1rem;
            border-radius: 0.25rem;
            margin: 0 0.25rem;
        }
        .stack {
            border: 1px solid #e5e7eb;
        }
        .stack div {
            border-bottom: 1px solid #e5e7eb;
            height: 3rem;
        }
        .stack div:last-child {
            border-bottom: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <input type="text" id="inputValue" />
        <div class="buttons">
            <button onclick="pop()">Pop</button>
            <button onclick="push()">Push</button>
        </div>
        <div class="stack" id="stack">
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
            <div></div>
        </div>
    </div>

    <script>
        function pop() {
            const stack = document.getElementById('stack');
            for (let i = 0; i < stack.children.length; i++) {
                if (stack.children[i].textContent !== '') {
                    stack.children[i].textContent = '';
                    break;
                }
            }
        }

        function push() {
            const inputValue = document.getElementById('inputValue').value;
            const stack = document.getElementById('stack');
            for (let i = stack.children.length - 1; i >= 0; i--) {
                if (stack.children[i].textContent === '') {
                    stack.children[i].textContent = inputValue;
                    break;
                }
            }
        }
    </script>
</body>
</html>

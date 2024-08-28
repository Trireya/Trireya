![1000026189](https://github.com/user-attachments/assets/b86f8413-cafe-4e12-b676-9fecd0533c4f)
-<!DOCTYPE html>
<html>
<head>
    <style>
        .heart {
            display: none;
            position: fixed;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            font-size: 2em;
        }
    </style>
</head>
<body>
    <button onclick="showHearts()">Click me!</button>
    <div class="heart" id="heart">&#10084;</div>

    <script>
        function showHearts() {
            const heart = document.getElementById('heart');
            heart.style.display = 'block';
            setTimeout(() => heart.style.display = 'none', 3000); // Hide hearts after 3 seconds
        }
    </script>
</body>
</html>

<!---
Trireya/Trireya is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

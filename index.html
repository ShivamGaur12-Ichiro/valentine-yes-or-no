<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Letter for You</title>
    <style>
        :root {
            --pink-bg: #ffe4e1;
            --heart-red: #ff4d6d;
            --soft-pink: #ff85a1;
        }

        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: var(--pink-bg);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
        }

        /* Floating Hearts Background */
        .hearts-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        /* The Envelope/Letter Box */
        .container {
            text-align: center;
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border: 5px solid var(--soft-pink);
            max-width: 400px;
            position: relative;
        }

        h1 {
            color: var(--heart-red);
            font-size: 2rem;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            height: 60px;
            align-items: center;
        }

        button {
            padding: 12px 30px;
            font-size: 1.2rem;
            border-radius: 10px;
            border: none;
            cursor: pointer;
            transition: transform 0.2s;
        }

        #yesBtn {
            background-color: var(--heart-red);
            color: white;
        }

        #yesBtn:hover {
            transform: scale(1.1);
        }

        #noBtn {
            background-color: #ccc;
            color: #666;
            position: absolute;
            transition: 0.1s ease;
        }

        .success-msg {
            display: none;
            font-size: 1.5rem;
            color: var(--heart-red);
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="hearts-bg" id="hearts"></div>

    <div class="container" id="mainCard">
        <div id="content">
            <div style="font-size: 50px;">💌</div>
            <h1>Will you be my Valentine?</h1>
            <div class="buttons">
                <button id="yesBtn" onclick="celebrate()">Yes</button>
                <button id="noBtn" onmouseover="moveButton()">No</button>
            </div>
        </div>
        <div id="message" class="success-msg">
            Yay! See you on the 14th! ❤️
        </div>
    </div>

    <script>
        // 1. Move the "No" button when hovered
        function moveButton() {
            const btn = document.getElementById('noBtn');
            const card = document.getElementById('mainCard');
            
            // Calculate random positions within the visible screen
            // but keeping it somewhat near the card area
            const x = Math.random() * (window.innerWidth - btn.offsetWidth);
            const y = Math.random() * (window.innerHeight - btn.offsetHeight);
            
            btn.style.position = 'fixed';
            btn.style.left = x + 'px';
            btn.style.top = y + 'px';
        }

        // 2. What happens when "Yes" is clicked
        function celebrate() {
            document.getElementById('content').style.display = 'none';
            document.getElementById('message').style.display = 'block';
            createHearts();
        }

        // 3. Decorative floating hearts
        function createHearts() {
            for(let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.innerHTML = '❤️';
                    heart.style.position = 'fixed';
                    heart.style.left = Math.random() * 100 + 'vw';
                    heart.style.top = '100vh';
                    heart.style.fontSize = (Math.random() * 20 + 10) + 'px';
                    heart.style.transition = 'transform 3s linear, opacity 3s';
                    document.body.appendChild(heart);

                    // Animate up
                    setTimeout(() => {
                        heart.style.transform = `translateY(-110vh) rotate(${Math.random() * 360}deg)`;
                        heart.style.opacity = '0';
                    }, 100);

                    // Clean up
                    setTimeout(() => heart.remove(), 4000);
                }, i * 100);
            }
        }
    </script>
</body>
</html>

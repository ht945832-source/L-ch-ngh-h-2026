<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>8/3 - Lớp Giáo Lý Vào Đời 1</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@300;500;700&family=Pinyon+Script&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-gradient: linear-gradient(135deg, #fce4ec 0%, #f8bbd0 50%, #f48fb1 100%);
            --glass-bg: rgba(255, 255, 255, 0.25);
            --glass-border: rgba(255, 255, 255, 0.18);
            --accent-color: #ad1457;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background: var(--bg-gradient);
            font-family: 'Montserrat', sans-serif;
            color: #4a4a4a;
            overflow-x: hidden;
            min-height: 200vh;
        }

        /* Hiệu ứng hạt lấp lánh */
        #particles-js {
            position: fixed;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }

        /* Header Parallax */
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            z-index: 1;
        }

        .hero-title {
            font-family: 'Pinyon Script', cursive;
            font-size: clamp(4rem, 15vw, 8rem);
            color: white;
            text-shadow: 2px 5px 15px rgba(0,0,0,0.1);
            animation: float 4s ease-in-out infinite;
        }

        .hero-subtitle {
            font-size: 1.2rem;
            letter-spacing: 5px;
            text-transform: uppercase;
            color: var(--accent-color);
            font-weight: 700;
        }

        /* Container chính */
        .container {
            max-width: 900px;
            margin: -50px auto 100px;
            padding: 0 20px;
            position: relative;
            z-index: 2;
        }

        /* Glassmorphism Card */
        .glass-card {
            background: var(--glass-bg);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border-radius: 30px;
            border: 1px solid var(--glass-border);
            padding: 60px 40px;
            box-shadow: 0 25px 50px rgba(0,0,0,0.1);
            margin-bottom: 50px;
            transition: transform 0.3s ease;
        }

        .glass-card:hover {
            transform: translateY(-10px);
        }

        h2 {
            font-family: 'Dancing Script', cursive;
            font-size: 3rem;
            color: var(--accent-color);
            margin-bottom: 30px;
            text-align: center;
        }

        p {
            line-height: 2;
            font-size: 1.15rem;
            text-align: justify;
            margin-bottom: 20px;
        }

        /* Phân đoạn đặc biệt cho lớp Giáo lý */
        .scripture {
            font-style: italic;
            text-align: center;
            color: #880e4f;
            border-left: none;
            padding: 20px;
            position: relative;
        }

        .scripture::before, .scripture::after {
            content: "“";
            font-size: 4rem;
            position: absolute;
            opacity: 0.2;
        }
        .scripture::before { left: 0; top: -10px; }
        .scripture::after { right: 0; bottom: -40px; content: "”"; }

        footer {
            text-align: center;
            padding: 100px 0;
            background: rgba(255,255,255,0.3);
            border-radius: 100% 100% 0 0;
        }

        /* Animation */
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .scroll-indicator {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
            color: white;
            font-size: 2rem;
        }

        @keyframes bounce { 0%, 20%, 50%, 80%, 100% {transform: translateX(-50%) translateY(0);} 40% {transform: translateX(-50%) translateY(-10px);} }
    </style>
</head>
<body>

    <div id="particles-js"></div>

    <header>
        <div class="hero-subtitle">Mừng Ngày 8 Tháng 3</div>
        <h1 class="hero-title">Happy Women's Day</h1>
        <p style="font-weight: 500; color: white;">Dành riêng cho Cô và các bạn Lớp Vào Đời 1</p>
        <div class="scroll-indicator">↓</div>
    </header>

    <div class="container">
        
        <div class="glass-card">
            <h2>Gửi Cô - Người Thắp Lửa</h2>
            <p>
                Kính thưa Cô, nhân ngày Quốc tế Phụ nữ, chúng con xin được gửi tới Cô những lời tri ân sâu sắc nhất từ trái tim mình. Trong suốt hành trình học giáo lý <b>Vào Đời 1</b>, Cô không chỉ là người truyền dạy kiến thức, mà còn là một tấm gương sống động về lòng mến và sự hy sinh.
            </p>
            <p>
                Chúng con cảm ơn những giờ học đầy tâm huyết, cảm ơn những lời khuyên dạy bảo chân tình của Cô. Nguyện xin Thiên Chúa, qua lời cầu bầu của <b>Đức Trinh Nữ Maria</b> - mẫu gương tuyệt vời của người phụ nữ, ban xuống trên Cô muôn vàn Hồng ân, sức khỏe dồi dào và sự bình an trong tâm hồn. Chúc Cô mãi luôn rạng rỡ và tràn đầy niềm vui trên con đường phục vụ Thiên Chúa và các linh hồn nhỏ bé như chúng con.
            </p>
        </div>

        <div class="glass-card">
            <h2>Những Đóa Hoa Vào Đời 1</h2>
            <p>
                Các bạn nữ lớp mình ơi! Hôm nay là ngày để các bạn được chiều chuộng và tỏa sáng. Chúc các bạn không chỉ xinh đẹp ở vẻ bề ngoài mà còn sở hữu một tâm hồn thật đẹp, rạng ngời như ánh sáng Tin Mừng.
            </p>
            <p class="scripture">
                "Hãy sống như những đóa hoa, luôn hướng về phía Mặt Trời Công Chính là Chúa Kitô."
            </p>
            <p>
                Mong rằng mỗi bạn sẽ luôn giữ vững đức tin, sự dịu dàng và lòng nhân hậu. Chúc các bạn có một ngày 8/3 ngập tràn quà cáp, hoa tươi và những lời chúc ngọt ngào nhất. Hãy luôn tự tin vào giá trị bản thân vì mỗi bạn đều là một "kiệt tác" độc nhất mà Thiên Chúa đã dựng nên!
            </p>
        </div>

        <div class="glass-card" style="text-align: center;">
            <h2>Tâm Tình Cuối</h2>
            <p>
                Dù mai này lớp chúng ta có bước tiếp sang các khối lớp khác, hy vọng sợi dây liên kết giữa Cô và trò, giữa những người bạn đồng môn vẫn luôn bền chặt. Chúc cho phái đẹp lớp Vào Đời 1 một ngày lễ trọn vẹn và hạnh phúc nhất!
            </p>
            <div style="font-size: 3rem;">🌹🌷🌸</div>
        </div>

    </div>

    <footer>
        <p style="text-align: center; font-weight: 700; color: var(--accent-color);">Lớp Giáo Lý Vào Đời 1 - Giáo Xứ YÊN TRẠCH LOVE VĐ1 😘</p>
        <p style="text-align: center; font-size: 0.9rem;">2026 • Design with Love</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
        particlesJS("particles-js", {
            "particles": {
                "number": { "value": 80 },
                "color": { "value": "#ffffff" },
                "shape": { "type": "circle" },
                "opacity": { "value": 0.5 },
                "size": { "value": 3 },
                "move": { "enable": true, "speed": 2, "direction": "bottom" }
            }
        });
    </script>
</body>
</html>

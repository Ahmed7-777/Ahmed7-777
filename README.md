<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed | Social Media Links - ئەحمەد | بەستەری سۆشیاڵ میدیا</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <style>
        :root {
            --tiktok-pink: #FF0050;
            --instagram-purple: #E1306C;
            --email-blue: #007bff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(45deg, #1a1a1a, #2d2d2d);
            color: white;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem;
        }

        .container {
            max-width: 600px;
            width: 90%;
            text-align: center;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 1.5rem;
            animation: fadeIn 1s ease-in;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .bio {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            line-height: 1.6;
        }

        .social-links {
            display: grid;
            gap: 1rem;
            width: 100%;
        }

        .social-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 1.5rem;
            border-radius: 15px;
            display: flex;
            align-items: center;
            gap: 1rem;
            text-decoration: none;
            color: white;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .social-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .tiktok:hover { background: linear-gradient(45deg, var(--tiktok-pink), #000000); }
        .instagram:hover { background: linear-gradient(45deg, var(--instagram-purple), #FCAF45); }
        .email-card:hover { background: linear-gradient(45deg, var(--email-blue), #00b4ff); }

        .social-icon {
            font-size: 2rem;
        }

        .help-text {
            font-size: 0.9rem;
            margin-top: 8px;
            opacity: 0.8;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 480px) {
            body { padding: 1rem; }
            h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>
     <div class="container">
        <img src="img/20250210145451.png" alt="Ahmed - ئەحمەد" class="profile-img">
        <h1>Ahmed<br>7</h1>
        
        <p class="bio">
             Official Page of Ahmed-
 پەرەی فەرمئ ئەحمەد<br>
            Need help?! - پێویستت بە یارمەتییە؟  !
        </p>

        <div class="social-links">
            <!-- TikTok -->
            <a href="https://www.tiktok.com/@ahmed00y?_t=ZS-8tnU8OFYTmX&_r=1" class="social-card tiktok" target="_blank">
                <i class="fab fa-tiktok social-icon"></i>
                <div>
                    <h3>TikTok</h3>
                    <p>@ahmed00y</p>
                </div>
            </a>

            <!-- Instagram -->
            <a href="https://www.instagram.com/__a3medd__?igsh=source=qr" class="social-card instagram" target="_blank">
                <i class="fab fa-instagram social-icon"></i>
                <div>
                    <h3>Instagram</h3>
                    <p>@__a3medd__</p>
                </div>
            </a>

            <!-- Help Hotline Email -->
            <a href="mailto:ahmed0777v@outlook.com" class="social-card email-card">
                <i class="fas fa-life-ring social-icon"></i>
                <div>
                    <h3>HELP HOTLINE - یارمەتی  </h3>
                    <p>ahmed0777v@outlook.com</p>
                    <div class="help-text">
                         24/1!
                    </div>
                </div>
            </a>
        </div>
    </div>
</body>
</html>

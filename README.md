<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
    <meta name="description" content="Biodata Gita Yunita - Siswi SMAN 15 Jakarta">
    <title>🌟 Biodata Gita Yunita</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #fdf2f8 0%, #fce7f3 25%, #e0f2fe 50%, #d1fae5 75%, #fef3c7 100%);
            background-size: 400% 400%;
            animation: gradientShift 20s ease infinite;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Poppins', 'Segoe UI', Roboto, system-ui, sans-serif;
            padding: 20px;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(30px);
            border-radius: 40px;
            padding: 40px 35px;
            max-width: 500px;
            width: 100%;
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.15), 0 10px 25px rgba(138, 43, 226, 0.2), inset 0 1px 0 rgba(255,255,255,0.8);
            border: 1px solid rgba(255, 255, 255, 0.6);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 40px 70px rgba(0, 0, 0, 0.2), 0 15px 35px rgba(236, 72, 153, 0.25);
        }

        .header {
            text-align: center;
            margin-bottom: 35px;
            position: relative;
        }

        .avatar {
            width: 110px;
            height: 110px;
            background: linear-gradient(135deg, #ec4899, #8b5cf6, #3b82f6);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 3.5rem;
            box-shadow: 0 15px 30px rgba(236, 72, 153, 0.4);
            border: 5px solid white;
            position: relative;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .avatar span {
            animation: wave 2s ease-in-out infinite;
        }

        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(10deg); }
            75% { transform: rotate(-10deg); }
        }

        h1 {
            font-size: 2.2rem;
            font-weight: 800;
            background: linear-gradient(135deg, #ec4899, #8b5cf6, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 5px;
            letter-spacing: 1px;
        }

        .subtitle {
            color: #6b7280;
            font-size: 0.95rem;
            font-weight: 500;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .divider {
            width: 60px;
            height: 4px;
            background: linear-gradient(90deg, #ec4899, #8b5cf6);
            border-radius: 10px;
            margin: 15px auto 0;
        }

        .info-section {
            background: linear-gradient(135deg, rgba(255,255,255,0.7), rgba(255,255,255,0.4));
            border-radius: 25px;
            padding: 25px;
            margin-bottom: 25px;
            border: 1px solid rgba(255,255,255,0.5);
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        }

        .info-item {
            display: flex;
            align-items: center;
            padding: 14px 0;
            border-bottom: 1px solid rgba(0,0,0,0.06);
            transition: all 0.3s ease;
            gap: 15px;
        }

        .info-item:last-child {
            border-bottom: none;
        }

        .info-item:hover {
            transform: translateX(5px);
        }

        .icon {
            width: 45px;
            height: 45px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            flex-shrink: 0;
            box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        }

        .icon.pink { background: linear-gradient(135deg, #fce7f3, #fbcfe8); }
        .icon.purple { background: linear-gradient(135deg, #ede9fe, #ddd6fe); }
        .icon.blue { background: linear-gradient(135deg, #dbeafe, #bfdbfe); }
        .icon.green { background: linear-gradient(135deg, #d1fae5, #a7f3d0); }
        .icon.orange { background: linear-gradient(135deg, #fef3c7, #fde68a); }
        .icon.red { background: linear-gradient(135deg, #fee2e2, #fecaca); }

        .info-content {
            flex: 1;
        }

        .info-label {
            font-size: 0.8rem;
            font-weight: 600;
            color: #9ca3af;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 3px;
        }

        .info-value {
            font-size: 1.05rem;
            font-weight: 600;
            color: #1f2937;
        }

        .motivation-box {
            background: linear-gradient(135deg, #fef3c7, #fde68a);
            border-radius: 20px;
            padding: 22px;
            margin: 20px 0 25px;
            border-left: 5px solid #f59e0b;
            position: relative;
            box-shadow: 0 8px 25px rgba(245, 158, 11, 0.2);
        }

        .motivation-box::before {
            content: '"';
            position: absolute;
            top: -15px;
            left: 15px;
            font-size: 4rem;
            color: rgba(245, 158, 11, 0.3);
            font-family: Georgia, serif;
            line-height: 1;
        }

        .motivation-label {
            font-size: 0.85rem;
            font-weight: 700;
            color: #92400e;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .motivation-text {
            font-size: 1rem;
            font-weight: 500;
            color: #78350f;
            font-style: italic;
            line-height: 1.6;
        }

        .project-button {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 16px 25px;
            background: linear-gradient(135deg, #ec4899, #8b5cf6, #3b82f6);
            background-size: 200% 200%;
            animation: buttonGradient 3s ease infinite;
            color: white;
            text-decoration: none;
            border-radius: 20px;
            font-weight: 700;
            font-size: 1.1rem;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(139, 92, 246, 0.4);
            border: none;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }

        @keyframes buttonGradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .project-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(139, 92, 246, 0.6);
        }

        .project-button:active {
            transform: translateY(0px);
            box-shadow: 0 5px 15px rgba(139, 92, 246, 0.4);
        }

        .project-button .btn-icon {
            font-size: 1.5rem;
            animation: bounce 1.5s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateX(0); }
            50% { transform: translateX(5px); }
        }

        .badge {
            display: inline-block;
            background: rgba(255,255,255,0.3);
            padding: 3px 10px;
            border-radius: 15px;
            font-size: 0.75rem;
            font-weight: 600;
            color: white;
            margin-left: 8px;
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        .footer-text {
            text-align: center;
            margin-top: 20px;
            color: #9ca3af;
            font-size: 0.85rem;
            font-weight: 500;
        }

        /* Responsive */
        @media (max-width: 480px) {
            .card {
                padding: 30px 20px;
                border-radius: 30px;
            }
            h1 {
                font-size: 1.8rem;
            }
            .avatar {
                width: 90px;
                height: 90px;
                font-size: 2.8rem;
            }
            .info-item {
                padding: 12px 0;
            }
            .icon {
                width: 40px;
                height: 40px;
                font-size: 1.3rem;
                border-radius: 12px;
            }
            .info-value {
                font-size: 0.95rem;
            }
            .project-button {
                padding: 14px 20px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <!-- Header -->
        <div class="header">
            <div class="avatar">
                <span>👩🏻‍💼</span>
            </div>
            <h1>Gita Yunita</h1>
            <p class="subtitle">✨ Siswi Berprestasi ✨</p>
            <div class="divider"></div>
        </div>

        <!-- Info Section -->
        <div class="info-section">
            <!-- Umur -->
            <div class="info-item">
                <div class="icon pink">
                    🎂
                </div>
                <div class="info-content">
                    <p class="info-label">Umur</p>
                    <p class="info-value">16 Tahun</p>
                </div>
            </div>

            <!-- Asal Sekolah -->
            <div class="info-item">
                <div class="icon purple">
                    🏫
                </div>
                <div class="info-content">
                    <p class="info-label">Asal Sekolah</p>
                    <p class="info-value">SMAN 15 JAKARTA</p>
                </div>
            </div>

            <!-- Hobi -->
            <div class="info-item">
                <div class="icon blue">
                    🎧
                </div>
                <div class="info-content">
                    <p class="info-label">Hobi</p>
                    <p class="info-value">Mendengarkan Musik</p>
                </div>
            </div>

            <!-- Cita-cita -->
            <div class="info-item">
                <div class="icon green">
                    🚀
                </div>
                <div class="info-content">
                    <p class="info-label">Cita-cita</p>
                    <p class="info-value">Menjadi Pebisnis Handal</p>
                </div>
            </div>

            <!-- Makanan Favorit -->
            <div class="info-item">
                <div class="icon orange">
                    🍗
                </div>
                <div class="info-content">
                    <p class="info-label">Makanan Favorit</p>
                    <p class="info-value">Ayam Bakar</p>
                </div>
            </div>
        </div>

        <!-- Motivasi -->
        <div class="motivation-box">
            <div class="motivation-label">
                💡 Motivasi Hidup
            </div>
            <p class="motivation-text">
                "Membangun fondasi yang kokoh hari ini untuk mencetak generasi pemimpin di masa depan."
            </p>
        </div>

        <!-- Tombol Link Proyek -->
        <a href="https://gitayunita967-rgb.github.io/SliceFruit/" 
           target="_blank" 
           rel="noopener noreferrer" 
           class="project-button">
            <span class="btn-icon">🔪</span>
            Lihat Proyek SliceFruit
            <span class="btn-icon">🍉</span>
            <span class="badge">NEW</span>
        </a>

        <!-- Footer -->
        <p class="footer-text">
            © 2025 Gita Yunita • Dibuat dengan ❤️
        </p>
    </div>
</body>
</html>

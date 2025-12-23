<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cloud AI DevOps Banner</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: #f5f5f5;
            padding: 20px;
        }

        .banner-container {
            width: 1200px;
            height: 400px;
            background: linear-gradient(135deg, #0f172a 0%, #1e3a5f 25%, #0f172a 50%, #1a1f3a 75%, #0f172a 100%);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            position: relative;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 60px;
        }

        /* Animated background elements */
        .bg-element {
            position: absolute;
            opacity: 0.1;
            pointer-events: none;
        }

        .element-1 {
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, #3b82f6, transparent);
            border-radius: 50%;
            top: -100px;
            right: -100px;
            animation: float 8s ease-in-out infinite;
        }

        .element-2 {
            width: 250px;
            height: 250px;
            background: radial-gradient(circle, #10b981, transparent);
            border-radius: 50%;
            bottom: -80px;
            left: -50px;
            animation: float 10s ease-in-out infinite reverse;
        }

        .element-3 {
            width: 200px;
            height: 200px;
            background: radial-gradient(circle, #f59e0b, transparent);
            border-radius: 50%;
            top: 50%;
            right: 10%;
            animation: float 12s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) translateX(0px); }
            50% { transform: translateY(-30px) translateX(20px); }
        }

        /* Content wrapper */
        .content {
            position: relative;
            z-index: 2;
            max-width: 700px;
        }

        .main-title {
            font-size: 48px;
            font-weight: 800;
            color: #ffffff;
            margin-bottom: 15px;
            letter-spacing: -0.5px;
            line-height: 1.2;
        }

        .title-highlight {
            background: linear-gradient(135deg, #3b82f6, #10b981);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .subtitle {
            font-size: 18px;
            color: #cbd5e1;
            margin-bottom: 30px;
            line-height: 1.6;
            font-weight: 300;
        }

        /* Icons container */
        .icons-group {
            display: flex;
            gap: 20px;
            margin-bottom: 30px;
        }

        .icon-badge {
            width: 50px;
            height: 50px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            backdrop-filter: blur(10px);
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .icon-badge:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.15);
            border-color: rgba(255, 255, 255, 0.3);
        }

        .icon-badge.cloud { border-left: 3px solid #3b82f6; }
        .icon-badge.ai { border-left: 3px solid #10b981; }
        .icon-badge.devops { border-left: 3px solid #f59e0b; }

        /* CTA Button */
        .cta-button {
            display: inline-block;
            padding: 14px 40px;
            background: linear-gradient(135deg, #3b82f6, #1e40af);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 16px;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 10px 25px rgba(59, 130, 246, 0.3);
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 35px rgba(59, 130, 246, 0.4);
        }

        /* Right side accent elements */
        .visual-accent {
            position: relative;
            z-index: 2;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .accent-circle {
            width: 280px;
            height: 280px;
            border-radius: 50%;
            background: linear-gradient(135deg, rgba(59, 130, 246, 0.2), rgba(16, 185, 129, 0.2));
            border: 2px solid rgba(59, 130, 246, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 120px;
            animation: rotate 20s linear infinite;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .accent-circle::before {
            content: '⚙️';
            position: absolute;
        }

        /* Stats or features */
        .features {
            display: flex;
            gap: 30px;
            margin-top: 25px;
        }

        .feature-item {
            flex: 1;
            padding: 12px 0;
            border-bottom: 2px solid rgba(255, 255, 255, 0.1);
        }

        .feature-value {
            font-size: 22px;
            font-weight: 700;
            color: #3b82f6;
        }

        .feature-label {
            font-size: 12px;
            color: #94a3b8;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 5px;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .banner-container {
                flex-direction: column;
                height: auto;
                padding: 40px;
                text-align: center;
            }

            .main-title {
                font-size: 32px;
            }

            .subtitle {
                font-size: 14px;
            }

            .visual-accent {
                margin-top: 30px;
            }

            .accent-circle {
                width: 180px;
                height: 180px;
                font-size: 80px;
            }

            .features {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="banner-container">
        <!-- Background animated elements -->
        <div class="bg-element element-1"></div>
        <div class="bg-element element-2"></div>
        <div class="bg-element element-3"></div>

        <!-- Main Content -->
        <div class="content">
            <div class="main-title">
                Enterprise <span class="title-highlight">Cloud Intelligence</span>
            </div>

            <p class="subtitle">
                Seamlessly integrate cloud infrastructure, artificial intelligence, and DevOps practices for next-generation digital transformation
            </p>

            <div class="icons-group">
                <div class="icon-badge cloud" title="Cloud Computing">☁️</div>
                <div class="icon-badge ai" title="Artificial Intelligence">🤖</div>
                <div class="icon-badge devops" title="DevOps">🔧</div>
            </div>

            <div class="features">
                <div class="feature-item">
                    <div class="feature-value">99.9%</div>
                    <div class="feature-label">Uptime</div>
                </div>
                <div class="feature-item">
                    <div class="feature-value">24/7</div>
                    <div class="feature-label">Support</div>
                </div>
                <div class="feature-item">
                    <div class="feature-value">ML-Ops</div>
                    <div class="feature-label">Automated</div>
                </div>
            </div>

            <button class="cta-button">Explore Solutions →</button>
        </div>

        <!-- Visual Accent -->
        <div class="visual-accent">
            <div class="accent-circle"></div>
        </div>
    </div>
</body>
</html>

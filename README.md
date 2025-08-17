<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rebin Ali / Social Media</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            direction: rtl;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .profile-section {
            margin-bottom: 30px;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 15px;
            font-size: 40px;
            color: white;
            position: relative;
            overflow: hidden;
            animation: pulse 2s infinite;
        }

        .profile-img {
            background-image: url('https://i.ibb.co/VYhBRBCC/reben-new-lain-ca20449b-eb93-4cfb-9454-078d4b1a11e8.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        h1 {
            color: #333;
            font-size: 24px;
            margin-bottom: 10px;
        }

        .subtitle {
            color: #666;
            font-size: 14px;
            margin-bottom: 20px;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .social-link {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            padding: 15px 20px;
            background: white;
            border-radius: 15px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            border: 2px solid transparent;
        }

        .social-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            border-color: #667eea;
        }

        .social-link:active {
            transform: translateY(-1px);
        }

        .social-icon {
            width: 40px;
            height: 40px;
            margin-left: 15px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 18px;
            position: relative;
        }

        /* Phone - moved to top */
        .phone { 
            background: #34C759;
        }
        .phone::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .whatsapp { 
            background: #25D366;
        }
        .whatsapp::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.465 3.516z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .viber { 
            background: #665CAC;
        }
        .viber::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M12 2C6.477 2 2 6.477 2 12c0 1.89.525 3.66 1.438 5.168L2 22l4.832-1.438C8.34 21.475 10.11 22 12 22c5.523 0 10-4.477 10-10S17.523 2 12 2zm3.8 13.4c-.2.6-.9 1.1-1.5 1.2-.4 0-.9.1-2.9-.6-2.4-1-3.9-3.4-4-3.5-.1-.1-.8-1.1-.8-2s.5-1.4.7-1.6c.2-.2.4-.3.5-.3s.3 0 .4.1c.1.1.5 1.2.5 1.3.1.1.1.2 0 .4-.1.2-.1.3-.3.5-.1.1-.3.3-.1.6.2.3.9 1.5 2 2.4.1.1 1.8 1.3 2 1.4.2.1.3.1.4 0 .1-.1.6-.7.8-.9.2-.2.4-.2.6-.1.2.1 1.3.6 1.5.7.2.1.3.2.4.3.1.1.1.6-.1 1.2z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .telegram { 
            background: #0088cc;
        }
        .telegram::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M11.944 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0a12 12 0 0 0-.056 0zm4.962 7.224c.1-.002.321.023.465.14a.506.506 0 0 1 .171.325c.016.093.036.306.02.472-.18 1.898-.962 6.502-1.36 8.627-.168.9-.499 1.201-.82 1.23-.696.065-1.225-.46-1.9-.902-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.0613.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .instagram { 
            background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%);
        }
        .instagram::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .facebook { 
            background: #1877F2;
        }
        .facebook::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .snapchat { 
            background: #FFFC00; 
            color: #000;
        }
        .snapchat::before {
            content: '👻';
            font-size: 20px;
            color: #000;
        }

        .tiktok { 
            background: #000000;
        }
        .tiktok::before {
            content: '';
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white"><path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.722.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/></svg>') center/contain no-repeat;
            width: 24px;
            height: 24px;
        }

        .link-text {
            flex: 1;
            text-align: right;
            font-weight: 500;
        }

        .link-label {
            font-size: 16px;
            margin-bottom: 2px;
        }

        .link-value {
            font-size: 12px;
            color: #888;
        }

        @media (max-width: 480px) {
            .container {
                padding: 20px;
                margin: 10px;
            }
        }

        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(255, 107, 107, 0.7);
            }
            70% {
                box-shadow: 0 0 0 10px rgba(255, 107, 107, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(255, 107, 107, 0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-section">
            <div class="profile-img"></div>
            <h1 id="displayNameKurdish" style="font-size: 22px; margin-bottom: 5px;">ڕێبین علی سعید</h1>
            <h1 id="displayName">Rebin Ali Saeed</h1>
            <p class="subtitle">پەیوەندی بکە لە ڕێگەی:</p>
        </div>

        <div id="displayMode">
            <div class="links-container">
                <!-- Phone - بەشی پەیوەندی لە سەرەتا -->
                <a href="tel:+9647507812951" class="social-link" id="phoneLink">
                    <div class="social-icon phone"></div>
                    <div class="link-text">
                        <div class="link-label">پەیوەندی</div>
                        <div class="link-value">+9647507812951</div>
                    </div>
                </a>

                <!-- WhatsApp -->
                <a href="https://wa.me/9647507812951" class="social-link" id="whatsappLink">
                    <div class="social-icon whatsapp"></div>
                    <div class="link-text">
                        <div class="link-label">WhatsApp</div>
                        <div class="link-value">+9647507812951</div>
                    </div>
                </a>

                <!-- Viber -->
                <a href="viber://chat?number=%2B9647507812951" class="social-link" id="viberLink">
                    <div class="social-icon viber"></div>
                    <div class="link-text">
                        <div class="link-label">Viber</div>
                        <div class="link-value">+9647507812951</div>
                    </div>
                </a>

                <!-- Telegram -->
                <a href="https://t.me/rebinderbendi" class="social-link" id="telegramLink">
                    <div class="social-icon telegram"></div>
                    <div class="link-text">
                        <div class="link-label">Telegram</div>
                        <div class="link-value">@rebinderbendi</div>
                    </div>
                </a>

                <!-- Instagram -->
                <a href="https://instagram.com/rebin.derbendi" class="social-link" id="instagramLink">
                    <div class="social-icon instagram"></div>
                    <div class="link-text">
                        <div class="link-label">Instagram</div>
                        <div class="link-value">@rebin.derbendi</div>
                    </div>
                </a>

                <!-- Facebook -->
                <a href="https://facebook.com/rebin.derbendi" class="social-link" id="facebookLink">
                    <div class="social-icon facebook"></div>
                    <div class="link-text">
                        <div class="link-label">Facebook</div>
                        <div class="link-value">rebin.derbendi</div>
                    </div>
                </a>

                <!-- Snapchat -->
            <a href="https://www.snapchat.com/add/rebin.derbendi" class="social-link">
                <div class="social-icon snapchat"></div>
                <div class="link-text">
                    <div class="link-label">Snapchat</div>
                    <div class="link-value">rebin.derbendi</div>
                </div>
            </a>

                <!-- TikTok -->
                <a href="https://www.tiktok.com/@rebinderbendi" class="social-link" id="tiktokLink">
                    <div class="social-icon tiktok"></div>
                    <div class="link-text">
                        <div class="link-label">TikTok</div>
                        <div class="link-value">@rebinderbendi</div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <script>
        // Load saved data on page load
        window.onload = function() {
            loadPresetData();
        };

        function loadPresetData() {
            // Set preset data for Rebin Ali Saeed
            const data = {
                name: 'Rebin Ali Saeed',
                whatsapp: '+9647507812951',
                viber: '+9647507812951', 
                telegram: 'rebinderbendi',
                instagram: 'rebin.derbendi',
                facebook: 'rebin.derbendi',
                phone: '+9647507812951'
            };

            // Update name
            document.getElementById('displayName').textContent = data.name;

            // Update Phone - بەشی پەیوەندی لە سەرەتا
            updateLink('phone', data.phone, 'tel:+9647507812951');
            
            // Update WhatsApp - opens chat directly
            updateLink('whatsapp', data.whatsapp, 'https://wa.me/9647507812951');
            
            // Update Viber - opens chat directly  
            updateLink('viber', data.viber, 'viber://chat?number=%2B9647507812951');
            
            // Update Telegram - opens profile
            updateLink('telegram', '@rebinderbendi', 'https://t.me/rebinderbendi');
            
            // Update Instagram - opens profile
            updateLink('instagram', '@rebin.derbendi', 'https://instagram.com/rebin.derbendi');
            
            // Update Facebook - opens profile
            updateLink('facebook', 'rebin.derbendi', 'https://facebook.com/rebin.derbendi');
        }

        function updateLink(platform, value, url) {
            const link = document.getElementById(`${platform}Link`);
            const display = document.getElementById(`${platform}Display`);
            
            if (value && value.trim()) {
                link.style.display = 'flex';
                link.href = url;
                if (display) display.textContent = value;
            } else {
                if (link) link.style.display = 'none';
            }
        }

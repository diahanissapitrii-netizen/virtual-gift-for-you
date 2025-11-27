# virtual-gift-for-you
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtual Gift for My Love</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px 0;
        }

        .container {
            width: 90%;
            max-width: 450px;
            background-color: #ffffff;
            border-radius: 20px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            padding: 30px;
            text-align: center;
        }

        .header-pink {
            color: #d84381;
            font-size: 2em;
            margin-bottom: 10px;
            font-weight: bold;
        }

        .subheader {
            color: #b58392;
            font-size: 1.1em;
            margin-bottom: 30px;
        }

        .video-box {
            background-color: #fce4ec;
            height: 200px; 
            border-radius: 10px;
            margin-bottom: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #880e4f;
            font-weight: bold;
            overflow: hidden; 
        }

        .nav-buttons {
            display: flex;
            justify-content: space-around;
            margin-bottom: 30px;
        }

        .nav-button {
            background-color: #f8bbd0;
            color: #880e4f;
            border: none;
            padding: 10px 15px;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .nav-button:hover {
            background-color: #f48fb1;
        }

        .content-section {
            padding: 20px;
            background-color: #fff;
            border-radius: 15px;
            border: 1px solid #f8bbd0;
            margin-top: 20px;
            text-align: left;
        }

        .content-section h3 {
            color: #d84381;
            margin-top: 0;
            border-bottom: 2px solid #f8bbd0;
            padding-bottom: 5px;
        }

        .postcard-image {
            width: 100%;
            height: 150px;
            background-color: #fce4ec;
            border: 1px dashed #d84381;
            border-radius: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 15px;
        }

        .postcard-image span {
            color: #880e4f;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container" id="main-content">
    <div class="header-pink">HAPPY BIRTHDAY!</div>
    <div class="subheader">Hi, Abang Sayang!</div>

    <div class="video-box">
        <div class="video-box">
<iframe src="https://drive.google.com/file/d/1-f0XWCxTDvLRjiWT_mUzEUAbx61v_I3v/preview" width="100%" height="300" frameborder="0" allowfullscreen></iframe>
</div>

    </div>

    <div class="nav-buttons">
        <button class="nav-button" onclick="showContent('profile')">Profile</button>
        <button class="nav-button" onclick="showContent('twenty')">Forty</button>
        <button class="nav-button" onclick="showContent('readMe')">Read Me</button>
    </div>

    <div class="content-section" id="profile-content" style="display: none;">
        <h3>a little about u (and us)</h3>
        <p>She is the youngest daughter, a girl full of ambition and determination. She deserves all the best things in life. But most importantly, she is the one I love.</p>
        <div class="video-box" style="height: 100px;">
            [Placeholder Foto Anda Berdua]
        </div>
    </div>

    <div class="content-section" id="twenty-content" style="display: none;">
        <h3>Video of the two of us</h3>
        <div class="video-box" style="height: 300px; padding: 0;">
            <iframe src="https://drive.google.com/file/d/1-zrx-RCEMTlbFrBftFoqGk1hSeovTQyZ/preview"
                style="width:100%; height:100%; border-radius:10px; border:none;"
                allowfullscreen>
            </iframe>
        </div>
        <button class="nav-button" style="width: 100%; margin-top: 10px;">COLLECT</button>
    </div>

    <div class="content-section" id="readMe-content" style="display: none;">
        <h3>Happy Birthday!</h3>
        <div class="postcard-image" style="background-color: #f8bbd0; height: 30px; margin-bottom: 20px;">
            <span style="color: #ffffff;">COLLECTED POSTCARD</span>
        </div>
        
        <p style="white-space: pre-wrap; text-align: left; line-height: 1.6;">
            Selamat ulang tahun sayangku❤️
            
            Hari ini bukan hanya pengingat bahwa kamu telah ada, tapi juga pengingat bahwa You Matter.

            Di tengah segala hiruk pikuk, kamu adalah alasan mengapa tahun-tahun ini terasa berarti. Kamu adalah orang yang menginspirasi dan membahagiakan.

            Sejujurnya, aku hanya ingin mengatakan bahwa I'm glad I met you. Kamu membuat hidupku lebih berwarna dan penuh petualangan.

            
            Tahun ini, tahun depan, dan tahun-tahun berikutnya, semoga kita selalu bersama, menertawakan hal-hal konyol dan mengumpulkan kenangan indah.

            I love you, and can't wait to make more memories with you.

            With lots of love,
            Anis.
        </p>
    </div>
    
</div>

<script>
    function showContent(contentId) {
        // Sembunyikan semua konten
        document.getElementById('profile-content').style.display = 'none';
        document.getElementById('twenty-content').style.display = 'none';
        document.getElementById('readMe-content').style.display = 'none';

        // Tampilkan konten yang dipilih
        document.getElementById(contentId + '-content').style.display = 'block';
    }
    // Secara default, tidak ada konten yang ditampilkan saat pertama kali dibuka.
</script>

</body>
</html>

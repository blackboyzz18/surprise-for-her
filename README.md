<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise for my Girl</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            margin: 0;
            flex-direction: column;
            text-align: center;
        }

        .gift-box {
            font-size: 100px;
            cursor: pointer;
        }

        .message {
            margin-top: 20px;
            font-size: 24px;
            color: #555;
        }

        .shayari {
            display: none;
            margin-top: 30px;
            font-size: 22px;
            color: #333;
            max-width: 80%;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <div class="gift-box" onclick="openSurprise()">🎁</div>
    <div class="message">Click on it!</div>
    <div class="shayari" id="shayari">
        कभी सोचा नहीं था, कि ज़िंदगी इतनी खूबसूरत हो जाएगी,<br>
        तेरी मुस्कुराहट से हर ग़म दूर हो जाएगी।<br>
        तुम्हारी आँखों में जो खुशियाँ चमकती हैं,<br>
        मुझे हर पल में नई ज़िंदगी मिल जाएगी। 💖✨<br><br>

        तुम्हारा साथ मिलता है तो हर रास्ता आसान लगता है,<br>
        तुम्हारी बातों में वो जादू है, जो हर लम्हा मीठा बनाता है। 🥰<br>
        मेरे हर दिन की शुरुआत तुम्हारे नाम से होती है,<br>
        लक्षिता, तुम हो मेरे दिल की सबसे प्यारी सुबह की पहली किरण,<br>
        और रात को सोने से पहले का सबसे खूबसूरत ख़्वाब। 🌅🌙<br><br>

        मुझे हर उस पल का इंतज़ार रहता है,<br>
        जब तुम्हारे साथ होंगे हम,<br>
        और ये दुनिया सिर्फ हमारी होगी। 🌍💑<br>
        पारस तुमसे बेतहाशा मोहब्बत करता है,<br>
        तुम ही उसकी खुशी, उसका ख़्वाब, और उसका सपना हो,<br>
        हर पल में तुम्हारा साथ ही उसके दिल को सुहाना लगता है। ❤🌹<br><br>

        लक्षिता, तुम्हारी मुस्कुराहट में वो ताकत है,<br>
        जो मेरे सारे दर्द भुला देती है। 😊💕<br>
        तुम्हारे साथ हर रात खूबसूरत लगती है,<br>
        और हर सुबह तुम्हारी यादों में बहती है। ☀🌸<br>
        पारस तुम्हें हर पल में खुश देखना चाहता है,<br>
        क्योंकि तुम उसकी ज़िंदगी का सबसे खूबसूरत हिस्सा हो। 🥰🌟
    </div>

    <script>
        function openSurprise() {
            document.getElementById('shayari').style.display = 'block';
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=\device-width, initial-scale=1.0">
    <title>Snowboarding - Designer Boarders</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            color: white;
        }
        .hero {
            display: flex;
            position: relative;
            width: 100%;
            height: 100vh;
            overflow: hidden;
        }
        .hero img {
            width: 33.33%;
            height: 100vh;
            object-fit: cover;
        }
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .overlay h1 {
            font-size: 4.5rem;
            font-weight: 900;
            margin: 0;
            text-align: center;
        }
        .overlay h2 {
            font-size: 2rem;
            font-weight: 400;
            margin-top: 10px;
            text-align: center;
        }
        .caption {
            position: absolute;
            color: white;
            font-size: 1rem;
        }
        .left-caption {
            top: 10%;
            left: 5%;
        }
        .right-caption {
            top: 10%;
            right: 5%;
        }
        .bottom-caption {
            bottom: 5%;
            right: 5%;
        }
        .bottom-left-caption {
            bottom: 5%;
            left: 5%;
        }
    </style>
</head>
<body>
    <div class="hero">
        <img src="https://img.redbull.com/images/c_fill,g_auto,w_450,h_600/q_auto:low,f_auto/redbullcom/2020/11/4/tjwdcqenkqojgmbitumh/burton-gore-tex-3l-freebird-stretch-bib-pant" alt="Snowboarder Left">
        <img src="https://www.burton.com/static/community/advice/jacket-length-pow-slash.jpg" alt="Snowboarder Center">
        <img src="https://funpackedlife.com/wp-content/uploads/4-26.webp" alt="Snowboarder Right">
        <div class="overlay">
            <h1>SNOWBOARDING</h1>
            <h2>FOR THE DESIGNER BOARDERS</h2>
        </div>
        <div class="caption left-caption">Ron Apuya</div>
        <div class="caption right-caption">Brian Head Range</div>
        <div class="caption bottom-caption">Extreme Custom Boards</div>
        <div class="caption bottom-left-caption">For The Designer Boarders</div>
    </div>
</body>
</html>

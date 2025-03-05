<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2010년 3월 6일, 알래스카</title>
    <style>
        body {
            background-color: black;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
            padding: 50px;
        }
        .hidden {
            opacity: 0;
            transition: opacity 2s ease-in;
        }
        .reveal {
            opacity: 1 !important;
        }
        a {
            color: #00bfff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <h1>2010년 3월 6일, 알래스카에서 들려온 단 한 마디...</h1>
    <p>그날, 이곳에서 무슨 일이 있었을까?</p>
    <p><strong>📍 좌표: <a href="https://www.google.com/maps/place/Korean+Community+Center+of+Anchorage/@61.1791,-149.9063,15z" target="_blank">61.1791° N, 149.9063° W</a></strong></p>
    <p>이곳을 방문하면, 당신도 그 순간을 느낄 수 있습니다.</p>
    
    <h2 id="hiddenText" class="hidden">무~야~호!</h2>
    
    <script>
        setTimeout(() => {
            document.getElementById("hiddenText").classList.add("reveal");
        }, 5000); // 5초 후 "무야호" 나타남
    </script>
</body>
</html>

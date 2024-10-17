<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered Page</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .container {
            width: 100%;
            max-width: 800px;
            padding: 20px;
        }
        .countdown {
            width: 100%;
            padding-bottom: 25%;
            position: relative;
        }
        .countdown iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .form {
            width: 100%;
            height: 2697px;
            border: none;
        }
        @media (max-width: 800px) {
            .container {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="countdown">
            <script>(function(d, s, id) { var js, pjs = d.getElementsByTagName(s)[0]; if (d.getElementById(id)) return; js = d.createElement(s); js.id = id; js.src = "//www.tickcounter.com/static/js/loader.js"; pjs.parentNode.insertBefore(js, pjs); }(document, "script", "tickcounter-sdk"));</script>
            <a data-type="countdown" data-id="5969422" class="tickcounter" style="display:block; left:0; width:100%; height:0; position:relative; padding-bottom:25%; margin:0 auto;" title="Countdown to EOYP" href="//www.tickcounter.com/">Countdown to EOYP</a>
        </div>
        <iframe class="form" src="https://docs.google.com/forms/d/e/1FAIpQLSfJxhOkybz_ZA0ygd0wLzISUxHU4dK-Elwvk0ZpTj3iyyHq9w/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    </div>
</body>
</html>

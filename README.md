<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My HTML Page</title>
    <style>
        .halfl {
            width: 50%;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-self: center;
            float:left;
            background-color: black;
        }
        .halfr {
            width: 50%;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-self: center;
            float:right;
            background-color: black;
            color: white;
        }
        .x{
            width: 100%;
            height: 50%;
            display: flex;
            justify-content: flex-start;
            align-self: flex-start;

        }
        .katılın
        {
            width: 100%;
            height: 50vh;
            display: flex;
            justify-content: flex-end;   
            align-items: flex-end;       
        }
    </style>
</head>
<body style="background-color: black;">
    <div >
    <div class="halfl"   >
        <g style="margin-left:20% ; margin-top:10% ;">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="70%" height="70vh"  fill="white"  >
            <path style="display: flex; justify-content:center; align-self: center; " d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"></path>
        </svg>
    </g>
    </div>
    <div class="halfr">
        <div class="x">
            <h1 style="color: white; font-size: 75px; margin: 10%; ">Şu anda olup bitenler</h1>
        </div>
        <div class="katılın">
            <h2 style="color: white; font-size: 60px; margin: 10%; ">hemen katılın</h2>
        </div>
    </div>
</div>
</body>
</html>

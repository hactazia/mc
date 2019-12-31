<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Heart</title>
        <style>
            body {
                margin: 0;
                padding: 0;
                display: flex;
                justify-content: center;
                align-items: center;
                min-height: 100vh;
                background-image: radial-gradient(#ff0000,#5a0000);
            }
            .heart{
                position: relative;
                width: 200px;
                height: 200px;
                background: #e80202;
                transform: rotate(45deg);
                box-shadow: 30px 30px 200px rgb(0,0,0,.5);
                animation: animate 1s linear infinite;
            }
            @keyframes animate {
                0% {
                    transform: rotate(45deg) scale(1);
                }
                20% {
                    transform: rotate(45deg) scale(.8);
                }
                40% {
                    transform: rotate(45deg) scale(1.2);
                }
                60% {
                    transform: rotate(45deg) scale(1);
                }
                80% {
                    transform: rotate(45deg) scale(1.3);
                }
                100% {
                    transform: rotate(45deg) scale(1);
                }
            }
            .heart:before{
                content: '';
                position: absolute;
                top: -100px;
                width: 200px;
                height: 101px;
                background: #e80202;
                border-top-left-radius: 100px;
                border-top-right-radius: 100px;
            }
            .heart:after{
                content: '';
                position: absolute;
                left: -100px;
                width: 101px;
                height: 200px;
                background: #e80202;
                border-top-left-radius: 100px;
                border-bottom-left-radius: 100px;
            }
        </style>
    </head>
    <body>
        <div class="heart">
        </div>
    </body>
</html>

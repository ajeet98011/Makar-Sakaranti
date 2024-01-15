# Makar-Sakaranti
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Makar Sankranti</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
  @import url('https://fonts.googleapis.com/css?family=Montserrat:400,500,600|Muli:400,600,700&display=swap');
* {
    margin: 0;
    padding: 0;
}

body {
    background: #87cefa;
}

.kite {
    position: absolute;
    width: 100px;
    height: 100px;
    background: rgb(9, 255, 0);
    transform: rotate(45deg);
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    animation: flying 5s ease-in-out infinite;
}

.kite:before,
.kite:after {
    content: '';
    position: absolute;
}

.kite:before {
    top: 50%;
    left: -20%;
    width: 141%;
    border-top: 1px solid #000;
    transform: rotate(45deg);
}

.kite:after {
    top: 0;
    left: 0;
    width: 100px;
    height: 100px;
    border-top-left-radius: 100%;
    border-left: 1px solid #000;
    border-top: 1px solid #000;
}

.kite1 {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #deff22;
    transform: rotate(45deg);
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    animation: flying1 5s ease-in-out infinite;
}

.kite1:before,
.kite1:after {
    content: '';
    position: absolute;
}

.kite1:before {
    top: 50%;
    left: -20%;
    width: 141%;
    border-top: 1px solid black;
    transform: rotate(45deg);
}

.kite1:after {
    top: 0;
    left: 0;
    width: 100px;
    height: 100px;
    border-top-left-radius: 100%;
    border-left: 1px solid black;
    border-top: 1px solid black;
}

.tail {
    position: relative;
    top: 95px;
    left: 85px;
    width: 0;
    height: 0;
    border-left: 20px solid transparent;
    border-right: 20px solid transparent;
    border-bottom: 20px solid black;
    transform: rotate(-45deg);
    overflow: hidden;
    background: transparent;
}

@keyframes flying {
    0%,
    100% {
        top: 0%;
        left: 0%;
    }
    25% {
        top: -20%;
        left: 5%;
    }
    50% {
        top: -15%;
        left: 20%;
    }
    75% {
        top: -10%;
        left: 5%;
    }
}

@keyframes flying1 {
    0%,
    100% {
        top: -30%;
        left: -30%;
    }
    25% {
        top: -20%;
        left: 5%;
    }
    50% {
        top: -25%;
        left: 20%;
    }
    75% {
        top: -10%;
        left: 15%;
    }
}

.wish {
    position: absolute;
    right: 0;
    bottom: 0;
    z-index: -1;
    background: transparent;
    width: 100%;
}

.wish img {
    width: 500px;
    background: transparent;
}

.heading {
    color: #fff;
    text-align: center;
    letter-spacing: 5px;
    text-shadow: 5px 5px 12px rgb(232, 8, 8), 11px 16px 12px rgba(71, 103, 121, 0.8);
    font-family: 'Montserrat', sans-serif;
    font-weight: 600 !important;
    letter-spacing: 1px;
    text-transform: uppercase;
    width: 100%;
    font-size: 80px;
}

#background-wrap {
    bottom: 0;
    left: 0;
    padding-top: 50px;
    position: fixed;
    right: 0;
    top: 0;
    z-index: -2;
}


/* KEYFRAMES */

@-webkit-keyframes animateCloud {
    0% {
        margin-left: -1000px;
    }
    100% {
        margin-left: 100%;
    }
}

@-moz-keyframes animateCloud {
    0% {
        margin-left: -1000px;
    }
    100% {
        margin-left: 100%;
    }
}

@keyframes animateCloud {
    0% {
        margin-left: -1000px;
    }
    100% {
        margin-left: 100%;
    }
}


/* ANIMATIONS */

.move {
    -webkit-animation: animateCloud 35s linear infinite;
    -moz-animation: animateCloud 35s linear infinite;
    animation: animateCloud 35s linear infinite;
    -webkit-transform: scale(0.65);
    -moz-transform: scale(0.65);
    transform: scale(0.65);
}

.Move {
    -webkit-animation: animateCloud 20s linear infinite;
    -moz-animation: animateCloud 20s linear infinite;
    animation: animateCloud 20s linear infinite;
    -webkit-transform: scale(0.3);
    -moz-transform: scale(0.3);
    transform: scale(0.3);
}

.ajeet {
    -webkit-animation: animateCloud 30s linear infinite;
    -moz-animation: animateCloud 30s linear infinite;
    animation: animateCloud 30s linear infinite;
    -webkit-transform: scale(0.5);
    -moz-transform: scale(0.5);
    transform: scale(0.5);
}

.kali {
    -webkit-animation: animateCloud 18s linear infinite;
    -moz-animation: animateCloud 18s linear infinite;
    animation: animateCloud 18s linear infinite;
    -webkit-transform: scale(0.4);
    -moz-transform: scale(0.4);
    transform: scale(0.4);
}

.x5 {
    -webkit-animation: animateCloud 25s linear infinite;
    -moz-animation: animateCloud 25s linear infinite;
    animation: animateCloud 25s linear infinite;
    -webkit-transform: scale(0.55);
    -moz-transform: scale(0.55);
    transform: scale(0.55);
}


/* OBJECTS */

.cloud {
    background: #fff;
    background: -moz-linear-gradient(top, #fff 5%, #f1f1f1 100%);
    background: -webkit-gradient(linear, left top, left bottom, color-stop(5%, #fff), color-stop(100%, #f1f1f1));
    background: -webkit-linear-gradient(top, #fff 5%, #f1f1f1 100%);
    background: -o-linear-gradient(top, #fff 5%, #f1f1f1 100%);
    background: -ms-linear-gradient(top, #fff 5%, #f1f1f1 100%);
    background: linear-gradient(top, #fff 5%, #f1f1f1 100%);
    filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#fff', endColorstr='#f1f1f1', GradientType=0);
    -webkit-border-radius: 100px;
    -moz-border-radius: 100px;
    border-radius: 100px;
    -webkit-box-shadow: 0 8px 5px rgba(0, 0, 0, 0.1);
    -moz-box-shadow: 0 8px 5px rgba(0, 0, 0, 0.1);
    box-shadow: 0 8px 5px rgba(0, 0, 0, 0.1);
    height: 120px;
    position: relative;
    width: 350px;
}

.cloud:after,
.cloud:before {
    background: #fff;
    content: '';
    position: absolute;
    z-indeX: -1;
}

.cloud:after {
    -webkit-border-radius: 100px;
    -moz-border-radius: 100px;
    border-radius: 100px;
    height: 100px;
    left: 50px;
    top: -50px;
    width: 100px;
}

.cloud:before {
    -webkit-border-radius: 200px;
    -moz-border-radius: 200px;
    border-radius: 200px;
    width: 180px;
    height: 180px;
    right: 50px;
    top: -90px;
}

.kite .thread,
.kite1 .thread {
    position: absolute;
    width: 2px;
    /* Adjust the thickness of the thread as needed */
    height: 100%;
    background: #333;
    /* Change the color of the thread */
    top: 0;
    left: 50%;
    transform: translateX(-50%);
}

.kite .thread {
    transform: rotate(45deg) translateX(-50%);
}

.kite1 .thread {
    transform: rotate(45deg) translateX(-50%);
}

.wish img {
    width: 500px;
    background: transparent;
    animation: floatAnimation 4s ease-in-out infinite;
}

@keyframes floatAnimation {
    0%,
    100% {
        transform: translateX(10);
    }
    50% {
        transform: translateX(40px);
    }
}
</style>


<body>

    <div id="background-wrap">
        <div class="Move">
            <div class="cloud"></div>
        </div>

        <div class="move">
            <div class="cloud"></div>
        </div>

        <div class="size">
            <div class="cloud"></div>
        </div>

        <div class="ajeet">
            <div class="cloud"></div>
        </div>

        <div class="kali">
            <div class="cloud"></div>
        </div>
    </div>

    <div class="kite">
        <div class="tail"></div>
        <div class="thread"></div>
    </div>

    <div class="kite1">
        <div class="tail"></div>
        <div class="thread"></div>
    </div>

    <div class="wish">
        <img src="https://freepngimg.com/thumb/makar_sankranti/96630-makar-sankranti-cartoon-child-line-for-happy-countdown.png">
        <h1 class="heading">Happy Makar Sankranti</h1>
        <h2><pre>               🪁 Like the vibrant kites in the sky, may your aspirations soar and your spirit stay unbroken. Happy Uttarayan!</pre></h2>
    </div>

</body>

</html>

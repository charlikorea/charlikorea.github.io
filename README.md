<!DOCTYPE html>
<html lang="es">
    <head>
        <link rel="stylesheet" type="text/css" href="meperdonas.css">
        <title>I love you amor</title>
    </head>
    <body>

        <div class="heart"></div>
        <h1>Te amo tuti</h1>




    </body>
</html>


body{
    margin: 0;
    padding: 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #0b1522;
}

.heart{
    height: 70px;
    width: 70px;
    background: #f20044;
    transform:rotate(-45deg) ;
    box-shadow: -10px 10px 90px #f20044;
    animation: heart 0.6s linear infinite;
}

@keyframes heart{
    0%{
        transform: rotate(-45deg) scale(1.07)
    }
    80%{
        transform: rotate(-45deg) scale(1.0);
    }

    100%{
        transform: rotate(-45deg) scale( 0.8);
    }
}


.heart::before{
    content: "";
    position: absolute;
    height: 70px;
    width: 70px;
    background: #f20044;
    top: -50%;
    border-radius: 50px;
    box-shadow: -10px -10px 90px #f20044;
}


.heart::after{
    content: "";
    position: absolute;
    height: 70px;
    width: 70px;
    background: #f20044;
    right: -50%;
    border-radius: 50px;
    box-shadow: -10px -10px 90px #f20044;
}
h1{
    color: aliceblue;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    position: relative;
    vertical-align: bottom;
    bottom: -100px;
    right: 100px;
    font-style: oblique;
    animation: h1 3s linear infinite
}


@keyframes h1 { 
    0%{
        transform: scale(1.1);
    }


    50%{
        transform: scale(1.3);
    }


    100%{
        transform: scale(0.7);
    }
}

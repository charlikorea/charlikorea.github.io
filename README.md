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


# Stefanie-Posavec
Web page presentation
<!DOCTYPE html>
<!-- sin estilo, solo elementos -->
<!-- ver mas elementos en http://www.w3schools.com/tags/ref_byfunc.asp -->
<html>
<head>
    <meta charset="UTF-8"/>
    <title> HTML 1 - v1</title>
    <link href="https://fonts.googleapis.com/css?family=Abril+Fatface" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Concert+One" rel="stylesheet">


    <style type="text/css">
    body {
        background: pink;
    }
    #container{
        width: 800px;
        background: white;
        padding: 2px;
        margin-left: 5px;
    }

    .caja{
        width: 700px;
        background: yellow;
        padding: 2px;
        margin: 10px;
    }

    img {
        width: 400px;
        padding: 10px;
        margin: 0px;
        border: 5px solid green;
    }

    h1{
        background: yellow;
        padding: 2px;
        font-family: 'Abril Fatface', cursive;
        font-size: 42px;
        color: grey;
    }

    h2{
        background: yellow;
        padding: 2px;
        font-family: 'Concert One', cursive;
        font-size: 32px;
        color: black;
    }

    p{
        background: yellow;
        padding: 2px;
        font-family: serif;
        font-size: 18px;
        color: black;
    }

</style>

     
</head>


<body>
 
    <div id="container">
        <h1>Este es un Título h1</h1>

        <div class="caja">
            <h2>Hola papurri</h2>
            <img src="img/01.jpg">
              <p>este es un parrafo con un link a <a href="http://www.theclinic.cl" target="_blank">The Clinic</a></p>
        </div>

        <div class="caja">
            <h2>Este es un Título h2</h2>
            <img src="img/02.jpg">
              <p>Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. </p>
        </div>

        <div class="caja">
            <h2>Este es un Título h2</h2>
            <img src="img/03.jpg">
              <p>Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. Texto largo. </p>
        </div>



    </div>


</body>
</html>

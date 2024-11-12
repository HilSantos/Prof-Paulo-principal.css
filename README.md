# Prof-Paulo-principal.css

body{
    font-family: Arial, Helvetica, sans-serif;
    width: 1000px;
    margin-left: auto;
    margin-right: auto;
}

header h1{
    width: 240px;
    float: left;
    background-image: url(../Multimidia/meu-amigo-cao-petshop-header.png);
    background-repeat: no-repeat;
    background-position: center center;
    height: 200px;
    text-indent: -1000px;
    margin-bottom: 0;
}

header #anuncio{
    width: 510px;
    float: left;
    margin: 80px auto auto;
    padding-top: 0;
}

header section a[href="boletim.html"]{
    border: solid #c0262c thin;
    padding: 15px;
    border-radius: 15px;
    color: #c0262c;
    text-decoration: none;
    font-size: 1em;
}

header section{
    padding-top: 70px;
}

header section p{
    color: #999999;
    margin: 33px auto 7px;
}

header section figure{
    width: 100%;
    margin: 0;
}

header section figure a{
    padding: 25px 5px 0 ;
    border: none;
}

header section figure a:first-child{
    padding: 25px 5px 0 0;
}

header section figure a:last-child{
    padding: 25px 0 0 5px;
}

/* barra de navegação */

nav{
    background-color: #000;
    overflow: auto;
    clear: both;
    margin-top: 10px;
}

nav ul{
    list-style: none;
    padding-left: 0;
    margin-top: 1px;
}

nav ul li{
    float: left;
}

nav ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 1.2em;
    padding: 8px 50px;
    line-height: 2em;
}

#inicial a[href="index.html"],
#quemSomos a[href="quem-somos.html"],
#produtos a[href="produtos.html"],
#banhoEtosa a[href="banho-e-tosa"],
#curiosidade a[href="curiosidades.html"]{
background-color: #c0262c;
}

#inicial aside{
    width: 230px;
    float: left;
    margin-top: 30px;
}

#inicial main{
    width: 490px;
    float: left;
    margin: 30px 25px 10px;
}

footer{
    clear: both;
    border-top: 7px solid #999;
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 10px;
}

footer p{
    margin: 0;
}

main h1{
    color: #c0262c;
    font-size: 2.5em;
    border-bottom: #c0262c solid thin;
    padding-bottom: 7px;
}

main h2{
    font-size: 1.75em;
    background: url(../Multimidia/back-bolinha.gif) repeat top center;
    color: #fff;
    letter-spacing: 0.1em;
    padding: 7px;
    width: 316px;

}
main p{
    font-size: 1.1em;
    line-height: 1.3em;
    text-align: justify;
}
main h2+p:first-line{
    font-size: 1.17em;
    font-variant: small-caps;
    font-weight: bolder;
    font-style: italic;
}
main hr{
    border-color: #c0262c;
}

/* produtos */

#produtos table{
    width: 600px;
    margin: 50px auto 30px;
    text-align: center;
    border-collapse: collapse;
}

#produtos th, #produtos td{
    border: #999 solid 1px;
    padding: 5px;
}

#produtos caption{
    background-color: #999;
    color: #fff;
    padding: 15px 0;
    font-size: 1.5em;
}

#produtos td[colspan]{
    font-style: italic;
    font-weight: bold;
    color: #999;
}

#produtos tr:hover{
    background-color: #feff76;
}

/* boletim */

form{
    background-color: #999;
    margin: 30px 0;
    padding: 20px;
    border-radius: 0 15px;
}

input[type="submit"]{
    background-color: #c0262c;
    background: linear-gradient(to bottom,#6b1516 0%,#c0262c 30%,#c0262c 70%, #6b1516 100%);
    border: none;
    border-radius: 30px;
    font-size: 1.2em;
    color: #fff;
    padding: 10px 30px;
    margin: 20px 0;
    text-shadow: 2px 2px 5px #000;
    cursor: pointer;
}

input#nome, input#email{
    background-color: transparent;
    border: none;
    border-bottom: #000 solid 1px;
    font-size: 1.2em;
    color: #fff;
    width: 800px;
}

::-webkit-input-placeholder{
    color: #465c29;
    font-style: italic;
    font-size: .8em;
}

::-moz-placeholder{
    color: #465c29;
    font-style: italic;
    font-size: .8em;
}

:-ms-input-placeholder{
    color: #465c29;
    font-style: italic;
    font-size: .8em;
}

label{
    display: block;
    margin-top: 7px;
    float: left;
    width: 60px;
}

/* banho e tosa - formulario */

#banhoEtosa fieldset{
    background-color: #fff;
    border: none;
    border-radius: 0 15px;
    margin-bottom: 20px;
}

#banhoEtosa fieldset legend{
    background-color: #c0262c;
    color: #fff;
    font-weight: bold;
    letter-spacing: 0.05em;
    padding: 10px;
    margin-left: 13px;
}

#banhoEtosa fieldset label{
    display: block;
    margin-top: 7px;
    float: left;
    width: 115px;
}

#banhoEtosa fieldset input[type="text"],
#banhoEtosa fieldset input[type="email"]{
    border: none;
    border-bottom: #000 solid 1px;
    font-size: 1.2em;
    color: #000;
    width: 770;
}

#banhoEtosa fieldset textarea{
    width: 750px;
    height: 100px;
    font-size: 1.2em;
    border: #000 solid 1px;
}

#banhoEtosa fieldset label.labelSimples{
    display: inline;
    float: none;
}

#banhoEtosa p{
    text-align: left;
}

#banhoEtosa p:first-line{
    font-size: inherit;
    font-variant: inherit;
    font-weight: inherit;
    font-style: inherit;
}

#banhoEtosa main h2{
    background: url(../Multimidia/postit.jpg)
    no-repeat top left;
    color: #000;
    padding: 35px;
    width: 207px;
    height: 115px;
    font-size: 1.3125;
    letter-spacing: 0.07em;
}

/* Quem somos */

#quemSomos main img{
    float: left;
    margin: 0 20px 20px 0;
    padding: 10px;
    border: solid #c0262c thin;
    background-color: #fff;
}

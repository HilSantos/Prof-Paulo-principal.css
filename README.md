# Prof-Paulo-principal.css

body{
    font-family: Arial, Helvetica, sans-serif;
}



h1{
    color: #c0262c;
    font-size: 2.5em;
    border-bottom: #c0262c solid thin;
    padding-bottom: 7px;
}

h2{
    font-size: 1.75em;
    background: url(../Multimidia/back-bolinha.gif) repeat top center;
    color: #fff;
    letter-spacing: 0.1em;
    padding: 7px;
    width: 316px;

}
p{
    font-size: 1.1em;
    line-height: 1.3em;
    text-align: justify;
}
p:first-line{
    font-size: 1.17em;
    font-variant: small-caps;
    font-weight: bolder;
    font-style: italic;
}
hr{
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

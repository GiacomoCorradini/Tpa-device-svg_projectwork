# DII - Tecniche di programmazione avanzata

Homework 1

### SVG device

Macchina

Parametri da inserire:
_ Altezza macchina
_ Lunghezza macchina
_ Dimensioni ruote
_ Posizione x delle ruote

<?xml version="1.0" encoding="UTF-8" standalone="no"?> 

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="600">

    <!--Rettangolo bianco-->
    <rect  x="0" y="0" width="800" height="600" style="fill:rgb(255,255,255);stroke-width:3;stroke:rgb(0,0,0)"/>

    <!--Carrozzeria-->
    <rect  x="100" y="430" rx="10" ry="10" width="350" height="80" style="stroke-width:3;stroke:rgb(0,0,0)" fill="red"/>  

    <!--Ruote-->
    <circle cx="170" cy="500" r="40" stroke="black" stroke-width="3" fill="black" />

    <circle cx="370" cy="500" r="40" stroke="black" stroke-width="3" fill="black" />

    <circle cx="170" cy="500" r="25" stroke="black" stroke-width="3" fill="gray" />

    <circle cx="370" cy="500" r="25" stroke="black" stroke-width="3" fill="gray" />

    <!--Finestrini-->
    <polygon points="160,430 200,370 300,370 300,430 160,430" style="fill:red;stroke:black;stroke-width:5" />
    
    <polygon points="300,370 380,430 300,430" style="fill:lightblue;stroke:black;stroke-width:5" />

    <!--Spoiler-->
    <rect  x="110" y="400" width="20" height="30" style="stroke-width:3;stroke:rgb(0,0,0)" fill="red"/>  
 
</svg>

### SVG MACHINE

Macchina + .....
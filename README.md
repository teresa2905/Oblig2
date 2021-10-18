# Oblig2
 
 Koden: 
    article {
        border-bottom: 0.1px solid darkgrey;
        width: 100%;
        column-count: 2;
        column-gap: 10%;
        column-width: 45%;
    }

    article > img, div {
        display: inline-block;
        width: 100%;
    }
Fungerer fint på safari, men ikke chrome, de vil ikke komme ved siden av hverandre med inline-block, og uten kommer det tekst under/over bildene

Vi kan alternativt ha koden:
    article {
        border-bottom: 0.1px solid darkgrey;    
    }

    article > img, div {
        width: 45%;
        margin: 0 2%;
        display: inline-block;
        vertical-align: middle;
    }
Slikt kommer det ikke tekst under/over bildene

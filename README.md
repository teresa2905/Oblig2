# Oblig2
 
Linkto GitHub pages: https://teresa2905.github.io/Oblig2/

Name and Student number:
    Fahmi Haybe Mohammed, s362106
    Behdad Nikkah,s362085
    Teresa Pham, s345368


Måtte laste opp index.html og style.css på nytt slik at det var i top nivået i repository, hadde det i en mappe


I screens 600px–960px og screens >960px virker columns forskjellig på chrome og safari

    article > div > * {
            display: inline-block;
        }
Denne fungerer fint på chrome, men på safari kommer teksten under bildet i tredje article "Eliminate gender disparities"

    article > div, img > * {
            display: inline-block;
        }
Mens denne fungerer fint på safari, kommer alt innholdet i den ene kolonnen på chrome (har prøvd font-size: 0; på parent container og font-size: 1.rem; på child, men fungerer fortsatt ikke)
Napisao Ivan Jonjić Pavin (IJPantic na github-u), 24. listopada, 2026.

    KRATKE UPUTE:

        Isarani obli kvadrat koji se nalazi na nekoj rupi predstavlja da ta prikljucnica treba ici na uzemljenje:

            Emiter od tranzistora,
            Katoda od ispravljacke diode,
            Katoda od LED zarulje,
            Prikljucnica uzemljenja GND.

        Isarani obli prvokutnik u donjem desnom uglu predstvalja dodatni, neobavezni prostor koji se moze koristiti za korekcie gresaka

        Prikljucnice:

            ConnA predstavlja konekciju ulaza a binarnog zbrajala
            ConnB predstavlja konekciju ulaza b binarnog zbrajala
            ConnC predstavlja konekciju ulaza c binarnog zbrajala ("Carry in", eng.)
            ConnP predstavlja konekciju izlaza p binarnog zbrajala koji se koristi za kaskadiranje vise binarnih zbrajala ("Propagate", eng.)
            ConnY predstavlja konekciju izlaza y binarnog zbrajala (Rezultat zbrajanja)
            Conn5V predstavlja konekciju napajanja binarnog zbrajala (Idealno 5V)
            ConnGND predstavlja konekciju uzemljenja binarnog zbrajala ("GND", eng.)

        Varijacije plocice:

            U kaskadi punih binarnih zbrajala, sve plocice u nizu osim zadnje, trebaju na mjestu komponente LED P napraviti kratki spoj, bilo vanjskom zicom ili tragom bakra

        Dimenzije plocice:

            Na plocicu se treba nacrtati resetku (Lagano olovkom) dimenzija 25x13 polja, za velicinu stranica kvadrata preporuca se 4mm (Potrebna plocica dimenzija 10x5cm)

        KiCAD datoteke:

            Za otvaranje KiCAD datoteka sheme spoja i pcb sheme preporucaje se koristi kicad-10.0.3 verziju programa (KiCAD je FOSS)


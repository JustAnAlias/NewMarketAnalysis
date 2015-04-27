# NewMarketAnalysis
School Project

Specifications below in Danish...

Brief
Til: Datamatikerne
Fra: MAK Gruppe 2
Emne: Programmering af udvælgelsesprogram
Dato: 17/4 2015
Korsbæk på Bakken
Vi har fået til opgave, at undersøge forskellige markeder, som kunne være mulige at eksportere konceptet
“Korsbæk på Bakken” til. Korsbæk på Bakken er en ny del af Bakken hvor, man har bygget Korsbæk by fra TVserien
Matador. Byen består af forskellige restauranter placeret i nogle af karaktererne fra seriens boliger. Her
kan man opleve karaktererne, deres hjem og mad. Generelt skaber Korsbæk på Bakken stemningen og
følelsen af at være med i et afsnit af Matador, og skildrer samtidig atmosfæren og tiden i 1930’erne.
Se mere om konceptet her: http://www.korsbaek-bakken.dk
Formål med produktet/programmet:
Vi skal bruge et overskueligt værktøj/program, som vi kan bruge til at rangere mulige eksportmarkeder
(lande). Vi vil gerne finde ud af hvilket land der opfylder vores kriterier bedst. Derved kan vi finde ud af,
hvilket land, der er den bedste mulighed, at eksportere konceptet “Korsbæk på Bakken” til.
Beskrivelse af produktet:
Et program hvor vi kan strukturer en række forskellige faktorer i en tabel eller lignende. De elementer vi skal
have med i programmet er en række forskellige lande, hvor vi skal have plottet nogle forskellige
informationer ind for hvert land. Informationerne for hvert land er:
- Kriterier: Hvilke kriterier der er vigtige for landet at opfylde. (antallet af kriterier skal være fleksibelt).
Det kan fx være BNP og vækst.
- Vigtighed: Hvor vigtigt hvert kriterier er. (vægten af alle kriterierne sammenlagt må i alt kun give 25
point)
- Skala: Her vurderes det, hvor meget det givne land scorer på hvert kriterium. Dette er på en skala
fra 0-4.
- Point: Vigtigheden og skalaen ganget sammen, til et samlet point for kriteriet. Så hvis nu et kriterie
var vægtet til 3, og et land score 10, så får det 0 point.
Kriterierne og vigtigheden er konstante, altså er de ens for hvert lands tabel. Derudover skal skala og point
være variable, så vi kan ændre i dem (da disse ikke er ens for hvert enkelte land).
Vores krav til funktionalitet:
Der skal være en tabel/oversigt for hvert land.
Programmet skal kunne udregne pointene til de forskellige kriterier (vigtig*skala). Derudover skal det også
kunne udregne summen af pointene sammen for hvert land, dvs. den totale score for landet.
Vi ønsker, at man i programmet kan have flere tabeller/oversigter ved siden af hinanden, så vi kan
sammenligne de totale point for de forskellige lande. Derudover vil vi gerne have, at programmet kan
fremhæve det land, der scorer den højeste samlede score.

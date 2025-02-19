# EmailBestand

Lees uit het tekstbestand *Email.txt* de namen en de e-mailadressen en
toon deze in een TextBox. Zorg voor een correcte lay-out. Voorzie een
gestructureerde foutafhandeling wanneer het bestand niet gevonden kan
worden en wanneer er zich een onverwachte fout kan voordoen.

![](./media/image1.png)

-   De opdrachtknop **Inlezen** leest het bestand in een StringBuilder
    en drukt het af in het linker tekstvak *resultTextBox*. Gebruik
    hiervoor de functie *StringBuilder InlezenBestand(string
    bestandsnaam).*

-   De opdrachtknop ***Inlezen/Dialoogvenster*** maakt gebruik van
    OpenFileDialog om het juiste bestand te openen om in te lezen met de
    functie *InlezenBestand()*.

![](./media/image2.png)

-   Met de opdrachtknop *Inlezen/Dictionary* wordt het bestand ingelezen
    in een dictionary *Dictionary\<string, string\> dicGeg* en afgedrukt
    in resultTextBox.

-   De opdrachtknop *Wegschrijven / Dictionary* gebruikt de dictionary
    *dic*G*eg* om de e-mailadressen weg te schrijven naar een nieuw
    bestand *Adressen.txt*.

-   De opdrachtknop *Toevoegen* zorgt ervoor dat de ingevoerde gegevens
    toegevoegd worden aan het bestand *Email.txt*. Gebruik hier een
    SaveFileDialog voor.

![](./media/image3.png)

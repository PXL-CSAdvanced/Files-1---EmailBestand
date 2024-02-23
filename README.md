# EmailBestand

Lees uit het tekstbestand *Email.txt* de namen en de e-mailadressen en
druk af in TxtResultaat. Zorg voor een correcte lay-out. Voorzie een
gestructureerde foutafhandeling wanneer het bestand niet gevonden kan
worden en wanneer er zich een onverwachte fout kan voordoen.

![Afbeelding met tekst, schermopname, software, nummer Automatisch
gegenereerde
beschrijving](./media/image1.png){width="6.291119860017498in"
height="2.44913167104112in"}

-   De opdrachtknop **Inlezen** leest het bestand in een StringBuilder
    en drukt het af in het linker tekstvak *TxtResultaat*. Gebruik
    hiervoor de functie *StringBuilder InlezenBestand(string
    bestandsnaam).*

-   De opdrachtknop ***Inlezen/Dialoogvenster*** maakt gebruik van
    OpenFileDialog om het juiste bestand te openen om in te lezen met de
    functie *InlezenBestand()*.

![Afbeelding met tekst, schermopname, software, scherm Automatisch
gegenereerde
beschrijving](./media/image2.png){width="5.049956255468066in"
height="2.8452930883639547in"}

-   Met de opdrachtknop *Inlezen/Dictionary* wordt het bestand ingelezen
    in een dictionary *Dictionary\<string, string\> dicGeg* en afgedrukt
    in TxtResultaat.

-   De opdrachtknop *Wegschrijven / Dictionary* gebruikt de dictionary
    *dic*G*eg* om de e-mailadressen weg te schrijven naar een nieuw
    bestand *Adressen.txt*.

-   De opdrachtknop *Toevoegen* zorgt ervoor dat de ingevoerde gegevens
    toegevoegd worden aan het bestand *Email.txt*. Gebruik hier een
    SaveFileDialog voor.

![Afbeelding met tekst, schermopname, software, scherm Automatisch
gegenereerde
beschrijving](./media/image3.png){width="5.438303805774278in"
height="3.0640988626421697in"}

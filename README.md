# SolidWorksExportVBA

SolidWorks Export Macro
🔧 Beschrijving
Deze macro voor SolidWorks automatiseert het exporteren van 3D-modellen naar meerdere bestandsformaten. Het script werkt met zowel parts (.SLDPRT) als assemblies (.SLDASM) en genereert de volgende exports:

✅ STEP-bestand (.STEP)

✅ 3D PDF-bestand (.PDF)

✅ 2D PDF van de tekening (.PDF) (indien een .SLDDRW-bestand met dezelfde naam aanwezig is)

Dit versnelt het exportproces en garandeert consistente output voor productie, klantcommunicatie of archivering.

▶️ Functionaliteit
Detecteert automatisch of het actieve document een part of assembly is.

Zoekt automatisch naar een bijbehorende .SLDDRW tekening in dezelfde map.

Exporteert de bestanden naar dezelfde map als het originele model.

Werkt volledig automatisch met minimale gebruikersinteractie.

📁 Voorbeeldoutput
Bij bestand Behuizing.SLDPRT worden de volgende bestanden gegenereerd:

scss
Kopiëren
Bewerken
Behuizing.STEP
Behuizing_3D.pdf
Behuizing.pdf (alleen als Behuizing.SLDDRW bestaat)
🚀 Gebruik
Sla de macro op als .swp-bestand in SolidWorks.

Voeg de macro toe aan een knop via Tools > Customize > Commands > Macro.

Open een part of assembly en klik op de knop om de bestanden automatisch te exporteren.

💡 Vereisten
SolidWorks 2020 of nieuwer (3D PDF-export vereist Premium of Professional)

VBA Macro-functionaliteit ingeschakeld

📜 Licentie
MIT License – vrij te gebruiken en aan te passen.


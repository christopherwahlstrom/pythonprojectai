# Python Project AI
Det egna projektet av Christopher Wahlström


Projektsbeskrivning

1. Projektidé och Syfte

  Projektidé
  Genom mitt projekt syftar jag till att utveckla en AI-driven modell som kan försöka förutsäga vädermönster baserat på historiska data. Genom att analysera parametrar som temperatur, luftfuktighet och nederbörd vill jag skapa en modell som ger framtida prognoser inom . 

  Syfte
  Mitt mål är att bygga en prediktiv modell som kan bidra till mer precisa väderprognoser genom att analysera historiska väderdata för att kunna förutsäga framtida väderhändelser. Detta skulle man kunna använda som stöd inom jordbruk, logistik sektorn eller för andra branscher där väderförutsägelser skulle kunna vara bra att ha.

2. Val av dataset
   
  Jag har initialt valt ett dataset från Kaggle (länk: [Kaggle Weather Prediction Dataset](https://www.kaggle.com/datasets/ananthr1/weather-prediction)) eftersom det innehåller omfattande historisk väderdata som kan hjälpa modellen att identifiera mönster i väderförändringar över tid.

  Egenskaper och Kvalitet

  Datastorlek: Datasetet från Kaggle verkar ha en stor mängd poster med väderrelaterad data, vilket ger en bra bas för att träna maskininlärningsmodeller.
  Innehåll: Datasetet innehåller viktiga väderparametrar som temperatur, luftfuktighet och vindhastighet.
  Datakvalitet: Vid första inspektion av datasetet verkar datan vara relativt komplett men kan innehålla vissa tomma värden (null-värden) och eventuella outliers som kräver förbehandling av datan. 

3. Mål med Projektet
  Personliga lärandemål

  Med detta projekt skulle jag vilja fördjupa mina kunskaper inom maskininlärning, särskilt för regressionsproblem, samt förbättra mina färdigheter i dataförbehandling och modellutvärdering. Jag skulle även vilja lära mig att hantera och bearbeta väderrelaterade data, vilket kan ha praktiska tillämpningar inom många olika områden.
  
  Praktiska mål
  
  Målet är att utveckla en modell som kan ge prognoser för väderförhållanden baserat på historiska data. Modellen ska vara tillräckligt robust för att identifiera mönster och kunna förutsäga vädret över en viss period med rimlig noggrannhet.

4. Val av Modell och Alternativ

  Initiala Modeller
  För detta projekt överväger jag att börja med arbeta med regressionsmodeller som linjär regression för att få en grundläggande förståelse för datasetet och dess mönster. Därefter skulle jag eventuellt kunna gå vidare till mer avancerade tidsseriealgoritmer som LSTM (Long Short-Term Memory) neural nätverk, som ska vara bra lämpade för sekventiell data som   
  väder.

  Utforskningsmöjligheter
  Eftersom olika modeller kan prestera olika bra beroende på datans struktur, planerar jag att jämföra deras prestanda och utvärdera vilken som ger mest exakta resultat. Det här kan innebära att experimentera med olika parametrar och strukturer för att hitta den optimala modellen för väderförutsägelse.

5. Teknisk Plattform
  Val av verktyg och miljöer
  Jag kommer att implementera projektet i Python, och med Jupyter Notebook som jag kommer att använda för dataanalys och modellträning. För modellering och maskininlärning planerar jag att använda bibliotek som TensorFlow/Keras för djupa neurala nätverk och Scikit-learn för enklare regressionsmodeller.

6. Kommande Utveckling i projektet
  * Dataförbehandling: Utföra grundläggande dataanalys för att identifiera eventuella tomma värden och outliers, samt normalisera och skala data.
  * Modellval och Träning: Jag kommer börja med enkla modeller och gradvis övergå till mer avancerade tekniker om nödvändigt.
  * Utveckling och Utvärdering: Efter modellträning kommer jag att utvärdera modellen och försöka justera den för att förbättra noggrannheten. Målet är att slutföra en grundläggande version till slutgiltiga inlämningen.

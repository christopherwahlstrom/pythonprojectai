# Python Project AI
Det egna projektet av Christopher Wahlström

## Projektsbeskrivning

### 1. Projektidé och Syfte

#### Projektidé
Genom mitt projekt syftar jag till att utveckla en AI-driven modell som kan försöka förutsäga vädermönster baserat på historiska data. Genom att analysera parametrar som temperatur, luftfuktighet och nederbörd vill jag skapa en modell som ger framtida prognoser inom .

#### Syfte
Mitt mål är att bygga en prediktiv modell som kan bidra till mer precisa väderprognoser genom att analysera historiska väderdata för att kunna förutsäga framtida väderhändelser. Detta skulle man kunna använda som stöd inom jordbruk, logistik sektorn eller för andra branscher där väderförutsägelser skulle kunna vara bra att ha.

### 2. Val av dataset

Jag har initialt valt ett dataset från Kaggle (länk: [Kaggle Weather Prediction Dataset](https://www.kaggle.com/datasets/ananthr1/weather-prediction)) eftersom det innehåller omfattande historisk väderdata som kan hjälpa modellen att identifiera mönster i väderförändringar över tid.

#### Egenskaper och Kvalitet

- **Datastorlek**: Datasetet från Kaggle verkar ha en stor mängd poster med väderrelaterad data, vilket ger en bra bas för att träna maskininlärningsmodeller.
- **Innehåll**: Datasetet innehåller viktiga väderparametrar som temperatur, luftfuktighet och vindhastighet.
- **Datakvalitet**: Vid första inspektion av datasetet verkar datan vara relativt komplett men kan innehålla vissa tomma värden (null-värden) och eventuella outliers som kräver förbehandling av datan.

### 3. Mål med Projektet

#### Personliga lärandemål
Med detta projekt skulle jag vilja fördjupa mina kunskaper inom maskininlärning, särskilt för regressionsproblem, samt förbättra mina färdigheter i dataförbehandling och modellutvärdering. Jag skulle även vilja lära mig att hantera och bearbeta väderrelaterade data, vilket kan ha praktiska tillämpningar inom många olika områden.

#### Praktiska mål
Målet är att utveckla en modell som kan ge prognoser för väderförhållanden baserat på historiska data. Modellen ska vara tillräckligt robust för att identifiera mönster och kunna förutsäga vädret över en viss period med rimlig noggrannhet.

### 4. Val av Modell och Alternativ

#### Initiala Modeller
För detta projekt överväger jag att börja med arbeta med regressionsmodeller som linjär regression för att få en grundläggande förståelse för datasetet och dess mönster. Därefter skulle jag eventuellt kunna gå vidare till mer avancerade tidsseriealgoritmer som LSTM (Long Short-Term Memory) neural nätverk, som ska vara bra lämpade för sekventiell data som väder.

#### Utforskningsmöjligheter
Eftersom olika modeller kan prestera olika bra beroende på datans struktur, planerar jag att jämföra deras prestanda och utvärdera vilken som ger mest exakta resultat. Det här kan innebära att experimentera med olika parametrar och strukturer för att hitta den optimala modellen för väderförutsägelse.

### 5. Teknisk Plattform

#### Val av verktyg och miljöer
Jag kommer att implementera projektet i Python, och med Jupyter Notebook som jag kommer att använda för dataanalys och modellträning. För modellering och maskininlärning planerar jag att använda bibliotek som TensorFlow/Keras för djupa neurala nätverk och Scikit-learn för enklare regressionsmodeller.

### 6. Utvecklingen i projektet

- **Dataförbehandling**: Utföra grundläggande dataanalys för att identifiera eventuella tomma värden och outliers, samt normalisera och skala data.
- **Modellval och Träning**: Jag kommer börja med enkla modeller och gradvis övergå till mer avancerade tekniker om nödvändigt.
- **Utveckling och Utvärdering**: Efter modellträning utvärderar modellen och försöka justera den för att förbättra noggrannheten. Målet är att slutföra en grundläggande version till slutgiltiga inlämningen.

### Motivering för valet av algoritmer och olika modeller för mitt projekt

För detta projektet valde jag att prova på linjär regression och ett tips jag läste om på nätet som kallas Random Forest som initiala modeller , samt en Deep Learning metod:

- **Linjär regression**: Valde jag för att det är hyffsat enkelt att implementera och ger en baslinje för att förstå linjära samband mellan variabler.
- **Random Forest**: Använde jag då det ska var robust med möjlighet att överanpassa samtidigt som det hanterar icke linjära samband och funkar bra för både numeriska och kategoriska data vilket behöver hanteras i analysen av väder.

## Slutsats

Genom detta projekt har jag utvecklat en modell för att förutsäga vädermönster baserat på historiska data. Jag började med att utforska och förbehandla datasetet, vilket inkluderade att hantera tomma värden och normalisera data. Därefter implementerade jag och utvärderade olika modeller, inklusive linjär regression och Random Forest.

### Resultat

- **Linjär Regression**: Denna modell gav en grundläggande förståelse för linjära samband mellan variablerna och fungerade som en bra baslinje.
- **Random Forest**: Denna modell visade sig vara mer robust och hanterade både numeriska och kategoriska data effektivt. Den kunde också fånga icke-linjära samband i datasetet.

### Reflektioner

- **Modellprestanda**: Random Forest-modellen presterade bättre än linjär regression i att förutsäga `temp_max`, vilket visar på vikten av att använda mer avancerade modeller för komplexa dataset.
- **Dataförbehandling**: Förbehandling av data, inklusive One-Hot Encoding och skalning, var avgörande för att förbättra modellens prestanda.
- **Framtida Arbete**: För framtida arbete kan det vara intressant att utforska mer avancerade tidsseriealgoritmer som LSTM (Long Short-Term Memory) neural nätverk för att ytterligare förbättra förutsägelserna.

### Sammanfattning

Projektet har gett mig värdefulla insikter i hur man kan använda maskininlärning för att förutsäga vädermönster. Genom att jämföra olika modeller och deras prestanda har jag lärt mig mycket om dataförbehandling, modellutvärdering och hur man hanterar väderrelaterade data. Denna kunskap kan vara användbar i mer avancerat utförande med en större data som grund inom många olika områden där väderförutsägelser är viktiga, såsom jordbruk och logistik.
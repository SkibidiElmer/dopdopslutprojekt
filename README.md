# 📊 Shoe Prices – Dataanalys och Visualisering  
**Slutprojekt – Programmering 1, VT 2025**  
Av: Elmer  

---

## 🔗 Länkar  
- [Trello Board – Projektplanering](https://trello.com/b/jINeN9jO)  
- [Dataset – Shoe Prices (CSV)](https://www.kaggle.com/datasets/rkiattisak/shoe-prices-dataset)  
- [GitHub Repository](https://github.com/SkibidiElmer/dopdopslutprojekt)  

---

## 📝 Projektbeskrivning  

I detta projekt har jag jobbat med ett dataset om skor från Kaggle. Det innehåller info om olika skomodeller, priser, märken, storlekar och typ av sko. Jag valde det för att jag gillar skor och ville se om man kunde hitta några mönster i priser, märken och skotyper.  

Jag gjorde två olika diagram:  
- 📊 Ett stapeldiagram som visar genomsnittspriset för olika skotyper.  
- 🥧 Ett cirkeldiagram som visar vilka märken som förekom flest gånger.  

Sen gick jag ett steg längre och testade **maskininlärning** – jag använde en SVR-modell (Support Vector Regression) för att försöka förutsäga priset på skor baserat på deras märke, kön, typ och storlek. Det var rätt avancerat, men riktigt kul.  

Jag använde Python med verktyg som **Pandas**, **Matplotlib** och **Scikit-learn**. Det mesta funkade bra, men vissa saker var fett kluriga – så shoutout till Google och ChatGPT som räddade mig mer än en gång 😂  

Jag lärde mig mycket om hur man jobbar med data, visualisering och till och med lite AI.  
Om jag haft mer tid hade jag kunnat fördjupa analysen ännu mer, men ärligt talat pallar jag inte mer hahaha.  

---

## 💬 Dem tre bubblorna  

### 1. **Data**  
Jag använde Shoe Prices-datasetet som innehåller:  
- Skotyp  
- Pris  
- Märke  
- Kön  
- Storlek  

### 2. **Bearbetning**  
- Rensade datan (tog bort onödiga tecken som "$", tomma värden, osv)  
- Gjorde om kategoriska värden till siffror med OneHotEncoder  
- Skalade data med StandardScaler  
- Delade upp i träning och test  
- Tränade en SVR-modell  

### 3. **Visualisering**  
Jag gjorde två visualiseringar:  
- Stapeldiagram för genomsnittspriser per skotyp  
- Cirkeldiagram för hur ofta varje märke förekom i datan  

---

## ✅ Trello  
Min Trello-board är uppdelad i:  
- **Todo** – Att göra  
- **Doing** – Pågående  
- **Done** – Klart  

---

## 📦 Tekniker & Verktyg  
- Python 🐍  
- Pandas 🧮  
- Matplotlib 📈  
- Scikit-learn 🤖  
- Jupyter Notebook 📓  
- GitHub 🗃️  
- Trello ✅  

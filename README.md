# IMDB Actors

Vi ska nu bygga en applikation som hämtar information ifrån en JSON fil och sedan renderar ut datan. I slutändan ska vi ha något likt bilden nedan

[Bild](https://ibb.co/V3jm3rD)


# Övning 1

I videoklippen har vi lärt oss hur man importera react ifrån CDN. Nu ska vi lära oss hur man brukar göra det på de "vanliga" sätter

### Yarn

Öppna upp terminalen och kör `yarn create react-app namnet-på-din-app`

### NPM

Öppna upp terminalen och kör `npm init react-app namnet-på-din-app`

---
 1. Efter installation så navigera in i er nya mapp
 2. Öppna upp projektet i Visual Studio Code
 3. Undersök innehållet och vad för filer du har fått
 4. Starta igång projektet med att skriva `npm run start` i terminalen

# Övning 2

Du ska nu skapa tre nya mappar 

 1. Components
 2. Styling
 3. Data

Alla komponenter ska finnas i Components filen. CSS ska finnas i Styling samt JSON filen ska ligga i data filen. 


# Övning 3

Skapa nu två komponenter som heter Button och Card. 

 - Button ska vara en knapp som ska återanvändas överallt där knappar ska finnas. Den ska vara  generell och inte ha något hårdkodat i sig. 

 - Card ska vara en tabell som ska följande props: 
	 - En bild
	 - Name
	 - Popularity
	 - Action (En knapp med delete)

tips: Jobba med `<td>, <table>, <tr>, <th>`

# Övning 4

När komponenterna är färdiga är det nu dags att rendera ut dessa med dynamisk data. Ladda ner filen som heter `imdb.json` och lägg in den i data mappen. 

Rendera ut 5 objekt från filen. 


# Övning 5

Skapa tre nya knappar (återanvännd button komponenten) och döp dessa till **"Generate random actor",** **"Sort by name"** & **"Sort by populairty"**

# Övning 6

Skapa 3 nya funktioner 

 - **Generate random actor**
	 - Hämtar 5 nya objekt ifrån JSON listan
 - Sort by name
	 - Sorterar tabellen/listan på namn (A-Ö)
 -	Sort by populairty
	 -	Sorterar tabellen/listan på populiarty (1-100)


Tips: Jobba med states

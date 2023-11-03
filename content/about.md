---
Title: About
Description: This is our index page.
---

#Tekniker som används i portfolio

##Pico
Pico är själva ramverket som används här. Det innehåller många olika språk och tekniker. Tex används Markdown för att mata in text som denna. Fördelen som jag förstår det är att vi använder oss av meta information som bygger ett ramverk där informationen är uppdelad i olika delar tex är informationen/content i en mapp och style i en annan osv. Det blir väldigt enkelt att uppdatera olika delar på hela sidan, som att byta style genom att bara ändra på ett ställe för att ändra tema och hela sidans utseende.Nedan ser du lite kortare information om olika tekniker och språk på sidan

###Markdown
Jag vet inte riktigt hur jag ska beskriva markdown om det är ett språk eller en teknik eller sätt att skriva text som lätt går att översätta till HTML. Det gör att du får en tydlig bild av hur texten kommer se ut ungefär, direkt i din editor tex VS code, utan att behöva lägga till olika tags etc. Hur som helst är denna text skriven som markdown text.

###PHP
PHP är iaf ett programmerings språk. I Pico används PHP mest som jag förstår det för loopar och villkor på massa olika ställen. Detta behövs såklart för att ramverket ska fungera och va användarvänligt. Tex så blir det ju just PHP som används för att upptäcka när du gjort en ny sida (som den här about sidan). Så fort du ger den en title upptäcks den och bearbetas..typ.

###CSS
CSS använder vi oss av för att styla sidan såklart. till en början har vi "bara" CSS när Pico startar men i nuläget (kmom02) har vi även installerat ett till hjälpmedel, nästa punkt.

###SASS
Detta kurs momentet (kmom02) är det SASS vi tittar på. Det står för Syntactically Awesome Style Sheets. Det är om jag förstår rätt en teknik som utvecklar css till ett slags super css. Dom fördelar jag förstått hittils är väl att vi nu kan använda variabler, nestlade regler och olika slags import/mixin/extended. Variabler säger ju sig självt att det kan va användbart tex till färger eller font inställningar. Lättare att lägga in en och samma variablel på flera olika ställen än att kopiera hela tiden. Lättare att uppdatera oxå så klart. nästlade regler gör det ju mera likt HTML kodens classer och tags vilket gör det lite mer lätt begripligt oxå. import är ju bra så man kan dela upp sin style kod i olika filer men det har ju faktiskt css oxå. Däremot ska det bli intressant att förstå sig på vad mixin och extend kan hjälpa till med. Det hoppas jag att jag snart har förstått.

###Twig
Det här är en ny teknik för mej. Som jag förstår det är det en template engine till PHP..Kan det betyda att man skapar nån form av miljö där man laddar upp templates med hjälp av twig. Det jag förstått är att en variablel skrivs {{ variabelnamn }} och för loppar och liknande används {% kod %}. Känns ju väldigt användbart ihop med PHP loopar så att koden blir kort och liksom återanvänds eller vad man ska säga. Känns lite som stora delar av Pico bygger på att twig ihop med PHP skapar sidor ut efter det innehåll du ger i content mappen (lite förenklat kanske..).

###JavaScript Object Notation
Nu är jag ute på väldigt djupt vatten. Jag ser att Picos grund innehåller .json filer vilket jag tror är javascript filer. Dessa filer vet jag ingenting om än så länge mer än att dom behövs för att allt ska funka. Ska bli spännande längre fram när vi kan förstå oss på dom också.


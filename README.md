# Gulp and Git together - Start Template
A basic template, just to know how it works

## Automatisering
Automatiseringen syftar till att man som utvecklare kan granska sina ändringar i webbläsaren utan att man manuellt behöver uppdatera sidan. 

## Paket
1. **Concat** - används för att sammanföra filer i en src-katalog till en och samma fil i önskad pub-pubbliseringskatalog
2. **Imagemin** - används för att komprimera bilder - mindre filstorlek utan minskad kvalité 
3. **Uglify** - används för att komprimera (minify) javascriptsfiler - ta bort onödigt innehåll så som kommentarer och radbrytningar 
4. **Uglifycss** - används för att komprimera (minify) css-filer - ta bort onödigt innehåll så som kommentarer och radbrytningar 
5. **Sass** - används till att konvertera scss till css

## System
**CopyHtml** -används för att kopiera alla html-filer från src till publiseringsmappen
**Run**- används för att köra task
**Watch** - Används för att övervaka förändringar som görs i filerna och kör automatiskt vissa uppgifter

## Verktyg
#Att starta upp Automatisk uppdatering används kommandot gump
#Att avsluta Automatisk uppdatering används kommandot Ctrl + C

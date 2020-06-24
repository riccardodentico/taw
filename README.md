# PROGETTO DI TECNOLOGIE E APPLICAZIONI WEB - UNIVE 2018/19

Progetto per l'esame di tecnologie e applicazioni web di Riccardo Dentico e Marco Barnà.

La consegna del progetto si trova nel file: taw_2019_exam.pdf
La relazione del progetto si trova nel file: relazione.pdf


## DBMS E SERVER WEB

Il DBMS e il server web sono ospitati online su Heroku e Mongo Atlas, pertanto non è necessario farne partire l'esecuzione manualmente.


## PRIMA COSA DA FARE

Dopo essersi posizionati nella cartella "/ClientsApp/ionic-web-app", eseguire i comandi:
 - npm install
 - npm install -g ionic cordova electron 
 - ionic build


## CLIENT WEB

Per avviare l'applicazione web, dopo essersi posizionati nella cartella "/ClientsApp/ionic-web-app", eseguire il comando:
 - ionic serve



## APP MOBILE 

Per testare l'applicazione mobile con un emulatore, dopo essersi posizionati nella cartella "/ClientsApp/ionic-web-app", eseguire i comandi:
 - ionic cordova run android -l (per testare l'applicazione Android sull' emulatore di Android Studio)
 - ionic cordova build android (per testare l'applicazione sul proprio dispositivo Android, nell'output del terminale sarà indicata la locazione dell'apk)


## APP DESKTOP

Per eseguire l'applicazione desktop, dopo essersi posizionati nella cartella "/ClientsApp/ionic-web-app", eseguire il comando:
- npm run electron
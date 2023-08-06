# MyRealtime
Dies ist ein Android Programm (Android Studio) zum öffnen der PTB Uhr auf dem Handy oder Tablet. 
Dazu ist eine Internetverbindung notwendig.
Das Programm nutzt dazu WebView. Wenn keine Internetverbindung vorhanden ist, nutzt das Programm die Systemzeit
vom Gerät. Die Webseite vom Pysikalisch-Technischen Bundesanstalt in Braunschweig stellt eine exakte Uhrzeit zur
Verfügung. Die Differenz zwischen dem Androidgerät und der Realzeit (Delta T) kann dargestellt werden.

 ![Programm](https://github.com/DL1RLB/MyRealtime/assets/69315366/aa345883-64ba-4037-b58f-94b249ca79e2)
     
# Java
  - MainActivity (Startseite mit Kontextmenü)
    - WebView öffnet den Link
    - Check ob eine Internetverbindung vorhanden ist, mit dem ConnectionDetector und dann Aufrufen des Seite oder
    - mittels Intent die "NoInternet" Seite öffnen
    
  - ConnectionDetector (prüft ob eine Internetverbindung vorhanden ist)
    - ConnectivityManager aus dem Service gibt ein context zurück.
      
  - ActivityNoInternet (Seite die aufgerufen wird wenn keine Internet vorhanden ist, dann wird die Systemzeit vom Handy genutzt)
    - Alamrmeldung mit dem Hinweis dass kein Internet gefunden wurde und deshalb die Systemzeit vom Handy angezeigt wird.
    - Möglichkeit zur Infoseite zu gelangen.
      
  - ActivityInfo (Seite mit hilfreichen Informationen)
    - Allgemeine Informationen einer html-Seite aus dem Assets-Ordner.
   

# Hinweis
Alle Informationen sind aus dem Internet. Kein Anspruch auf Richtigkeit der Programmierung. 
Keine Veröffentlichung bei Google Play Store vorgesehen. Das Programm soll nur ein Beispiel der
Programmierung sein.
Keine weiteren Funktionen implementiert.

# Quelle
Die Uhr und weitere Informationen ist über dass Internet zu erreichen.
https://uhr.ptb.de/ 

Lutz

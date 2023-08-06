# MyRealtime
Die ist ein Android Programm (Android Studio) zum öffnen der PTB Uhr auf dem Handy oder Tablet. Dazu ist eine Internetverbindung notwendig.
Das Programm nutzt dazu WebView. Wenn keine Internetverbindung vorhanden ist, nutzt das Programm die Systemzeit
vom Gerät. Die Webseite vom Pysikalisch-Technischen Bundesanstalt in Braunschweig stellt eine exakte Uhrzeit zur
Verfügung. Die Differenz zwischen dem Androidgerät und der Realzeit (Delta T) kann dargestellt werden.

 ![Programm](https://github.com/DL1RLB/MyRealtime/assets/69315366/aa345883-64ba-4037-b58f-94b249ca79e2)
     
# Java
  - MainActivity (Startseite mit Kontextmenü)
  - ConnectionDetector (prüft ob eine Internetverbindung vorhanden ist)
  - ActivityNoInternet (Seite die aufgerufen wird wenn keine Internet vorhanden ist, dann wird die Systemzeit vom handy genutzt)
  - ActivityInfo (Seite mit hilfreichen Informationen)

# Hinweis
Alle Informationen sind aus dem Internet. Kein Anspruch auf Richtigkeit der Programmierung. 
Keine Veröffentlichung bei Google Play Store vorgesehen. Das Programm soll nur ein Beispiel der
Programmierung sein.
Keine weiteren Funktionen implementiert.

Lutz

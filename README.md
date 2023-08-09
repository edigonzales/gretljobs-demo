# gretljobs-demo

Demo-Repository für https://demo.gretl.app / https://sogis-gretlx-frontend-phs32.ondigitalocean.app/: GRETL-Jobs mit Github Actions.

Es kann eine XTF-Datei (Modell `SO_AFU_ABBAUSTELLEN_Publikation_20221103`, Daten: https://files.geo.so.ch/ch.so.afu.abbaustellen/aktuell/ch.so.afu.abbaustellen.xtf.zip) hochgeladen werden. Die Datei muss entzippt sein. Sie wird mit _ilivalidator_ geprüft, mit _ili2pg_ in die Datenbank importiert und wieder exportiert. Die Logfiles und die exportierte XTF-Datei können under den Github Actions Artefakten heruntergeladen werden.



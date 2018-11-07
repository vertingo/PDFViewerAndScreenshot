Système de capture d'écran + Visualisation d'un fichier PDF(Android)
Charge et visualise l'url du fichier en cliquant sur Afficher un Aperçu de votre fichier PDF !

<p align="center">
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="http://vertin-go.com/Fonctions_Annexes/annexes/pdt-page-de-telechargement/Notification/images/topsiteapp11.png" width="250" height="300"/></a>
</p>
Partager une capture d'écran via Gmail, SMS, Messenger etc...

<p align="center">
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="http://vertin-go.com/Fonctions_Annexes/annexes/pdt-page-de-telechargement/Notification/images/topsiteapp12.png" width="250" height="300"/></a>
</p>
  
Système de capture d'écran + Visualisation d'un fichier PDF(Android)

 <p align="center">  <a href="https://play.google.com/store/apps/details?id=com.vertin_go.topsiteapp&amp;rdid=com.vertin_go.topsiteapp" target="_blank"><img alt="" src="http://www.mycompanyadmin.com/imagesrte/d548982/appstore-icon-mobile-retina.png" width="200" height="147" /></a></p>
 
 <p align="center"> <a href="https://play.google.com/store/apps/details?id=com.vertin_go.topsiteapp&amp;rdid=com.vertin_go.topsiteapp"><img src="http://vertin-go.com/Fonctions_Annexes/annexes/pdt-page-de-telechargement/Notification/images/Demo_App_TopSite.gif" width="500" height="350"/></a></p>
 
  
Système de capture d'écran + Visualisation d'un fichier PDF(Android)
Au niveau programmation Java Android ajouter la ligne suivante dans votre build.gradle module : app 

```
compile 'es.voghdev.pdfviewpager:library:1.0.2' 
```

Ajouter également dans votre AndroidManifest: 

```
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" /> 
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" /> 
<uses-permission android:name="android.permission.INTERNET" /> 
```

Implémenter l'interface DownloadFile.Listener et View.OnClickListener dans l'activité RemotePDFActivity 

public class RemotePDFActivity extends BaseSampleActivity implements DownloadFile.Listener, View.OnClickListener{

```
Un petit coup de pouce suivez nous sur YouTube et Facebook!
[You Tube] ==> https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1
[Facebook] ==> https://www.facebook.com/vertingo/
```

<p align="center">
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://platform-media.herokuapp.com/assets/images/reseaux-sociaux/youtube2.png" width="400" height="250"/></a>
  <a href="https://www.facebook.com/vertingo/"><img src="https://platform-media.herokuapp.com/assets/images/reseaux-sociaux/rejoins_nous.png" width="400" height="250"/></a>
</p>



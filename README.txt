IHK Trainer Mobile v135 – Android-Projekt mit GitHub-Build

Dieses ZIP enthält:
- deine HTML-Simulation als app/src/main/assets/index.html
- ein Android-WebView-Projekt
- einen GitHub-Actions-Workflow, der automatisch eine APK baut

Wichtig:
In dieser Umgebung konnte ich keine fertige APK kompilieren.
Deshalb ist dies der schnellste direkte Weg zu einer APK ohne lokalen Android-Build.

So bekommst du die APK:
1. ZIP entpacken
2. den kompletten Ordner in ein neues GitHub-Repository hochladen
3. auf GitHub: Actions -> "Build Android APK" -> Run workflow
4. nach dem Build unter "Artifacts" die Datei IHK-Trainer-debug-apk herunterladen
5. darin liegt die fertige .apk

Lokaler Weg:
- Projekt in Android Studio öffnen
- Build -> Build APK(s)

Hinweise:
- Die HTML-Simulation wurde als index.html in die App-Assets eingebunden
- Paketname: com.ihktrainer.mobile
- App-Name: IHK Trainer Mobile

# Generelle Informationen

Falls Fragen aufkommen, welche kein anderer Coach beantworten kann, ist es möglich mich eventuell für kurze Fragen über Slack zu erreichen. Falls hier etwas fehlt gerne einen Pull Request aufmachen oder mir über Slack bescheid geben.

Slack Name: Henri Beck

## JavaScript Ressourcen

### Tutorials
 - [Code Academy](codeacademy.com)
   - Level: Fängt sehr einfach an!
   - Es gibt hier auch Wege die Aufgaben am Anfang welche doch sehr einfach sind zu überspringen. Bedeutet man kann auch in der Mitte anfangen oder gegebenfalls nur nochmal gewisse Sachen sich angucken.
   - [Introduction to JavaScript](https://www.codecademy.com/learn/introduction-to-javascript)
 - [javascript.info](https://javascript.info/)
   - Code Snippets und Erklärungen für bestimmte Sachen, wie z.B. Variablen, Funktionen oder Operatoren
   - Allerdings nur auf **English** verfügbar.

## React JS Resourcen

### Websites
 - [React JS](https://reactjs.org/docs/hello-world.html)
 
### Tutorials
 - [Build with React](http://buildwithreact.com/tutorial)
   - Level: Easy
 - [React JS Tutorial](https://reactjs.org/tutorial/tutorial.html)
   - Level: Indeterminate

### Demo Projekte
Alle Demo Projekte sind gut kommentiert und 'sollten' funktionieren.

 - Name + Nachname Beispiel: [codesandbox.io](https://codesandbox.io/s/pp9rqxy86m)
 - Zähler Beispiel: [codesandbox.io](https://codesandbox.io/s/l5rl2q53x9)
 - TodoList Beispiel: [codesandbox.io](https://codesandbox.io/s/wooolxx9rl)
 - Advanced TodoList Beispiel: [](https://codesandbox.io/s/q97m8ow4zj)
 - CSS mit React JS: [codesandbox.io](https://codesandbox.io/s/qqlqnjm5j6)

### Mit React JS lokal arbeiten

Um React JS lokal auf eurem Rechner zum laufen zu bringen braucht ich [Node JS](https://nodejs.org/de/).
Einfach die Installations Datei für Version 8 runterladen und ausführen.
Wenn ihr lokal mit React JS arbeiten wollt, würde ich euch empfehlen mit [VS Code](https://code.visualstudio.com/) zu arbeiten.

Dann müsst ihr die folgenden Befehle in eine Konsole eingeben
> Wer nicht weiß was eine Konsole ist, einfach mal Martin fragen oder einen Coach fragen

```sh
npm install -g npx

# Erstellen einer neuen React App
npx create-react-app my-cool-new-app

# Wechseln in den neue erstellten Ordner
cd ./my-cool-new-app

# Started des lokalen Servers
npm start
```

Dies sollte einen neuen Tab öffnen mit einem lokalen Development Server.

Zum beenden des Servers den Prozess in der Konsole mit `STRG+C` beenden.
Zum wieder starten des Servers in dem Order wieder `npm start` ausführen.

## LLM Apps erstellen...ohne OpenAI
Möchtest du LLM Apps bauen...aber ohne Abhängigkeiten von OpenAI? Nun, ich habe hier den Code für dich, mein Freund. In diesem Projekt zeige ich, wie man eine Langchain x Streamlit App mit GPT4All baut. Wir beginnen mit einer einfachen App und bauen dann einen Langchain PythonREPL Agenten auf.

## Sieh es live und in Aktion 📺
[![Tutorial](https://i.imgur.com/qBoUX8m.jpg)](https://youtu.be/5JpPo-NOq9s 'Tutorial')

# Start 🚀
1. Erstelle eine virtuelle Umgebung `python -m venv nonopenai`
2. Aktiviere sie:
   - Windows:`.\nonopenai\Scripts\activate`
   - Mac: `source nonopenai/bin/activate`
3. Installiere den GPT4All Installer mit GUI-basierten Installern
   - Windows: https://gpt4all.io/installers/gpt4all-installer-win64.exe 
   - Mac: https://gpt4all.io/installers/gpt4all-installer-darwin.dmg
   - Ubuntu: https://gpt4all.io/installers/gpt4all-installer-linux.run
4. Lade die benötigten LLM-Modelle herunter und notiere den Pfad, wo sie installiert sind
5. Klone dieses Repo `git clone https://github.com/nicknochnack/Nopenai`
6. Gehe in das Verzeichnis `cd NonOpenAI`
7. Installiere die benötigten Abhängigkeiten `pip install -r requirements.txt`
8. Aktualisiere den Pfad der Modelle in Zeile 9 von `app.py` und Zeile 5 von `app-chain.py`
9.  Starte die Python-Agent-App mit `streamlit run app.py` oder die Chain-App mit `streamlit run app-chain.py`
10. Kehre zu meinem YouTube-Kanal zurück und gib ein Like und abonniere 😉...nein, ernsthaft...bitte! lol
11. Die Vergleichs-App kann gestartet werden mit `streamlit run app-comparison.py`. Bevor du das machst, aktualisiere den Basis ggml-Download-Pfad in Zeile 16, z.B. `BASE_PATH = 'C:/Users/User/AppData/Local/nomic.ai/GPT4All/'` und den OpenAI API-Schlüssel in Zeile 18

# Weitere Referenzen 🔗
<p>-<a href="https://github.com/nomic-ai/gpt4all/tree/main">GPT4All Referenz
</a>: hauptsächlich verwendet, um zu ermitteln, wie die GPT4All-Bibliothek installiert und referenziert wird. Die Doco änderte sich häufig, zum Zeitpunkt der Programmierung war dies das aktuellste Beispiel, wie man es zum Laufen bringt.</p>

# Wer, Wann, Warum?
👨🏾‍💻 Autor: Nick Renotte <br />
📅 Version: 1.x<br />
📜 Lizenz: Dieses Projekt steht unter der MIT-Lizenz </br>

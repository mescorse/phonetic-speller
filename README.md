# Private Phonetic Speller

A compact, browser-based phonetic spelling tool with English and a selectable second language shown side by side. Text conversion runs locally in the browser; the page does not send entered text to a server.

## Automatic publication on Windows

1. Install [Git for Windows](https://git-scm.com/download/win) and [GitHub CLI](https://cli.github.com/) if they are not already installed.
2. Open a terminal and run `gh auth login` once to connect GitHub CLI to your GitHub account.
3. Extract this ZIP file.
4. In the extracted folder, run:

   ```powershell
   py -3 publish_phonetic_speller.py
   ```

The script creates a **public** repository named `phonetic-speller`, uploads `index.html`, and enables GitHub Pages. The hosted website will be at `https://YOUR_USERNAME.github.io/phonetic-speller/`.

## Privacy

The repository and website are public, but text entered into the tool is processed locally in the browser. The application does not upload the text entered by the user.

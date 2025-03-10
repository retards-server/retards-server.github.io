# **Setup**

## **Scaricare Prism**

Se non ce l'avete ancora, dovete scaricare Prism Launcher:

- Installate Prism da [qui](https://prismlauncher.org/download/).
- Apritelo e configurate le impostazioni come preferite.
- Quando vi chiede di collegare il vostro account:

=== "Avete pagato Minecraft?"
    Connettete il vostro account Microsoft.
=== "Volete craccare Minecraft?"
    - Non connettete nessun account Microsoft.
    - Finite la configurazione finché non si apre Prism, poi chiudetelo.
    - Aprite un terminale, inserite il seguente comando e premete invio:
    === "Linux"
        `echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "MSA"}],"formatVersion": 3}' > ~/.local/share/PrismLauncher/accounts.json`
    === "MacOS"
        `echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "MSA"}],"formatVersion": 3}' > ~/Library/Application\ Support/PrismLauncher/accounts.json`
    === "Windows"
        `echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "MSA"}],"formatVersion": 3} > %appdata%/PrismLauncher/accounts.json`
    - Riaprite Prism.
    - Cliccate su "Accounts" in alto a destra.
    - Cliccate su "Add offline"
    - Inserite l'username che preferite.
    - Salvatelo e cliccate "Set default".

- Cliccate su "Settings".
- Cliccate su "Java".
- Impostate "Maximum memory allocation" alla metà della RAM del vostro PC.

## **Scaricare il modpack**

Se avete Prism ma non avete ancora installato il modpack:

- Aprite Prism.
- Cliccate su "Add Instance" in alto a sinistra.
- Cliccate su "Import".
- Incollate il seguente link: `https://github.com/retards-server/modpack/releases/latest/download/RetardsServer.mrpack`.
- Aspettate che Prism scarichi il modpack.

## Aggiornare il modpack

Per aggiornare il modpack:

- Scaricate l'ultima versione da [qui](https://github.com/retards-server/modpack/releases/latest/download/RetardsServer.mrpack).
- Aprite Prism, cliccate sull'istanza, poi "Edit" -> "Version" -> "Select file"
- Cliccate sul modpack che avete appena scaricato.
- Aspettate che si aggiorni.

## Entrare nel Server

Per entrare nel Server:

- Assicuratevi di essere loggati nel vostro account su aternos.org.
- Andate su aternos.org/servers e accendete il Server.
- Aprite Minecraft e cliccate su "Multiplayer".
- Quando il Server è acceso, entrate.

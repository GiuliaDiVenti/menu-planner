# Menù della settimana

App web per pianificare pranzi e cene, con la proteina di ogni pasto a colpo d'occhio e le ricette salvate.
È una pagina statica (`index.html`): niente server, niente build.

## Pubblicarla su GitHub Pages

1. Su GitHub: **New repository**, nome per esempio `menu`, visibilità **Public**, crea.
2. **Add file → Upload files** e carica tutti i file di questa cartella (`index.html`, `manifest.json`, le tre icone `.png`). Poi **Commit changes**.
3. **Settings → Pages**: in *Build and deployment* scegli *Deploy from a branch*, branch `main`, cartella `/ (root)`, **Save**.
4. Dopo uno o due minuti la pagina è su `https://TUO-USERNAME.github.io/menu/`.

## Metterla sulla Home dell'iPhone

1. Apri il link su **Safari**.
2. Tocca Condividi → **Aggiungi alla schermata Home**.
3. Lascia attivo **Apri come app web** e tocca **Aggiungi**.

Fai questo prima di inserire i pasti: la app installata ha uno spazio dati suo, separato da Safari.

## I tuoi dati

- I pasti e le ricette restano **solo sul dispositivo** in cui li inserisci (nel browser). Non finiscono nella repo.
- In fondo alla pagina c'è **Esporta dati**, che scarica una copia di sicurezza in un file `.json`, e **Importa dati**, che la ripristina. Esporta ogni tanto, soprattutto prima di cambiare telefono o cancellare l'app.
- Se cancelli l'icona o svuoti i dati del sito, i dati si perdono.

## Modificare qualcosa

Cambia i file nella repo (o caricane di nuovi con lo stesso nome) e GitHub Pages si aggiorna da solo in pochi minuti. Se la app installata mostra ancora la versione vecchia, chiudila e riaprila.

Le categorie delle proteine sono nella lista `PROT` dentro `index.html`.

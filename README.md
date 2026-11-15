Nova Horizon

Un browser per Android che fa il browser, ma con dentro gli strumenti che di solito si cercano in dieci app diverse.

Nova Horizon è un browser basato sul motore WebView di Android. Non è una "WebView con una barra degli
indirizzi": sopra il motore c'è un livello di funzioni — blocco delle pubblicità, gestore di password cifrato,
lettura pulita, traduzione, download intelligenti, strumenti per i file APK, backup — costruito per essere
usato ogni giorno, non per fare numero nella lista delle funzionalità.

Versione: 5.38.0 (versionCode 5380)
Pacchetto: com.novahorizon.browser
APK: ~1,2 MB, firmato, installabile su Android 8.0 o superiore (minSdk 26)
Lingua dell'interfaccia: italiano
Prezzi: nessuno. Nessun abbonamento, nessun account, nessuna pubblicità.
Licenza: MPL-2.0
Indice

Perché esiste
Dati tecnici
Le 78 funzioni, una per una
Privacy: cosa esce dal dispositivo
Permessi richiesti, e perché
Sicurezza
Prestazioni e dimensione: numeri veri
Limiti noti
Installazione e aggiornamenti
Come è fatto dentro
Licenza e attribuzioni
Perché esiste

Un browser "leggero" di solito è solo una finestra sul web. Un browser "completo" pesa 80 MB e ti chiede un
account. Nova Horizon sta in mezzo, scegliendo una direzione precisa:

Il motore è quello di Android. Niente Chromium impacchettato, niente GeckoView: l'APK resta intorno
al megabyte e riceve gli aggiornamenti di sicurezza del motore insieme agli aggiornamenti di sistema.
Le funzioni servono a qualcosa. Ogni voce del menu apre qualcosa che si può fare davvero. Niente voci
segnaposto, niente pulsanti che portano a un "prossimamente".
Il dispositivo è tuo. Le regole di blocco sono già dentro il pacchetto, le password stanno in una cassa
cifrata con la chiave del telefono, i backup si cifrano prima di uscire. Non esiste un server Nova Horizon,
perché non esiste proprio.
Niente è nascosto. Il menu ha 78 voci, tutte visibili. Non ci sono "funzioni segrete" da scoprire.
Dati tecnici

Voce	Valore
Nome visualizzato	Nova Horizon
Pacchetto	com.novahorizon.browser
Versione	5.38.0 (codice 5380)
Motore	WebView di sistema (Chromium aggiornato con Android)
Linguaggio	Java 17
Android minimo	8.0 Oreo (minSdk 26)
Android di riferimento	15 (compileSdk / targetSdk 35)
Dimensione APK	1 259 272 byte (1,20 MiB)
Firma	v1 (JAR) + v2 + v3, chiave personale dell'autore
SHA-256 certificato firmatario	e18138ec2463599825a8edfa1c082a79fb28b8d657cc9c65d22c935c6fe5392b
Interfaccia	nativa Android (nessuna UI web), quattro varianti scelte dalle Impostazioni
Traduzioni pagina	10 lingue, motore Google (endpoint pubblico)
Lista di blocco	inclusa nell'APK, nessun aggiornamento remoto
Le 78 funzioni, una per una

Il menu è organizzato in otto categorie. Qui sotto ci sono tutte le voci, nell'ordine in cui le trovi.

1. Schede e navigazione (12)

Home — la pagina iniziale con ricerca, collegamenti rapidi, colori personalizzabili e il pulsante che
apre l'elenco completo delle funzioni.
Nuova scheda — apre una scheda vuota in primo piano.
Scheda senza cronologia — una scheda "usa e getta": quello che visiti non entra nella cronologia.
Mission Control — la vista d'insieme di tutte le schede aperte, con anteprima e chiusura rapida.
Organizza schede — raggruppa le schede per argomento, con nome e colore per ogni gruppo.
Consenti una finestra di accesso — sblocca temporaneamente una finestra di login (popup) per il sito
corrente, quando il blocco dei popup impedisce l'accesso.
Apri in browser esterno — passa l'indirizzo corrente a un'altra app.
Assistenza accesso Arena — percorso guidato per gli accessi che richiedono il ritorno all'app tramite
collegamento (OAuth), con i domini ammessi gestiti da una policy dedicata.
Diagnostica accesso — mostra perché un accesso non è andato a buon fine: cookie, popup, indirizzo di
ritorno, schema del collegamento.
Organizzazione — le impostazioni dei gruppi di schede: creazione, rinomina, colore.
Chiudi tutte le schede — con conferma, chiude tutto in un colpo.
Cerca tra le schede — filtro sul titolo e sull'indirizzo di tutte le schede aperte.
2. Preferiti e cronologia (8)

Aggiungi ai preferiti — salva la pagina con titolo e indirizzo.
Preferiti — elenco completo, con apertura ed eliminazione.
Cronologia — elenco per data, con cancellazione selettiva o totale.
Salva per dopo — mette la pagina in una lista di lettura.
Letture salvate — riapre le pagine messe da parte, anche il testo estratto.
Salva nella raccolta — archivia la pagina in una raccolta tematica ("Ricette", "Lavoro", …).
Raccolte — le raccolte con i rispettivi contenuti.
Salva pagina per dopo — la stessa lista di lettura, raggiungibile anche dal Centro browser.
3. Pagina e lettura (16)

Trova nella pagina — ricerca nel testo della pagina corrente.
Nova AI / strumenti pagina — strumenti che lavorano sul testo della pagina: riassunto, domande sul
contenuto, ricerca con fonti reali ("Gemini Search" usa i metadati restituiti e non inventa fonti). Si
configura con una chiave dell'utente, conservata cifrata nel Keystore: senza chiave la funzione non
invia nulla a nessuno, semplicemente non è disponibile.
Modalità lettura — estrae l'articolo, elimina menu, banner e pubblicità, e lo mostra pulito.
Velocità / interrompi lettura — la voce ad alta voce: sette velocità (da 0,5× a 3,0×) e il comando per
fermarla.
Traduci pagina — traduce il testo visibile nella lingua scelta, blocco per blocco, con la barra di
stato che dice cosa sta succedendo.
Richiedi sito desktop — cambia lo User-Agent per la pagina corrente e ricarica.
Salva pagina offline (.mht) — salva la pagina intera in un singolo file .mht, leggibile senza rete.
Zoom del testo — ingrandisce solo il testo, senza deformare il layout.
Sorgente HTML — mostra il codice della pagina, con copia e condivisione.
Nova Pro Suite — il pannello che raccoglie gli strumenti avanzati in un unico posto.
Bionic & Reader View — modalità di lettura con testo "bionico" (sillabe in grassetto), pensata per
leggere più velocemente.
Identità browser / User-Agent — sceglie con quale identità presentarsi ai siti.
Traduci e confronta — originale e traduzione affiancati, riga per riga.
Apri archivio — apre archivi compressi dall'archivio locale, in streaming, senza estrarre percorsi
controllati dall'archivio (difesa contro il path traversal).
Profilo di lettura — dimensione (da 15 a 24 pt), interlinea (1,2×–2,0×), tema chiaro / seppia /
scuro, carattere sans / serif.
Trova con contatore — ricerca nella pagina con il numero di occorrenze e i pulsanti avanti/indietro.
Aspetto dell'interfaccia

Ci sono quattro interfacce, si scelgono da Impostazioni → Interfaccia browser:

Nova rinnovata — hero compatto, una riga di scorciatoie circolari con l'icona vera del sito,
Download e Raccolte come pillole, schede recenti con miniatura, titolo, indirizzo e "quando".
Nova attuale — l'interfaccia a griglia con le card grandi.
Nova precedente e Classica precedente — le versioni storiche, intatte.
La scelta è una preferenza a sé: chi non la tocca resta esattamente dove era. In più, due rifiniture:

Trasparenza pulsanti UI (Impostazioni, ultima voce): spenta, 25%, 50%, 75%. Cambia solo l'opacità del
riempimento dei pulsanti — testo e icone restano pieni — e funziona con qualunque palette, comprese quelle
generate da Colori con AI.
Icona adattiva: sfondo e simbolo separati, icona rotonda dichiarata e icona a tema per Android 13+.
Lo stesso marchio compare nella Home accanto a "Il tuo spazio".
Icone dei siti nelle scorciatoie

Quando aggiungi una scorciatoia, il browser riconosce il sito e ne scarica l'icona dal sito stesso
(/favicon.ico, poi /apple-touch-icon.png), solo in HTTPS. L'icona viene conservata in una cache locale,
ridotta a 96 px, e rivalidata dopo trenta giorni. Finché non arriva — o se il sito non ne ha una — si vede
l'iniziale del sito, mai un cerchio vuoto. Nessun servizio esterno di favicon, nessun identificativo
inviato a terzi.

4. Download e file (6)

Centro download — tutti i download con stato, avanzamento e azioni (apri, condividi, elimina).
Installa APK / XAPK / APKS — installa pacchetti Android anche quando sono divisi in più parti: XAPK
(archivio con APK principale e pacchetti di risorse) e APKS (bundle diviso). Ogni componente viene
verificato prima di entrare nella sessione di installazione del sistema.
Apri PDF locale — apre un PDF già sul dispositivo.
Ispeziona APK — legge il manifesto di un APK senza installarlo: nome del pacchetto, versione,
permessi richiesti, SDK minimo. Serve a capire cosa c'è dentro un file prima di darlo in pasto al sistema.
Spazio e cache — quanto occupano cache, cookie e dati dei siti, con cancellazione selettiva.
Coda dei download — i download in attesa, con l'ordine e la possibilità di annullarli.
I download riconoscono oltre 130 tipi di file — non solo ZIP e PDF, ma anche .md, .html, .txt,
.csv, .json, .yaml, .sh, .css, .js, .epub, .svg, immagini, audio e video — e funzionano
anche quando il server non dichiara la dimensione o non risponde alla verifica preliminare: in quel caso il
file viene scaricato comunque, invece di essere rifiutato.

5. Condivisione e acquisizione (8)

Condividi pagina — invia titolo e indirizzo a qualsiasi app.
Condividi link pulito — rimuove i parametri di tracciamento (utm_*, fbclid, …) prima di condividere.
Stampa / Salva PDF — usa il servizio di stampa di Android: stampante o PDF.
Screenshot pagina — cattura la parte visibile, in un tocco.
Cattura pagina intera — cattura anche quello che sta sotto lo scorrimento.
QR del link — trasforma l'indirizzo corrente in un codice QR, per passarlo a un altro telefono.
Scansiona codice QR — legge un QR con la fotocamera e apre il link, chiedendo conferma prima.
Condividi Nova Horizon (APK) — passa il pacchetto del browser a chi vuoi, senza store.
6. Privacy e dati (19)

Privacy Shield — il pannello del blocco pubblicità: stato, elenco delle liste attive, conteggio degli
elementi bloccati su quella pagina e interruttore per disattivarlo sul singolo sito.
Profilo del sito — cosa ha salvato quel sito: cookie, spazio, permessi concessi.
Privacy della pagina — riepilogo di cosa può fare la pagina aperta adesso.
Nascondi elemento — scegli con un tocco un elemento della pagina e nascondilo in modo permanente su
quel sito; la regola resta salvata.
Ripristina elementi del sito — annulla tutte le regole di elementi nascosti per quel sito.
Sessione isolata sperimentale — una sessione separata, senza cookie né dati condivisi.
Gestore password — la cassa cifrata: credenziali per sito, generatore di password robuste, ricerca,
indice con icona a chiave e compilazione automatica su richiesta. Sblocco con credenziale del
dispositivo (Keystore) e password principale; esportazione cifrata o CSV solo su richiesta esplicita.
Gestisci dati siti — elimina dati, cookie e cache di un singolo sito.
Esporta backup JSON — salva preferiti, cronologia, impostazioni, raccolte, script e regole.
Ripristina backup JSON — rimette tutto a posto dopo un cambio di telefono.
Permessi dei siti — fotocamera, microfono e posizione, per sito, con tre valori: consenti,
blocca, chiedi. Il confronto è sull'host esatto.
Banner cookie — toglie di mezzo gli avvisi di consenso più diffusi (OneTrust, Didomi, Cookiebot,
Usercentrics, CMP…), quelli che coprono mezza pagina e bloccano lo scorrimento. Non decide nulla al posto
tuo: toccare il pulsante "accetta" è una funzione separata, spenta di default e da attivare esplicitamente.
Backup automatico — copie periodiche dei dati dell'app, da ripristinare in caso di problemi.
Sincronizzazione WebDAV — manda il backup su uno spazio personale (Nextcloud, ownCloud, box propri).
Solo HTTPS, e il file viene cifrato prima di partire.
Motore di rendering — la carta d'identità del motore: chi lo fornisce, che versione è, quanto è
aggiornato, con un avviso se è vecchio.
Pannello del sito — tutte le impostazioni di un singolo sito in una schermata.
Cancella all'uscita — alla chiusura cancella cookie, cache e cronologia.
Protezione fingerprinting — aggiunge un rumore minimo e stabile per ogni sessione quando un sito legge
i pixel del canvas: il tuo dispositivo smette di avere un'impronta unica, la pagina continua a funzionare.
Script e CSS per sito — il "Tampermonkey" integrato: JavaScript o CSS che vale solo sul dominio
scelto (o su tutti), importabile da file, spento finché non lo attivi tu. Vedi sotto.
Script e CSS per sito, in dettaglio

Le estensioni del Chrome Web Store non funzionano su WebView: il motore non espone le API chrome.*, non
esiste il concetto di pagina in background e i file .crx non si possono caricare. Questa funzione copre il
caso d'uso reale delle estensioni — "su questo sito voglio che sia così" — con regole di sicurezza proprie.

Si crea uno script con nome, dominio, tipo (JavaScript o CSS, si cambia con un tocco) e
codice, oppure lo si importa da un file (fino a 200 kB).
Il dominio vuoto significa "tutti i siti". youtube.com vale per m.youtube.com, ma non per
notyoutube.com: il confronto è di dominio, non di sottostringa.
Il CSS viene inserito come testo in un unico <style>: non può chiudere il proprio tag.
Il JavaScript viene eseguito a pagina caricata (DOMContentLoaded) dentro un try/catch: se lo script è
sbagliato, la pagina non si rompe.
L'iniezione parte all'inizio del caricamento e viene ripetuta a fine pagina, per i siti che riscrivono il
contenuto; se per quel sito non c'è nulla di attivo, il browser non fa niente.
Non scarica nulla da nessun server: il codice è quello che hai scritto tu, e cambia solo se lo cambi tu.
Limiti: 100 script, 200 kB ciascuno.
7. Media e aspetto (6)

Velocità audio / video — rallenta o accelera i media della pagina.
Tema browser e siti — chiaro o scuro, applicato anche alle pagine che non hanno un tema scuro.
Picture-in-Picture — il video in una finestrella sopra le altre app.
Filtro notturno ambra — riduce la componente blu, per leggere la sera.
Riproduzione in background — l'audio continua anche con l'app in secondo piano.
Barra dimensione testo — la stessa scala dello zoom testo, sempre a portata di pollice.
8. Impostazioni (3)

Impostazioni — il pannello completo.
Centro browser — il punto di raccolta: sicurezza e permessi del sito, DNS privato, aggiornamenti,
scorciatoie, dati e diagnostica.
Info su Nova Horizon Browser v… — versione, motore, licenze, attribuzioni delle liste di blocco.
Privacy: cosa esce dal dispositivo

Questa è la parte che conta, quindi è scritta come una tabella e senza giri di parole. Nessun server Nova
Horizon esiste: non c'è telemetria, non c'è analytics, non c'è crash reporting automatico.

Cosa	Esce dal dispositivo?	Dove va
Cronologia, preferiti, raccolte, letture	No	Memoria dell'app
Password salvate	No	Cassaforte cifrata, chiave nel Keystore di Android
Backup	Solo se lo chiedi tu	Tuo spazio WebDAV, cifrato prima di partire
Elenco degli host bloccati	No	Liste già dentro l'APK
Testo tradotto	Sì, quando premi "Traduci"	Endpoint pubblico di traduzione Google
Ricerca dalla barra indirizzi	Sì, è una ricerca	Il motore di ricerca scelto
Domande a Nova AI	Sì, solo se configuri una chiave	Il fornitore della chiave che scegli
Icone dei siti per le scorciatoie	Sì: una richiesta al sito, come per una pagina	Il sito stesso, solo HTTPS; nessun servizio terzo
Screenshot, PDF, file scaricati	No	Memoria del dispositivo
L'invio del testo da tradurre è l'unico traffico che non è "il sito che stai visitando": succede solo
quando chiedi una traduzione, e riguarda il testo della pagina che hai davanti. Se la cosa non ti va bene, la
funzione semplicemente non si usa.

Permessi richiesti, e perché

Permesso	Perché serve	Quando viene chiesto
INTERNET	Aprire i siti. È un browser.	All'installazione
ACCESS_NETWORK_STATE	Sapere se c'è rete prima di provare una sincronizzazione	All'installazione
WRITE_EXTERNAL_STORAGE	Salvare i download nella cartella Download (solo Android 8–9)	All'installazione
POST_NOTIFICATIONS	Mostrare il progresso dei download e la riproduzione in background	Android 13+, a runtime
CAMERA	Solo per "Scansiona codice QR"	A runtime, al primo uso
RECORD_AUDIO	Solo se un sito chiede il microfono e tu lo consenti	A runtime, al primo uso
ACCESS_FINE_LOCATION	Solo se un sito chiede la posizione e tu la consenti	A runtime, al primo uso
REQUEST_INSTALL_PACKAGES	Installare APK che hai scaricato tu	A runtime, alla prima installazione
Nessun permesso è "per il browser in generale": quelli sensibili sono chiesti quando servono davvero, e
restano governati dal pannello Permessi dei siti.

Sicurezza

Certificati: se un certificato non è valido, la connessione si ferma. Non esiste un pulsante "prosegui
comunque", per nessun sito, in nessuna condizione. Il messaggio spiega cosa non va, ma non offre scorciatoie.
Trasporto sicuro: gli indirizzi http:// vengono aggiornati a https:// prima del caricamento. Le
eccezioni (siti raggiungibili solo in chiaro) valgono per un singolo dominio, le scegli tu, e restano sul
dispositivo.
Password: cifratura AES-GCM con chiave custodita nel Keystore di Android; lo sblocco richiede anche la
password principale. L'esportazione è cifrata per impostazione predefinita.
Da dove arrivano i file: i download passano da un controllo di autorizzazione; i pacchetti APK vanno in
una sessione di installazione del sistema (nessuna installazione silenziosa); i componenti di un APKS
vengono verificati uno per uno prima di essere scritti.
Contenuti ostili: i file .zip e simili si leggono in streaming, senza estrarre percorsi decisi
dall'archivio. Le risposte HTTP parziali incoerenti vengono rifiutate, per non unire due versioni diverse
dello stesso file.
Fingerprint: rumore stabile per sessione sul canvas, attivo solo se lo accendi.
Prestazioni e dimensione: numeri veri

Misure fatte sull'APK 5.38.0, non stime.

APK: 1 259 272 byte (1,20 MiB), firma v1+v2+v3.
Liste di blocco: circa 74 000 righe di host, già compresse dentro l'APK. Occupano 452 kB nel pacchetto
(2,3 MB una volta decompresse): il blocco funziona senza rete e senza aggiornamenti remoti, che è il
motivo per cui stanno lì. Toglierle farebbe risparmiare poco e romperebbe la promessa "funziona offline".
Rendering: il motore è quello di sistema. Gli aggiornamenti di sicurezza del motore arrivano con gli
aggiornamenti di Android, senza che l'APK cresca di un byte.
Memoria: le schede inattive possono essere liberate dal sistema (onTrimMemory), senza mai toccare la
scheda che stai guardando né le finestre di accesso in corso.
Avvio e navigazione: le iniezioni cosmetiche avvengono una sola volta per sito e vengono ricordate; i
salvataggi della cronologia sono raggruppati; la pagina non mostra più il lampo bianco al cambio di sito.
Limiti noti

Scritti qui perché è meglio saperli prima.

Le estensioni del Chrome Web Store non funzionano. Non è una scelta: WebView non espone le API
necessarie. L'alternativa è "Script e CSS per sito".
La traduzione passa da un servizio esterno (endpoint pubblico Google) e copre dieci lingue. È veloce
e gratuita, ma non è un motore installato sul telefono.
Nessuna sincronizzazione tra dispositivi dei preferiti: c'è il backup JSON e c'è WebDAV per il backup,
non un account.
Nessun blocco a livello di rete: il blocco avviene dentro il browser, non in tutta l'app del telefono.
Il tema scuro applicato ai siti è una rielaborazione dei colori: su alcuni siti molto elaborati qualche
dettaglio può risultare meno contrastato.
Nessuna pubblicazione su Google Play. Il browser è distribuito come APK firmato direttamente
dall'autore.
Installazione e aggiornamenti

Scarica NovaHorizon-V5.38.0.apk.
Apri il file e consenti l'installazione da quella fonte, se Android lo chiede.
L'app si chiama Nova Horizon nel launcher.
Aggiornamenti in place: ogni versione è firmata con la stessa chiave e ha lo stesso nome di pacchetto,
quindi la nuova build si installa sopra la precedente — schede, preferiti, password e impostazioni
restano. Per lo stesso motivo, una build firmata con una chiave diversa non si può installare sopra questa.
L'aggiornamento automatico è possibile con Obtainium, che controlla una pagina di release e installa le
nuove versioni da solo.

Ogni rilascio è accompagnato dal suo SHA-256: puoi verificare il file scaricato prima di installarlo.
Questo README viene aggiornato a ogni versione, insieme al registro dei test.

Come è fatto dentro

Il progetto è un singolo modulo Android, senza librerie di terze parti nel percorso caldo.

93 classi Java, circa 8 000 righe, una sola Activity principale.
La logica delicata sta in classi pure, senza dipendenze da Android, e viene verificata da test JVM:
questo è il motivo per cui il blocco pubblicità, il matching degli script, la politica delle password e il
riconoscimento dei download si possono collaudare senza un telefono.
Nessuna UI web: menu, pannelli, dialoghi e avvisi sono nativi. Si comportano come il resto di Android,
funzionano con TalkBack, rispettano il tema di sistema e non hanno ritardi di caricamento.
R8 + shrinking attivi; le liste di blocco sono compresse e mai duplicate in memoria.
Ogni funzione nuova ha un test che la copre; prima di ogni rilascio la suite completa deve passare.
Licenza e attribuzioni

Il codice è distribuito con Mozilla Public License 2.0. Le liste di blocco incluse provengono da progetti
pubblici (anudeepND, Frogeye, hostsVN e altri) e mantengono le rispettive licenze: le attribuzioni complete
sono nella schermata Info dell'app e nei file LICENSE-*.txt del pacchetto.

Nova Horizon non è affiliato a Google, ad Android, a nessun produttore di telefoni né a nessuno dei progetti
le cui liste sono incluse.

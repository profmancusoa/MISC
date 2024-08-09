---
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://source.unsplash.com/collection/9Eq26n8TeCM/1920x1080
background: /media/cover.webp
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
#highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
aspectRatio: "16_/9"
routerMode: "hash"
download: false
materia: MISC
as: 2024/2025
version: "1.0.0"
---

<!-- https://www.linkedin.com/pulse/password-cracking-top-10-techniques-1c/?midToken=AQF9ctzuADu41Q&midSig=0PtFrOuAHwuGU1&trk=eml-email_series_follow_newsletter_01-newsletter_content_preview-0-headline_&trkEmail=eml-email_series_follow_newsletter_01-newsletter_content_preview-0-headline_-null-z7cm~llmfix15~b9-null-null&eid=z7cm-llmfix15-b9&otpToken=MTMwMzFhZTIxNjI2Y2ZjZWI1MjgwY2U4NDExZmUxYjY4ZmM2ZDM0MjlmYTQ4ZDYzNzBjZTA4NmI0ODVmNTZiMzg4YWJhNjlkNDVlM2U4ZDU3ZjBkMmQxODM2MmE5Mjk5MDZmMzU2NzBmNTQ3OTgsMSwx -->

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div class="pt-12">
  <span class="px-2 py-1">
    Premi spazio o <carbon:arrow-right class="inline"/> per la prossima slide
  </span>
</div>


---

# Disclaimer


<Banner padding=50px mt=60px>
  Queste slide hanno carattere PURAMENTE didattico.<br>
  Tutte le informazioni contenute hanno lo scopo di fornire agli studenti nozioni basilari che li aiutino ad essere maggiormente consapevoli nell'uso di strumenti e servizi informatici. <br>
  Qualsiasi uso diverso dalla didattica non è assolutamente supportato dal docente
</Banner>

---

&nbsp;

<img src="/media/pwd_21.jpg" width="800" style="margin:auto;position:relative; left: 0px; top: 0px;">


---

&nbsp;

<img src="/media/pwd_16.png" width="250" style="margin:auto;position:relative; left: -300px; top: -50px;">

<img src="/media/pwd_17.png" width="250" style="margin:auto;position:relative; left: 300px; top: -300px;">

<img src="/media/pwd_18.gif" width="250" style="margin:auto;position:relative; left: 0px; top: -200px;">

<img src="/media/pwd_19.png" width="150" style="margin:auto;position:relative; left: 0px; top: -700px;">

<img src="/media/pwd_20.png" width="200" style="margin:auto;position:relative; left: 300px; top: -650px;">

<img src="/media/pwd_21.png" width="200" style="margin:auto;position:relative; left: -300px; top: -830px;">

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- Fin dagli albori dell'informatica il metodo più utilizzato per proteggere l'accesso ad una risorsa informatica (account, sito web, web banking, ...) è l'uso di una coppia di credenziali come `username` e `password`
- Il sistema verifica l'identità del soggetto che vuole utilizzare un dato servizio richiedendo:
  - **username**: un nome univoco che identifica l'identità del soggetto (umano o altra macchina) che richiede l'accesso al servizio
  - **password**: un segreto solamente in possesso dello username che richiede l'accesso al sistema
   
<img src="/media/pwd_01.png" width="350" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- Le password, ancora oggi, rappresentano la prima linea di difesa contro gli attacchi informatici
- Dato il loro larghissimo uso, sono anche `uno degli anelli più deboli` della sicurezza informatica
-  Gli hacker (***Black Hat*** --> sottospecie: **Cracker**) utilizzano diverse tecniche per "scoprire" le password 
-  `Uno dei metodi migliori per proteggere le proprie password consiste nel comprendere i metodi di attacco` 
-  Nel seguito vederemo le dieci principali tecniche di cracking delle password utilizzate dagli cracker e fornirò suggerimenti su come prevenirle.

<img src="/media/pwd_02.png" width="650" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<Banner padding=30px>
Un <mark>white hat hacker</mark> è un esperto di reti, di programmazione, di sistemi e di sicurezza informatica in grado di introdursi in reti di computer al fine di aiutarne i proprietari a prendere coscienza di un problema di sicurezza nel rispetto quindi dell'etica degli hacker e si contrappone a chi viola illegalmente sistemi informatici, anche senza vantaggio personale.
</Banner>

<img src="/media/pwd_03.png" width="450" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<Banner padding=30px>
Un <mark>black hat hacker/cracker</mark> invece è un profilo decisamente più pericoloso e soprattutto dannoso. Il suo obiettivo infatti è violare illegalmente  l’integrità di un sistema informatico con l’intenzione di creare appositamente dei danni, spesso per trarre vantaggio personale. 
</Banner>

<img src="/media/pwd_04.png" width="350" style="margin:auto;position:relative; left: 0px; top: 20px;">


---

# Password Cracking


<Sticker tag=1 text="Brute Force Attack" />

- Un attacco a `forza bruta` è una tecnica comune di cracking delle password 
- Prevede di provare ogni possibile combinazione di caratteri finché non viene trovata la password corretta. 
- I cracker, utilizzano software specializzati (john the ripper, hashcat, ...) per automatizzare questo processo 
- Sono in grado di decifrare anche password complesse se hanno abbastanza tempo. 

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizza password lunghe, complesse,univoche con lettere maiuscole e minuscole, numeri e simboli 
2. Utilizza un password manager per memorizzare le tue password (<mark>se tu la ricordi, io la indovino</mark>)
3. Implementare policy relative alle password che richiedano agli utenti di modificare regolarmente le password e limitare il numero di tentativi di accesso non riusciti prima che l'account venga bloccato.

---

# Password Cracking

Brute Force

- Le password non vengono **MAI** memorizzate in chiaro
- Se un attaccante viene in possesso del DB delle password, e queste sono in chiaro allora avrà immediatamente accesso a tutte le password
- Normalmente viene memorizzato un `HASH` della password

<Banner padding=30px mt=60px>
Un hash di una password è una rappresentazione della password stessa che non può essere invertita, ma la password originale può comunque essere determinata se qualcuno calcola di nuovo l'hash e ottiene lo stesso risultato
</Banner>

---

# Password Cracking

Brute Force

<img src="/media/pwd_22.png" width="550" style="margin:auto;position:relative; left: 0px; top: 20px;">

---

# Password Cracking

Brute Force

<br><br>

```bash
$ cat /etc/shadow

jon:$6$3bp5ZebUAYQBcCbU$VY5uo1P4hP5janl4x/f13lRXvCRMMaZs0fXVrGQg7ynn8e6gaQFwP6XcXY6ju/06YQmQJEsP9n.pKzYjEvSNj0:19941:0:99999:7:::
cello:$6$JWZL3FOxOp4SBl2g$2qHOZcMZDjK4VX1flYqpDE4OXkJCxr6NKxikoxfZsRi/CT6h.SD7QPDZBVpmmKD/a33968VcHkcXIf2bhZ.cC/:19941:0:99999:7:::
rizzo:$6$kvocf79AFVHZPoSf$6OUtOTt/9a2Ef.t2Sl5aPltVsMEPevw6PqsPjojh4Ls6JKhcfbZwXub182T1JY4.hW2ZxjLpl9U0fyh6ViVYF1:19941:0:99999:7:::
nicolo:$6$ZAWnY8UDGAS1hZnr$bhPC803jdfz8hL6whh5m36p6msVhBb4VWE7Wqdy0nZqkfc91rfSJN7XWmU7icq17yrW85U9jLnAgn/GJLdbOg/:19941:0:99999:7:::
user5:$6$NPL8O/ZEQxQTT8OO$/fhde7.D/Q5JR4CJYI2h4rTY7IZeS0w4tsbAId5Cuv2TBd0IHSC5C2ZIyulqdIetCOcjYGJ2RIm2S/Hvffk/p1:19941:0:99999:7:::
user6:$6$PhYFY1AqXVT6Xeb4$8HOdLC55Jv0mVu40PHlF4tQFTpBs9SYS766N.1lwVAjTcgamRGg2hMnauOe5IYl83G5ZODYBwfb853n6rDFh60:19941:0:99999:7:::
```

---

# Password Cracking

Brute Force

Un attacco `brute force` prevede vari passi:

1. ottenere il DB delle hash delle password
2. identificare l'algoritmo di hashing utilizzato
3. per ogni passowrd fare un brute force ricalcolando la hash di tutte le combinazioni possibili di caratteri
4. quando la hash calcolata `COINCIDE` con quella nel DB abbiamo scoperto la password

<Banner padding=30px mt=20px>
Intuitivamente possiamo dire che la qualità di una password è direttamente proporzionale al numero di combinazioni che un attaccante deve provare nel brute force 
</Banner>


---

# Password Cracking

Brute Force

<br>

|Alfabeto|Len Alfabeto|Len Passws|# Combinazioni|Esempio (N = 8)|
|-|-|-|-|-|
|Numerico|10|N|10^N|10^8|
|Caratteri minuscoli|26|N|26^N|26^8 ~ 208 * 10^9|
|Caratteri maiuscoli|26|N|26^N|26^8 ~ 208 * 10^9|
|Simboli|32|N|32^N|32^8 ~ 1099 * 10^9|

---

# Password Cracking

Brute Force

<br>

|Alfabeto|Len Alfabeto|Len Passws|# Combinazioni|Esempio (N = 8)|
|-|-|-|-|-|
|Numerico + <br>minuscole|36|N|36^N|36^8 ~ 2821 * 10^9|
|Numerico + <br>minuscole + <br>MAIUSCOLE|62|N|62^N|62^8 ~ 218340 * 10^9|
|Numerico + <br>minuscole + <br>MAIUSCOLE + <br>simboli|94|N|94^N|94^8 ~ 6095689 * 10^9|


---

# Password Cracking

Brute Force

- Dalle tabelle precedenti risulta eviente che

<Banner padding=20px mt=10px>
  In prima approssimazione, la qualità di una password è determinata dalla sua lunghezza e dall'alfabeto utilizzato.<br><br>
</Banner>  
<Banner padding=40px mt=20px>
Una buona password utilizza cifre numeriche, caratteri minuscoli, maiuscoli e simboli ed ha una lunghezza tale che rende il brute forcing impraticabile (in termini di tempo o di costo)
</Banner>


---

# Password Cracking

Brute Force

<img src="/media/pwd_23.png" width="850" style="margin:auto;position:relative; left: 0px; top: -20px;">

- Quindi una RTX 4090 calcola circa 6,8 * 10^9 Hash al secondo

---

# Password Cracking

**Alfabeto: numerico**

<img src="/media/pwd_24.png" width="900" style="margin:auto;position:relative; left: 0px; top: 0px;">

---

# Password Cracking

**Alfabeto: numerico + minuscole**

<img src="/media/pwd_25.png" width="900" style="margin:auto;position:relative; left: 0px; top: 0px;">

---

# Password Cracking

**Alfabeto: numerico + minuscole + maiuscole**

<img src="/media/pwd_26.png" width="900" style="margin:auto;position:relative; left: 0px; top: 0px;">

---

# Password Cracking

**Alfabeto: numerico + minuscole + maiuscole + simboli**

<img src="/media/pwd_27.png" width="900" style="margin:auto;position:relative; left: 0px; top: 0px;">


---

# Password Cracking

Brute Force

- Quindi la nostra scelta dell'alfabeto e della lunghezza della password è fondamentale per contrastare attacchi di tipo brute force
- Tuttavia c'è un'aspetto che non dipende da noi
  - La "potenza di fuoco" dell'attaccante
  - Sono noti **hashing rig** da 60 GPU
  - Probabilmente le istituzioni governative (NSA?) hanno decine o centinaia di questi rig

<Banner padding=30px mt=20px>
Pertanto la "qualità" della  nostra password dipende da noi e da quanto è intenzionato il nostro attaccante a scoprire la nostra password
<br>Quindi considerazioni e policy differenti possono essere adottate per uso personale, per uso aziendale e per uso pubblico
</Banner>


---

# Password Cracking

pwgen e keepassx

- Quindi come visto è necessario generare e usare password che sono lunghe e molto difficili da ricordare
- Quindi è importante utilizzare gli strumenti giusti (NO ONLINE TOOLS)

**GENERARE PASSWORD**

- Uno strumento utilissimo è `pwgen`

```bash
$ pwgen -c -n -y -s 20 1

kj}B(Hr/f}Z()mu]M3*.
```
<br>

- Genera una password:
  - lunga 20 caratteri
  - generata casualmente (-s)
  - che contiene almeno una lettera maiuscola (-c)
  - almeno una cifra (-n)
  - almeno un simbolo (-y)

---

# Password Cracking

pwgen e keepassx

**MEMORIZZARE PASSWORD**

<Banner padding=20px>
  Se tu la ricordi, io la indovino!!!
</Banner>

<br>

- Quindi è necessario uno strumento chiamato `password manager` per tenere traccia in modo sicuro di tutte le nostre password

[KeepassX](https://www.keepassx.org)

<img src="/media/pwd_28.png" width="600" style="margin:auto;position:relative; left: 0px; top: -30px;">

---

# Password Cracking

<Sticker tag=2 text="Dictionary Attack" />

- Un attacco a `dizionario` è simile a un attacco a forza bruta ma utilizza un elenco di parole da un dizionario o password di uso comune per decifrare le password. 
- Gli hacker utilizzano software in grado di provare migliaia di parole al secondo finché non viene trovata la password corretta.
- Ci sono [dizionari](https://github.com/kkrypt0nn/wordlists?tab=readme-ov-file) con milioni di parole (es: rockyou ha circa 14 Milioni di parole)

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Evitare di utilizzare parole, frasi o password comuni facili da indovinare. 
2. Utilizza invece una combinazione di caratteri casuali e non utilizzare la stessa password su più account.
3. Non usare dati personali all'interno della password (data di nascita, nome, sopranome, scuadra del cuore...)
  
---

# Password Cracking

<Sticker tag=3 text="Rainbow Table Attack" />

- Un attacco `Rainbow Table` è un attacco simile al tipo brute force
- Tuttavia anziché calcolare a run-time l'hash di ogni password , utilizza una tabella pre-calcolata di hash 
- Gli hacker creano una tabella di password comuni e dei relativi hash corrispondenti
- Quindi confrontano gli hash della password di destinazione con la tabella per trovare una corrispondenza.
- In questo modo, in alcuni scenari, si può decifrare una password molto più velocemente rispetto ad un attacco brute force
- Ci sono [rainbowtable](https://freerainbowtables.com) da oltre 1000 GB 
 
<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizza un algoritmo di hashing potente come bcrypt o scrypt
2. Aggiungi un `salt` univoco a ciascuna password prima di sottoporla ad hashing. 
3. Questo espande il set dei possibili valori, rendendo molto più lento l'attacco a forza bruta e inutile quello basato su rainbow table

---

# Password Cracking

<br>

```bash
Start Point         | End Point
--------------------------------
abc                 | CLticu7pz8PPQGtfIZw731
bcd                 | hsPCcJGhVOjLN1vjzj0m80
...
xyz                 | V4OAyKi4r.e9FcRAyXdyF/

```

<br>

- In questo modo anzichè calcolare l'hash per ogni combinazione (brute force) cerco l'hash che voglio cracckare nella tabelle
- Se trovo una corrispondenza nella colonna di sinistra leggo la password in chiaro


---

# Password Cracking

- Calcoliamo l'hash MD5 di una passowrd

```bash
$ openssl passwd -1 -salt aaaa abc
$1$aaaa$CLticu7pz8PPQGtfIZw731

$openssl passwd -1 -salt aaaa bcd
$1$aaaa$hsPCcJGhVOjLN1vjzj0m80

$openssl passwd -1 -salt aaaa xyz
$1$aaaa$V4OAyKi4r.e9FcRAyXdyF/
```
<br>

- Il "salt" è un valore casuale che viene aggiunto a una password prima che venga hashata. 
- I suoi scopi principali sono:
  - Prevenzione degli Attacchi con Rainbow Table
  - Diversificazione degli Hash
  - Prevenzione degli Attacchi su Password Riutilizzate


---

# Password Cracking

- Infatti se ricalcoliamo l'hash md5 con un salt diverso otteniamo risultati completamente diversi

```bash
$ openssl passwd -1 -salt aaab abc
$1$aaab$kYi6JKZzw7c.ExaKTjviv1

$ openssl passwd -1 -salt aaab bcd
$1$aaab$GaFNveL0I6uMiWCdiiTuI0

$ openssl passwd -1 -salt aaab xyz
$1$aaab$ZputqBz/cOvuwxEsj5noG1
```

<br>

- Quindi una tabella di hash è calcolata senza salt o per un solo salt
- Se quindi il nostro sistema esegui l'hashing delle password con un salt casuale
- Sarà necessario calcolare N hashtable 
- Linux usa un salt da 16 caratteri 
- Quindi è necessario calcolare 62^16 hashtable
- Essendo ciò impraticabile rende l'attacco rainbow table inefficace e viene neutralizzato


---

# Password Cracking

<Sticker tag=4 text="Social Engineering Attack" />

- L'ingegneria sociale è una tecnica che prevede la manipolazione delle persone per indurle a rivelare le loro password o altre informazioni sensibili. 
- Kevin Mitnick  (*the condor*) è stato il più famoso hacker della storia a sfruttare l'ingegneria sociale 
- Gli hacker possono impersonare una persona fidata, inviare e-mail di phishing o utilizzare altre tattiche per indurre gli utenti a rivelare le proprie password

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Informare gli utenti sui rischi legati alla condivisione di password e informazioni sensibili per prevenire attacchi di ingegneria sociale. 
2. Utilizza l'autenticazione a due fattori (2FA) per aggiungere un ulteriore livello di sicurezza 
3. Verificare l'identità di chiunque richieda informazioni sensibili
4. Non condividere informazioni personali anche se apparentemente innocue

---

# Password Cracking

2FA

<Banner padding=20px >
La 2FA, o autenticazione a due fattori (Two-Factor Authentication), è un metodo di sicurezza che richiede due forme di verifica per confermare l'identità di un utente
<br><br>Questo approccio aggiunge un livello di protezione supplementare rispetto all'uso di una sola password
</Banner>

<br>

La 2FA combina due di questi tre fattori:
- **Qualcosa che sai**: Una password o un PIN.
- **Qualcosa che hai**: Un dispositivo fisico come uno smartphone, un token hardware o una smart card.
- **Qualcosa che sei**: Un fattore biometrico come un'impronta digitale, il riconoscimento facciale o la scansione dell'iride.


<img src="/media/pwd_33.png" width="250" style="margin:auto;position:relative; left: 0px; top: -30px;">

---

# Password Cracking

2FA

**Come Funziona la 2FA**

Ecco un esempio comune di come funziona la 2FA:

- **Inserimento della Password:** L'utente inserisce la propria password per accedere a un servizio online.
- **Secondo Fattore di Autenticazione:** Dopo aver inserito la password corretta, viene richiesto di fornire un secondo fattore di autenticazione. Questo può essere un codice generato da un'app di autenticazione sullo smartphone, un codice inviato via SMS, un token generato da un dispositivo hardware, o una scansione biometrica.

---

# Password Cracking

2FA

**Tipi Comuni di 2FA**

- **App di Autenticazione:** App come Google Authenticator, Authy o Microsoft Authenticator generano codici temporanei a intervalli regolari.
- **Codici via SMS:** Un codice di verifica viene inviato al numero di telefono registrato dell'utente.
- **Token Hardware:** Dispositivi fisici come YubiKey generano codici di accesso unici.
- **Autenticazione Biomentrica:** L'uso di impronte digitali, riconoscimento facciale o scansione dell'iride per verificare l'identità dell'utente.

---

# Password Cracking

2FA

**Vantaggi della 2FA**

- **Maggior Sicurezza:** Anche se la password viene compromessa, l'attaccante non può accedere all'account senza il secondo fattore di autenticazione.
- **Protezione contro Phishing e Keylogger:** Gli attacchi che riescono a ottenere le password non sono sufficienti da soli per accedere agli account protetti da 2FA.


**Conclusione**

<Banner padding=25px>
La 2FA è una misura di sicurezza semplice ma molto efficace che protegge gli account online da accessi non autorizzati. 
<br>Implementando la 2FA, gli utenti possono proteggere meglio i propri dati personali e professionali, riducendo il rischio di compromissioni di sicurezza.
</Banner>
---

# Password Cracking

<Sticker tag=5 text="Shoulder Surfing Attack" />

- Il `shoulder Surfing` è un attacco fisico che prevede l'osservazione di qualcuno che inserisce le proprie credenziali in un sistema (propria password su un computer o dispositivo mobile, pin del bancomat, ...)
- Gli hacker possono guardare oltre le spalle di qualcuno in un luogo pubblico
- Oppure possono installare una telecamera nascosta per catturare le password. 
- Ci sono parecchi casi di cronaca che riportano questo tipo di attacco presso i bancomat pubblici

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Fare attenzione a chi e cosa ti circonda quando inserisci le password/pin 
2. Se possibile evitare di inserirle in luoghi pubblici
3. Cercare di coprire fisicamente l'inserimento delle credenziali in modo da rendere inefficace il *shoulder surfing*

---

# Password Cracking

shoulder Surfing

<img src="/media/pwd_29.jpg" width="300" style="margin:auto;position:relative; left: 250px; top: 0px;">

<img src="/media/pwd_30.jpg" width="450" style="margin:auto;position:relative; left: -200px; top: -200px;">

<img src="/media/pwd_31.png" width="250" style="margin:auto;position:relative; left: 0px; top: -150px;">




---

# Password Cracking

<Sticker tag=6 text="Phishing Attack" />

- Il phishing (*da fishing, cioè pescare*) è una tecnica che prevede l'invio di e-mail o messaggi che sembrano provenire da una fonte legittima 
- Lo scopo è indurre gli utenti a rivelare le proprie password o altre informazioni sensibili pensando di condividerle con una destinazione fidata (banca, scuola, compagnia telefonica,...)  
- Gli hacker utilizzano tattiche di ingegneria sociale e un linguaggio persuasivo per convincere gli utenti a fare clic su link o aprire allegati che installano malware o rubano dati. 

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Prestare attenzione quando si aprono e-mail o messaggi provenienti da fonti sconosciute
2. Cercare segni di phishing, come errori di ortografia, link e documenti sospetti
3. Utilizzare filtri anti-spam 
4. Dove possibile abilitare l'autenticazione a più fattori (MFA) per impedire tentativi di accesso non autorizzato

---

# Password Cracking

<img src="/media/pwd_32.png" width="400" style="margin:auto;position:relative; left: 0px; top: 0px;">

---

# Password Cracking

<Sticker tag=7 text="Key Logger Attack" />

- Questo attacco, spesso condotto tramite altri tipi di attacchi, prevede la registrazione delle sequenze di tasti che l'utente digita sul proprio dispositivo (comprese le password e i pin di sicurezza) 
- Gli hacker possono installare malware o utilizzare dispositivi fisici per acquisire sequenze di tasti e rubare password. 

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizzare un software antivirus aggiornati
2. Evitare di fare clic su collegamenti sospetti e di scaricare software da fonti non attendibili (*nulla è gratis*)
3. Utilizzare un gestore di password basato su hardware per archiviare le password.

---

# Password Cracking

Key Logger

<Banner padding=25px>
Un keylogger è un tipo di software o hardware che registra le sequenze di tasti premuti su una tastiera, spesso senza che l'utente sia a conoscenza di questa attività. <br><br>I keylogger sono strumenti potenti che possono essere utilizzati sia per scopi legittimi che per attività malevole.
</Banner>

---

# Password Cracking

Key Logger

**Tipi di Keylogger**

- **Keylogger Software:** Programmi che registrano i tasti premuti e memorizzano queste informazioni in un file di log, che può essere successivamente recuperato dall'attaccante. Possono essere installati su un computer tramite malware, download di software infetti o vulnerabilità di sicurezza.
- **Keylogger Hardware:** Dispositivi fisici che si collegano tra la tastiera e il computer, registrando le sequenze di tasti premuti. Questi dispositivi possono essere difficili da rilevare senza un'ispezione fisica del computer.

<img src="/media/pwd_34.png" width="300" style="margin:auto;position:relative; left: -300px; top: 20px;">

<img src="/media/pwd_35.png" width="300" style="margin:auto;position:relative; left: 300px; top: -180px;">

---

# Password Cracking

Key Logger

**Scopi e Utilizzi**

**Utilizzi Legittimi**

- **Monitoraggio dei Dipendenti:** Alcuni datori di lavoro utilizzano keylogger per monitorare l'uso delle tastiere dei dipendenti, con l'obiettivo di garantire la produttività o per motivi di sicurezza.
- **Controllo Parentale:** I genitori possono utilizzare keylogger per monitorare le attività online dei propri figli e proteggere loro da contenuti inappropriati.

**Utilizzi Malevoli**

- **Furto di Identità:** Gli attaccanti utilizzano keylogger per rubare informazioni personali come credenziali di accesso, numeri di carte di credito, e altre informazioni sensibili.
- **Spionaggio:** Keylogger possono essere utilizzati per spiare utenti specifici, raccogliendo informazioni sensibili o segreti aziendali.

---

# Password Cracking

Key Logger

**Conclusione**

<Banner padding=25px>
I keylogger possono rappresentare una grave minaccia alla sicurezza e alla privacy. <br>È importante essere consapevoli dei rischi associati e adottare misure preventive per proteggere le informazioni sensibili. <br>Utilizzare software di sicurezza aggiornato e monitorare attentamente l'attività del sistema sono passi fondamentali per proteggersi da questa minaccia.
</Banner>

<Banner padding=20px mt=20px>
Ricorda: NULLA E' GRATUITO!!!<br>
<br>Nemmeno il crack del gioco o dell'applicazione XYZ
</Banner>

---

# Password Cracking

<Sticker tag=8 text="Malware Attack" />

- Il malware è un tipo di software progettato per danneggiare o ottenere l'accesso non autorizzato a un computer o a una rete. 
- Il malware può essere utilizzato per rubare password, acquisire sequenze di tasti ed eseguire altri attacchi. 
- Spesso si nasconde in software a basso costo, freeware o peggio ancora cracckato
- Spesso il cracker di un gioco è un Malware

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Mantenere aggiornati l'antivirus e il sistema operativo
2. Installare le patch e gli aggiornamenti di sicurezza più recenti 
3. Evitare di fare clic su collegamenti sospetti o di scaricare software da fonti non attendibili e diffidare delle e-mail o dei messaggi con allegati.
4. Non installare software che apparentemente è gratuito o craccato

---

# Password Cracking

<Sticker tag=9 text="Man-in-the-Middle (MITM) Attack" />

- Un attacco `man-in-the-middle` (**MITM**) avviene quando un hacker intercetta le comunicazioni tra due parti per rubare informazioni sensibili, comprese le password. 
- Gli hacker utilizzano software o dispositivi fisici per intercettare le comunicazioni e acquisire password. 

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizzare canali di comunicazione sicuri, come HTTPS o una rete privata virtuale (VPN)
2. Diffida di siti critici basati su HTTP quando si accede a informazioni sensibili o si accede ad account. 
3. Inoltre, verificare l'identità del sito Web o del servizio a cui stai accedendo e fai attenzione alle reti Wi-Fi pubbliche o non protette.
4. Verificare il certificato SSL per accertarsi che sia rilasciato da una CA sicura

---

# Password Cracking

<Sticker tag=10 text="Password Reuse Attack" />

- Il riutilizzo della password è una pratica comune tra gli utenti e rappresenta un rischio significativo per la sicurezza. 
- Gli hacker possono utilizzare le password rubate da un account per accedere ad altri servizi se la stessa password viene riutilizzata. 

<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizzare una password univoca per ciascun account e servizio che si usa
2. Utilizzare un password manager sicuro off-line
3. Implementare l'autenticazione a più fattori (MFA) su tutti gli account per aggiungere un ulteriore livello di sicurezza e monitora regolarmente i tuoi account per attività sospette.

---

# Password Cracking

&nbsp;

**CONCLUSIONE**

- Le password sono ancora oggi elemento fondamentale per la protezione dell'accesso di risorse digitali e non
- Conoscere le principlai tecniche di cracking ci aiuta a comprendere che la scelta e la gestione di una password non è una cosa da prendere a "cuor leggero"
- Pertanto scegliamo password lunghe e complesse
- Utilizziamo un password manager `se tu le ricordi, io le indovino!!!`
- Dove possibile abilitiamo l'autenticazione 2FA (o MFA)
- Tenere la propria password privata e non condividerla con nessuno
- Non usare la stessa password per più account
- Aggiorna la passowrd almeno 2 volte all'anno

---

# Password Cracking

Esercitazione 01

- Ci sono molti strumenti a disposizione per il cracking delle password
- Come sempre lo strumento in se non è malevolo, ma può esserlo l'uso che se ne fa
- Un White Hat Hacker usa questi strumenti per verificare se le password di un sistema sono sicure e per scoprire eventuali criticità
- Un Black Hat Cracker usa questi strumenti per un vantaggio personale

- Tra i più utilizzati in ambito open troviamo:
  - Hashcat
  - JtR (John The Ripper)
  - Hydra
  - AirCrack-NG
  - ...


---

# Password Cracking

Esercitazione 01

- Questi tool sono molto potenti e di conseguenza anche complessi da utilizzare (almeno nelle loro forme più avanzate)
- Ci sono oltre 200 algoritmi di hashing
- Ci sono vari tipi di attacchi 
- Supportano CPU e GPU per "macinare" più hash possibili al secondo
- Possono essere distribuiti in cluster
- Tuttavia con un pò di pazienza si possono ottenere ottimi risultati

---

# Password Cracking

Esercitazione 01

- Nell'esercitazione useremo il famoso `John The Ripper` [official website](https://www.openwall.com/john/)

<br>

> John the Ripper è un software open-source progettato per effettuare il cracking delle password. È uno strumento molto utilizzato dagli amministratori di sistema e dai professionisti della sicurezza informatica per testare la robustezza delle password all'interno di un sistema. L'obiettivo principale di John the Ripper è quello di individuare password deboli, facili da indovinare o vulnerabili a determinati tipi di attacchi.

<br>

<Banner padding=30px mt=20px>
Essendo un tool potente, è ampiamente utilizzato sia in ambito legale per test di sicurezza (penetration testing), sia in contesti meno legittimi. È importante ricordare che l'uso di John the Ripper, o di altri strumenti simili, senza autorizzazione è illegale e può comportare conseguenze legali.
</Banner>

---

# Password Cracking

Esercitazione 01


**John the Ripper** supporta diversi tipi di attacco per il cracking delle password:

### 1. Attacco a dizionario (Dictionary Attack)
- Questo è il metodo più semplice e comune, dove John the Ripper utilizza un elenco predefinito di parole, noto come "dizionario", per tentare di indovinare la password. 
- Questo attacco è efficace contro password deboli che si trovano facilmente in liste comuni.

<br>

### 2. Attacco di forza bruta (Brute-Force Attack)
- In un attacco di forza bruta, John the Ripper prova tutte le possibili combinazioni di caratteri fino a trovare la password corretta. 
- Questo metodo è molto efficace, ma può richiedere molto tempo, specialmente per password lunghe o complesse.

---

# Password Cracking

Esercitazione 01

### 3. Attacco ibrido (Hybrid Attack)
- L'attacco ibrido combina l'attacco a dizionario con un attacco di forza bruta. 
- In pratica, John the Ripper prende una parola dal dizionario e poi la modifica leggermente aggiungendo numeri, caratteri speciali o cambiando la capitalizzazione per cercare di indovinare la password.

<br>

### 4. Attacco Rainbow Table
- Anche se John the Ripper non include nativamente le rainbow tables, può essere utilizzato in combinazione con esse. 
- Le rainbow tables sono tabelle precompute di hash, che consentono di risolvere gli hash di password in tempi molto più rapidi rispetto a un attacco brute-force tradizionale.

---

# Password Cracking

Esercitazione 01

### 5. Attacco basato su regole (Rule-based Attack)
- Questo metodo consente di applicare regole specifiche per modificare le parole del dizionario. 
- Ad esempio, può aggiungere numeri alla fine, sostituire lettere con numeri simili (come "e" con "3"), o combinare più parole. 
- È una forma avanzata di attacco ibrido.

<br>

### 6. Attacco incrementale (Incremental Mode)
- Questa modalità è una forma avanzata di brute-force che inizia con tentativi più semplici e continua a incrementare la complessità della password fino a trovarla. 
- Viene utilizzata per provare combinazioni che potrebbero non essere coperte da un dizionario standard.


---

# Password Cracking

Esercitazione 01

### 7. Attacco a sezioni (Section Attack)
- In questa modalità, John the Ripper divide l’attacco in sezioni, provando a crackare la password con una strategia specifica per ogni sezione. 
- È utile per password che seguono schemi riconoscibili, come prefissi o suffissi fissi.

<br>

### 8. Attacco di derivazione delle chiavi (Key Derivation Function Attack)
- John the Ripper supporta anche attacchi su password protette con funzioni di derivazione delle chiavi, come PBKDF2, bcrypt, scrypt, e altre. 
- Le KDF sono progettate per essere "lente" dal punto di vista computazionale, cioè richiedono più tempo e risorse per generare un hash rispetto agli algoritmi di hashing tradizionali come MD5 o SHA-1. 
- Questo rallentamento è intenzionale: rende il brute-force molto meno efficiente, perché ogni tentativo richiede molto più tempo rispetto a un algoritmo di hashing più veloce.


---

# Password Cracking

Esercitazione 01

- Vediamo come usare John The Ripper per effettuare un attacco a dizionario per scoprire la password di un file ZIP e di un file PDF.
- Per semplificare l'esercitazione utilizziamo un container docker appositamente preparato dal docente
- Segui tutte i passi in modo corretto in modo da scoprire le password

<img src="/media/pwd_36.png" width="350" style="margin:auto;position:relative; left: 0px; top: 30px;">

---

# Password Cracking

Esercitazione 01


`Verifica della presenza di Docker`

```bash
$ docker run -ti --rm hello-world

Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
c1ec31eb5944: Pull complete 
Digest: sha256:1408fec50309afee38f3535383f5b09419e6dc0925bc69891e79d84cc4cdcec6
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.
```

---

# Password Cracking

Esercitazione 01

`Installazione di John The Ripper`

```bash
$ docker pull profmancusoa/password-cracking:latest

latest: Pulling from profmancusoa/password-cracking
5de87e84afee: Pull complete 
8464f1dfa665: Pull complete 
Digest: sha256:5832b9c8943d49912a4ee45d1bc3b46c291a16ed901486244fe9dff481f36c7b
Status: Downloaded newer image for profmancusoa/password-cracking:latest
docker.io/profmancusoa/password-cracking:latest
```

<br>

`Verifichiamo la presenza dell'immagine`

```bash
$ docker image ls

REPOSITORY                       TAG           IMAGE ID       CREATED         SIZE
profmancusoa/password-cracking   latest        6335b156d8e5   16 hours ago    368MB
```

---

# Password Cracking

Esercitazione 01

`Lanciamo il container`

```bash
$ docker run -ti --rm profmancusoa/password-cracking

root@bb76266f0c89:~# 
```

- Ok ora siamo dentro il container con John The Ripper

`Vediamo cosa troviamo`

```bash
$ ls -la

total 36
drwx------ 1 root root 4096 Aug  8 18:10 .
drwxr-xr-x 1 root root 4096 Aug  9 10:10 ..
-rw-r--r-- 1 root root  789 Aug  8 18:07 .bashrc
-rw-r--r-- 1 root root  161 Jul  9  2019 .profile
-rw-r--r-- 1 root root 7470 Aug  8 18:10 secret.pdf
-rw-r--r-- 1 root root  223 Aug  8 18:10 secret.zip
```

---

# Password Cracking

Esercitazione 01

- Bene ci sono un file .zip ed un PDF con un nome intrigante
- Siccome siamo curiosi proviamo a vedere cosa contengono questi due file

`Unzip di secret.zip`

```bash
$ unzip secret.zip 

Archive:  secret.zip
[secret.zip] secret.txt password: 
password incorrect--reenter: 
password incorrect--reenter: 
   skipping: secret.txt              incorrect password

```

<br>

- Mannaggia lo zip è protetto da password e non possiamo "scompattarlo"

---

# Password Cracking

Esercitazione 01

- Vediamo se con il PDF siamo più fortunati
- Apri un altra shell con `CTRL + SHIFT + T`

`Copiamo il PDF sul nostro host`

```bash
$ docker cp lohacker:/root/secret.pdf .
```

<img src="/media/pwd_37.png" width="300" style="margin:auto;position:relative; left: 0px; top: 30px;">


---

# Password Cracking

Esercitazione 01

- Ok sia il file zip che PDF sono protetti da password. Che fare?
- Proviamo allora a scoprire la password con John The Ripper
- Come abbiamo visto per craccare la password abbiamo bisogno del suo hash, ma dove lo trovo?
- Niente paura sono contenuti nei file stessi, basta solo estrarli

`Estraiamo l'hash dello zip e salviamola in zip.hash`

```bash
$ zip2john secret.zip > zip.hash

ver 1.0 efh 5455 efh 7875 secret.zip/secret.txt PKZIP Encr: 2b chk, TS_chk, cmplen=37, decmplen=25
```

<br>

- Crea il file **zip.hash** che contiene l'hash della passowrd che protegge lo zip

```bash
$ cat zip.hash 
secret.zip/secret.txt:$pkzip$1*2*2*0*25*19*f8be99cc*0*44*0*25*9143*3c8a2e24d545077434272fba02f6312b7e1ed2e880d0a1e7bbc7003545685549bd29f7201a*$/pkzip$:secret.txt:secret.zip::secret.zip
```

---

# Password Cracking

Esercitazione 01

- Ok ora che abbiamo l'hash diamola in pasto a John The Ripper e vediamo se scopre qualcosa
- Utilizziamo un attacco a dizionario (o wordlist nel gergo di JtR)

```bash
$ root@85b9ed463d36:~# /usr/sbin/john --wordlist=/usr/sbin/password.lst --progress-every=1 zip.hash 
Using default input encoding: UTF-8
Loaded 1 password hash (PKZIP [32/64])
Will run 2 OpenMP threads
Note: Passwords longer than 21 [worst case UTF-8] to 63 [ASCII] rejected
Press 'q' or Ctrl-C to abort, 'h' for help, almost any other key for status
pinky009         (secret.zip/secret.txt)     
1g 0:00:00:00 DONE (2024-08-09 10:30) 3.125g/s 4736Kp/s 4736Kc/s 4736KC/s mrbubba..midnight2008
Use the "--show" option to display all of the cracked passwords reliably
Session completed. 
```
<br>

- Bam!!! 

---

# Password Cracking

Esercitazione 01

- JtR ha scoperto che la password è **pinky009**
- Verifichiamolo

```bash
$ unzip -P pinky009 secret.zip 
Archive:  secret.zip
 extracting: secret.txt

$ cat secret.txt 
Se leggi se un hacker!!!
```

<br>

- Molto bene siamno riusciti ad accedere al nostro file zip di cui ci eravamo dimenticati la password 

---

# Password Cracking

Esercitazione 01

- Bene ora lascio allo studente il crack della password del pdf
- Per estrarre l'hash dal file PDF bisogna usare il programma `pdf2john.py`

<br><br>

### Cosa c'è scritto nel file PDF????


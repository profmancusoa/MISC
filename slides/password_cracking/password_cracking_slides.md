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
 
<span style="font-family: 'Creepster', cursive;letter-spacing:5px;color:green; font-weight: 500; font-style:italic;font-size:1.5rem;">Contromisure:</span>

1. Utilizza un algoritmo di hashing potente come bcrypt o scrypt
2. Aggiungi un `salt` univoco a ciascuna password prima di sottoporla ad hashing. 
3. Questo espande il set dei possibili valori, rendendo molto più lento l'attacco a forza bruta e inutile quello basato su rainbow table

---

# Password Cracking

Aggiungere spiegazione salt con openssl ed esempi

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

aggiungere slide su autenticazione a due fattori

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

10 tecniche usate dai Cracker e strategie difensive
10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---


- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---
10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- erfds 
- erfds


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
as: 2023/2024
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

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- Fin dagli albori dell'informatica il metodo più utilizzato per proteggere l'accesso ad una risorsa informatica (account, sito web, web banking, ...) è la coppia `username` e `password`.
- Il sistema verifica l'identità del soggetto che vuole utilizzare un dato servizio richiedendo:
  - **username**: un nome univoco che identifica il soggetto (umano o altra macchina) che richiede l'accesso al servizio
  - **password**: un segreto solamente in possesso dello username che richiede l'accesso al sistema
   
<img src="/media/pwd_01.png" width="350" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

- Le password rappresentano la prima linea di difesa contro gli attacchi informatici
- Dato il loro larghissimo uso, sono anche **uno degli anelli più deboli** della sicurezza informatica.
-  Gli hacker (***Black Hat*** --> sottospecie: **Cracker**) utilizzano diverse tecniche per decifrare le password 
-  Uno dei metodi migliori per adottare misure per prevenirli consiste nel comprendere tali metodo 
-  Pertanto per i singolo individui e per le organizzazioni è utilissimo comprendere questi metodi  
-  Nel seguito vederemo le dieci principali tecniche di cracking delle password utilizzate dagli cracker e fornirà suggerimenti su come prevenirle.

<img src="/media/pwd_02.png" width="650" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<Banner padding=30px>
Un <mark>white hat</mark> è un hacker esperto di programmazione, di sistemi e di sicurezza informatica in grado di introdursi in reti di computer al fine di aiutarne i proprietari a prendere coscienza di un problema di sicurezza nel rispetto quindi dell'etica degli hacker e si contrappone a chi viola illegalmente sistemi informatici, anche senza vantaggio personale.
</Banner>

<img src="/media/pwd_03.png" width="450" style="margin:auto;position:relative; left: 0px; top: 10px;">


---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<Banner padding=30px>
Il cracker <mark>black hat</mark> invece è un profilo decisamente più pericoloso e soprattutto dannoso. Il suo obiettivo infatti è violare illegalmente  l’integrità di un sistema informatico con l’intenzione di creare appositamente dei danni, spesso per trarre vantaggio personale. 
</Banner>

<img src="/media/pwd_04.png" width="350" style="margin:auto;position:relative; left: 0px; top: 20px;">


<style>
  @import url('https://fonts.googleapis.com/css2?family=Creepster&display=swap');
</style>

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
1
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Brute Force Attack</span>  
</div>

- Un attacco di forza bruta è una tecnica comune di cracking delle password che prevede di provare ogni possibile combinazione di caratteri finché non viene trovata la password corretta. Gli hacker utilizzano software specializzati per automatizzare questo processo e possono decifrare anche password complesse se hanno abbastanza tempo. Utilizza password complesse e univoche con lettere maiuscole e minuscole, numeri e simboli per prevenire attacchi di forza bruta. Implementare policy relative alle password che richiedano agli utenti di modificare regolarmente le password e limitare il numero di tentativi di accesso non riusciti prima che l'account venga bloccato.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
2
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Dictionary Attack</span>  
</div>

- Un attacco con dizionario è simile a un attacco di forza bruta ma utilizza un elenco di parole da un dizionario o password di uso comune per decifrare le password. Gli hacker utilizzano software in grado di provare migliaia di parole al minuto finché non viene trovata la password corretta. Per prevenire attacchi tramite dizionario, evitare di utilizzare parole, frasi o password comuni facili da indovinare. Utilizza invece una combinazione di caratteri casuali e non utilizzare la stessa password su più account.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
3
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Rainbow Table Attack</span>  
</div>

- Un attacco Rainbow Table è un attacco hash precalcolato che utilizza una tabella di hash precalcolati per decifrare rapidamente le password. Gli hacker creano una tabella di password comuni e dei relativi hash corrispondenti, quindi confrontano gli hash della password di destinazione con la tabella per trovare una corrispondenza. Per prevenire gli attacchi alle tabelle arcobaleno, utilizza un algoritmo di hashing potente come bcrypt o scrypt e aggiungi un sale univoco a ciascuna password prima di sottoporla ad hashing.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
4
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Social Engineering</span>  
</div>

- L'ingegneria sociale è una tecnica che prevede la manipolazione delle persone per indurle a rivelare le loro password o altre informazioni sensibili. Gli hacker possono impersonare una persona fidata, inviare e-mail di phishing o utilizzare altre tattiche per indurre gli utenti a rivelare le proprie password. Informare gli utenti sui rischi legati alla condivisione di password e informazioni sensibili per prevenire attacchi di ingegneria sociale. Utilizza l'autenticazione a due fattori (2FA) per aggiungere un ulteriore livello di sicurezza e verificare l'identità di chiunque richieda informazioni sensibili.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
5
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Shoulder Surfing</span>  
</div>

- Lo spallamento è un attacco fisico che prevede l'osservazione di qualcuno che inserisce la propria password su un computer o dispositivo mobile. Gli hacker possono guardare oltre le spalle di qualcuno in un luogo pubblico o installare una telecamera nascosta per catturare le password. Per prevenire attacchi di spalla, fai attenzione a ciò che ti circonda quando inserisci le password ed evita di inserirle in luoghi pubblici. Inoltre, puoi utilizzare una schermata privacy per impedire ad altri di visualizzare il tuo schermo e bloccare il dispositivo quando non viene utilizzato

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
6
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Phishing</span>  
</div>

- Il phishing è una tecnica che prevede l'invio di e-mail o messaggi che sembrano provenire da una fonte legittima per indurre gli utenti a rivelare le proprie password o altre informazioni sensibili. Gli hacker utilizzano tattiche di ingegneria sociale e un linguaggio persuasivo per convincere gli utenti a fare clic su collegamenti o aprire allegati che installano malware o rubano dati. Per prevenire attacchi di phishing, prestare attenzione quando si aprono e-mail o messaggi provenienti da fonti sconosciute e cercare segni di phishing, come errori di ortografia o collegamenti sospetti. Inoltre, utilizza i filtri e-mail per bloccare i messaggi sospetti e abilitare l'autenticazione a più fattori (MFA) per impedire l'accesso non autorizzato all'account.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
7
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Key Logger Attack</span>  
</div>

- La registrazione delle sequenze di tasti è una tecnica che prevede l'acquisizione di ogni sequenza di tasti immessa su un computer o dispositivo mobile, comprese le password. Gli hacker possono installare malware o utilizzare dispositivi fisici per acquisire sequenze di tasti e rubare password. Per prevenire attacchi di registrazione dei tasti, utilizzare un software antivirus e mantenerlo aggiornato, evitare di fare clic su collegamenti sospetti o di scaricare software da fonti non attendibili e utilizzare un gestore di password basato su hardware per archiviare le password.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
8
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Malware Attack</span>  
</div>

- Il malware è un tipo di software progettato per danneggiare o ottenere l'accesso non autorizzato a un computer o a una rete. Il malware può essere utilizzato per rubare password, acquisire sequenze di tasti ed eseguire altri attacchi. Mantieni aggiornati il ​​tuo software e i tuoi sistemi operativi con le patch e gli aggiornamenti di sicurezza più recenti per prevenire attacchi malware. Utilizza un software antivirus e mantienilo aggiornato, evita di fare clic su collegamenti sospetti o di scaricare software da fonti non attendibili e diffidare delle e-mail o dei messaggi con allegati.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive


<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
9
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Man-in-the-Middle (MITM) Attack</span>  
</div>

- Un attacco man-in-the-middle (MITM) avviene quando un hacker intercetta le comunicazioni tra due parti per rubare informazioni sensibili, comprese le password. Gli hacker utilizzano software o dispositivi fisici per intercettare le comunicazioni e acquisire password. Per prevenire attacchi MITM, utilizzare canali di comunicazione sicuri, come HTTPS o una rete privata virtuale (VPN), quando si accede a informazioni sensibili o si accede ad account. Inoltre, verifica l'identità del sito Web o del servizio a cui stai accedendo e fai attenzione alle reti Wi-Fi pubbliche o non protette.

---

# Password Cracking

10 tecniche usate dai Cracker e strategie difensive

<div style="margin-bottom:10px;font-family: 'Creepster', cursive;">
<div style="width:60px; height:60px; border: 1px solid red; background: red; color: white; border-radius:100px; text-align: center; line-height:60px; font-size:40px; font-weight: 900; display:inline-block;" >
10
</div>
<span style="padding-right:10px;border:1px solid red; background: red; color: white;position: relative; top: -4px; left:-10px; font-size:30px;">Password Reuse</span>  
</div>

- Il riutilizzo della password è una pratica comune tra gli utenti e rappresenta un rischio significativo per la sicurezza. Gli hacker possono utilizzare le password rubate da un account per accedere ad altri se la stessa password viene riutilizzata. Per prevenire attacchi legati al riutilizzo della password, utilizza una password univoca per ciascun account e considera l'utilizzo di un gestore di password per generare e archiviare password complesse. Inoltre, implementa l'autenticazione a più fattori (MFA) su tutti gli account per aggiungere un ulteriore livello di sicurezza e monitora regolarmente i tuoi account per attività sospette.



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


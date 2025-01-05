# CENGBOX: Penetration Testing and Ethical Hacking

## Descrizione
Questo repository documenta un progetto di penetration testing didattico su un asset virtualizzato. Il progetto include tutte le fasi principali del penetration testing, dal discovery iniziale fino al mantenimento dell'accesso, utilizzando strumenti e metodologie consolidate.

### Scopo del Progetto
- Eseguire un'analisi completa della sicurezza del sistema target.
- Documentare le vulnerabilità individuate.
- Dimostrare le tecniche di compromissione e mantenimento dell'accesso.
- Fornire suggerimenti per migliorare la configurazione di sicurezza.

## Struttura del Progetto
Il progetto segue le seguenti fasi:
1. **Target Discovery**
   - Identificazione del sistema con strumenti come `nmap`, `arp-scan` e `p0f`.
2. **Target Enumeration**
   - Raccolta di informazioni sulle porte aperte e servizi attivi.
3. **Vulnerability Mapping**
   - Scansione e rilevamento vulnerabilità con tool come `Nessus`, `OWASP ZAP` e `Nikto`.
4. **Target Exploitation**
   - Tentativo di exploit delle vulnerabilità tramite strumenti automatizzati (`Metasploit`, `Armitage`) e manuali.
5. **Privilege Escalation**
   - Elevazione dei privilegi sul sistema target.
6. **Maintaining Access**
   - Creazione e utilizzo di backdoor per mantenere l'accesso al sistema compromesso.

## Strumenti Utilizzati
- **Network Scanning:** `nmap`, `arp-scan`, `p0f`
- **Vulnerability Scanning:** `Nessus`, `OWASP ZAP`, `Nikto`
- **Directory Bruteforcing:** `Dirb`, `OWASP DirBuster`, `Gobuster`
- **Exploit Frameworks:** `Metasploit`, `Armitage`

## Risultati
La macchina target è risultata vulnerabile in diverse aree, tra cui:
- Navigazione non autorizzata nelle directory web.
- Utilizzo di librerie deprecate (es. jQuery).
- Assenza di configurazioni di sicurezza avanzate (Content Security Policy, X-Frame Options).
- Cross-site scripting e algoritmi deboli.

## Conclusioni
Il sistema è stato compromesso con successo. I suggerimenti per migliorare la sicurezza includono:
- Riconfigurazione del web server.
- Aggiornamento delle librerie software.
- Rimozione delle informazioni esposte inutilmente.

## Autore
**Mattia d’Argenio**

Se hai domande o suggerimenti, non esitare a contattarmi.

---

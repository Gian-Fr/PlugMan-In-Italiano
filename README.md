# PlugMan

PlugMan è un semplice plugin che permette agli admin di gestire i plugins in-game o con la conscole senza dover riavviare il server.

## Features
* Attiva, Disattiva, Riavvia, Carica, Ricarica, e Disattiva i plugins in-game oppure con la console.
* Mostra i plugins in ordine alfabetico, con la versione (se specificata).
* Ottieni informazioni utili sui plugins ( comandi, versione, autore(i), etc. )
* Gestisci facilmente i plugins senza dover continuamente riavviare il server.
* Mostra i comandi registrati da un plugin.
* Trova il plugin che ha registrato quel comando.
* Auto riempimento con TAB per i nomi dei comandi e i nomi dei plugins.
* Crea un file con la lista dei plugins e le versioni.
* ~Controlla se il plugin è aggiornato con dev.bukkit.org~ Attualmente non disponibile
* Supporto dei Permessi - Tutti i comandi sono OP di default.

## Comandi
| Comando | Descrizione |
| --------------- | ---------------- |
| /plugman help | Mostra informazioni di aiuto. |
| /plugman list [-v] | Mostra tutti i Plugin (-v mostra le versioni). |
| /plugman info [plugin] | Ricevi informazioni su quel Plugin. |
| /plugman dump | Copia il nome e la versione del Plugin in un File. |
| /plugman usage [plugin] | Mostra i comandi che sono registrati dal Plugin. |
| /plugman lookup [command] | Trova il Plugin a cui è registrato il comando. |
| /plugman enable [plugin&#124;all] | Attiva il Plugin (all attiva tutti). |
| /plugman disable [plugin&#124;all] | Disattiva il Plugin (all disattiva tutti). |
| /plugman restart [plugin&#124;all] | Riavvia il Plugin (all riavvia tutti). |
| /plugman load [plugin] | Carica il Plugin. |
| /plugman reload [plugin&#124;all] | Ricarica il Plugin. |
| /plugman unload [plugin] | Rimuove il Plugin (per caricarlo nuovamente usa load). |
| /plugman check [plugin&#124;all] [-f] | Controlla se un Plugin è aggiornato (-f copia in un file per tutti). |

## Permessi
| Permesso | Default | Descrizione |
| ------------------------- | ---------- | ---------------- |
| plugman.admin | OP | Consente l'uso di tutti i comandi. |
| plugman.update | OP | Consente agli utenti di vedere i messaggi di aggiornamento. |
| plugman.help | OP | Consente l'uso del comando /plugman help. |
| plugman.list | OP | Consente l'uso del comando /plugman list. |
| plugman.info | OP | Consente l'uso del comando /plugman info. |
| plugman.dump | OP | Consente l'uso del comando /plugman dump. |
| plugman.usage | OP | Consente l'uso del comando /plugman usage. |
| plugman.lookup | OP | Consente l'uso del comando /plugman lookup. |
| plugman.enable | OP | Consente l'uso del comando /plugman enable. |
| plugman.enable.all | OP | Consente l'uso del comando /plugman enable all. |
| plugman.disable | OP | Consente l'uso del comando /plugman disable. |
| plugman.disable.all | OP | Consente l'uso del comando /plugman disable all. |
| plugman.restart | OP | Consente l'uso del comando /plugman restart. |
| plugman.restart.all | OP | Consente l'uso del comando /plugman enable all. |
| plugman.load | OP | Consente l'uso del comando /plugman load. |
| plugman.reload | OP | Consente l'uso del comando /plugman reload. |
| plugman.reload.all | OP | Consente l'uso del comando /plugman reload all. |
| plugman.unload | OP | Consente l'uso del comando /plugman unload. |
| plugman.check | OP | Consente l'uso del comando /plugman check. |
| plugman.check.all | OP | Consente l'uso del comando /plugman check all. |

## Configurazione
| File | URL |
| ----- | ------- |
| config.yml | https://github.com/r-clancy/PlugMan/blob/master/src/main/resources/config.yml |

## Sponsor 

<div style="text-align:center" markdown="1">

![image](https://raw.githubusercontent.com/r-clancy/PlugMan/master/images/jetbrains_logo.png "JetBrains")

JetBrains sta gentilmente supportando il progetto open source ( PlugMan ) con il suo Java IDE pieno di Features!

Dai un occhiata al software JetBrains <a href="http://www.jetbrains.com/">sul sito.</a>

---

![image](https://raw.githubusercontent.com/r-clancy/PlugMan/master/images/yourkit_logo.png "YourKit")

YourKit sta gentilmente supportando il progetto open source ( PlugMan ) con il suo Java Profiler pieno di Features!

YourKit è il creatore di strumenti innovativi e intelligenti per il profiling Java e .NET .

Dai un occhiata al software YourKit : <a href="http://www.yourkit.com/java/profiler/index.jsp"> Java Profiler</a> e <a href="http://www.yourkit.com/.net/profiler/index.jsp"> .NET Profiler</a>.

---

![image](https://raw.githubusercontent.com/r-clancy/PlugMan/master/images/intreppid_logo.png "Intreppid Logo")

Intreppid sta gentilmente supportando il progetto open source ( PlugMan ) con l' hosting per le build Jenkins insieme ad una piattaforma di test per lo sviluppo.

Dai un occhiata all' hosting premium (server dedicati e server di minecraft) di Intreppid <a href="https://www.intreppid.com/">sul sito </a>.

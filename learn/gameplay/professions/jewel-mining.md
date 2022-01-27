---
description: Informazioni riguardanti le JEWEL Mining Quests di livello 0
---

# JEWEL Mining

**Le seguenti informazioni sono corrette per la versione della Quest rilasciata sul sito** [**Beta**](https://beta.defikingdoms.com/#/)**. Qualsiasi informazione contenuta in questo documento è soggetta a modifiche.**

**le missioni JEWEL Mining** possono essere eseguite da un gruppo di un numero compreso tra 1 e 6 Eroi alla volta. Gli Eroi possono essere messi in coda per iniziare la Quest non appena la Stamina degli Eroi attualmente in missione viene consumata totalmente; tuttavia, il gruppo di Eroi interromperà la Quest non appena la Stamina di un Eroe raggiungerà lo zero. Inoltre, una volta che un gruppo di qualsiasi dimensione entra nella miniera, non è possibile aggiungere ulteriori minatori al gruppo. Quegli Eroi verranno messi in coda e non inizieranno la loro Quest fino a quando un Eroe nel gruppo precedente non raggiunge 0 Stamina, causando l'interruzione della missione dell'intero gruppo, o finché il giocatore non termina la Quest in anticipo.

**Le missioni JEWEL Mining** richiedono al giocatore di selezionare un **Lead Miner**. La quantità massima di JEWEL che può essere sbloccata nella Quest è determinata dalle **Statistiche del Lead Miner**: i punteggi **STR** ed **END** dell'Eroe, il livello di **Mining** e se ha il **Mining** come professione principale, influiscono sulla quantità massima che può essere sbloccata. Quando viene selezionato un **Lead Miner**, verranno visualizzati i ​​JEWEL sbloccabili massimi per il party e la quantità di JEWEL che può essere sbloccata dal **Lead Miner**.

È possibile aggiungere fino a cinque altri Eroi al gruppo di Mining per assistere il **Lead Miner**. Il loro contributo si baserà sui punteggi **STR** ed **END**, sul punteggio di **Mining** e sul fatto che gli Eroi abbiano o meno il **Mining** come Professione principale. Man mano che i singoli Eroi vengono aggiunti al gruppo, la quantità totale di JEWEL che il gruppo può sbloccare si aggiornerà aumentando. Una volta che l'importo totale sbloccabile del gruppo raggiunge l'importo massimo sbloccabile, l'aggiunta di altri Eroi non aumenterà ulteriormente i JEWEL sbloccabili, sebbene quegli Eroi possano comunque ricevere le **Gaia's Tears, Rune Shvās** e le **Uova Gialle**.

Gli Eroi con **Mining** come Professione principale consumano 1 Stamina ogni 10 minuti, tutti gli altri Eroi consumano 1 Stamina ogni 12 minuti. Tuttavia, se un gruppo di minatori contiene Eroi che non hanno **Mining** come Professione principale, tutti gli Eroi in quel gruppo consumeranno Stamina al tasso di 1 ogni 12 minuti. È importante raggruppare strategicamente i minatori per ottenere le massime ricompense.

Le missioni Mining hanno anche la possibilità di premiare gli Eroi con le **Gaia's Tears**, **Rune Shvās** e le **Uova Gialle**.\
**I Drop Rates base degli oggetti aumentano grazie al punteggio STR, END,  Mining, ed il gene Mining dell''Eroe.**

### **Formula dei Reward per Quest livello 0:**

**Formula Max unlock rate:**\
maxUnlockRate = (1000 \* (0.25 + (**STR** + **END**) \* 0.000625 + (**MinSkl**) \* 0.0025)) / lockedRatio

**Formula LockedRatio:**\
se lockedJWL > minLocked {\
lockedRatio = (1000 - 166 \* geneBonus)\
gli altri:\
lockedRatio = ((1000-166 \* geneBonus) \* minLocked) / lockedJWL

**Formula Hero unlock rate:**\
heroUnlockRate = (1000 \* (0.25 + (**STR** + **END**) \*0.000625 +(**MinSkl**) \* 0.0025)) / (6 \* (1000 -\
166 \* geneBonus))

**minLocked** = 20,000 JEWEL (si riduce linearmente se il portafoglio ha meno di 20.000 JEWEL bloccati)

**minSkill** = il valore intero dell'abilità Mining dell'Eroe

**geneBonus** = 1 se l'Eroe ha Mining come Professione principale, altrimenti 0

Inoltre, per ogni 15 Stamina consumati dal **Lead Miner**, c'è una probabilità del 10% di ricevere JEWEL bonus. Il bonus massimo è di 10 JEWEL, se il portafoglio ha almeno 5.000 JEWEL bloccati. Il bonus si riduce linearmente se il portafoglio ha meno di 5.000 JEWEL bloccati. Questo bonus viene dimezzato se il **Lead Miner** non ha il **Mining** come Professione principale.

### **Drop Rates Quest livello 0:**

**Shvās rune** - 0.3% per 5 Stamina spesi, aumentato a 1.5% con Mining come Professione principale

**Gaia's Tears** - 7% per 5 Stamina spesi, aumentato a 10.75% con Mining come Professione principale

**Uovo Giallo** - 0.02% (per 10 Stamina spesi)

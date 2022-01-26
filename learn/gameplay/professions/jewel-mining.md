---
description: Information about the Level 0 JEWEL Mining quest.
---

# JEWEL Mining

**Le seguenti informazioni sono corrette per la versione della Quest rilasciata sul sito** [**Beta**](https://beta.defikingdoms.com/#/)**. Qualsiasi informazione contenuta in questo documento è soggetta a modifiche.**

**le missioni JEWEL Mining** possono essere eseguite da un gruppo di un numero compreso tra 1 e 6 Eroi alla volta. Gli Eroi possono essere messi in coda per iniziare la Quest non appena la Stamina degli Eroi attualmente in missione viene consumata totalmente; tuttavia, il gruppo di Eroi interromperà la Quest non appena la Stamina di un Eroe raggiungerà lo zero. Inoltre, una volta che un gruppo di qualsiasi dimensione entra nella miniera, non è possibile aggiungere ulteriori minatori al gruppo. Quegli Eroi verranno messi in coda e non inizieranno la loro Quest fino a quando un Eroe nel gruppo precedente non raggiunge 0 Stamina, causando l'interruzione della missione dell'intero gruppo, o finché il giocatore non termina la Quest in anticipo.

Le missioni JEWEL Mining richiedono al giocatore di selezionare un Lead Miner. La quantità massima di JEWEL che può essere sbloccata nella Quest è determinata dalle Statistiche del Lead Miner: i punteggi STR ed END dell'Eroe, il livello di Mining e se ha il Mining come professione principale, influiscono sulla quantità massima che può essere sbloccata. Quando viene selezionato un Lead Miner, verranno visualizzati i ​​JEWEL sbloccabili massimi per il party e la quantità di JEWEL che può essere sbloccata dal Lead Miner.

È possibile aggiungere fino a cinque altri Eroi al gruppo di Mining per assistere il Lead Miner. Il loro contributo si baserà sui punteggi STR ed END, sul punteggio di Mining e sul fatto che gli Eroi abbiano o meno il Mining come Professione principale. Man mano che i singoli Eroi vengono aggiunti al gruppo, la quantità totale di JEWEL che il gruppo può sbloccare si aggiornerà aumentando. Una volta che l'importo totale sbloccabile del gruppo raggiunge l'importo massimo sbloccabile, l'aggiunta di altri Eroi non aumenterà ulteriormente i JEWEL sbloccabili, sebbene quegli Eroi possano comunque ricevere le Gaia's Tears, le rune Shvās e le Uova Gialle.

Heroes with **mining** as their main profession expend 1 Stamina every 10 minutes, and all other Heroes expend 1 Stamina per 12 minutes. However, if a party of Miners contains Heroes that do _not_ have **mining** as their main profession, all Heroes in that party will expend at the 1 Stamina per 12 minutes rate. It is important to strategically group miners to achieve maximum rewards.

Mining quests also have a chance to reward Heroes with **Gaia's Tears**, **Shvās runes**, and **Yellow Eggs**. Item drop rates are increased by varying combinations of **STR**, **END**, the **mining** stat, and the **mining** gene.

### **Level 0 rewards formula:**

**Max unlock rate formula:**\
maxUnlockRate = (1000 \* (0.25 + (**STR** + **END**) \* 0.000625 + (**MinSkl**) \* 0.0025)) / lockedRatio

**LockedRatio formula:**\
if lockedJWL > minLocked {\
lockedRatio = (1000 - 166 \* geneBonus)\
else\
lockedRatio = ((1000-166 \* geneBonus) \* minLocked) / lockedJWL

**Hero unlock rate formula:**\
heroUnlockRate = (1000 \* (0.25 + (**STR** + **END**) \*0.000625 +(**MinSkl**) \* 0.0025)) / (6 \* (1000 -\
166 \* geneBonus))

**minLocked** = 20,000 JEWEL (scales down linearly if wallet has less than 20k locked JEWEL)

**minSkill** = the integer value of the Hero's **mining** skill

**geneBonus** = 1 if character has **mining** as their main skill, else 0

Additionally, for every 15 Stamina spent by the **lead miner**, there is a 10% chance to receive bonus JEWEL. The maximum bonus is 10 JEWEL, if the wallet has at least 5,000 locked JEWEL. The bonus scales down linearly if the wallet has less than 5,000 locked JEWEL. This bonus is halved if the **lead miner** does not having **mining** as their main skill.

### Level 0 base item drop rates:

**Shvās rune** - 0.3% per 5 Stamina expended, boosted to 1.5% with **mining** main skill

**Gaia's Tears** - 7% per 5 Stamina expended, boosted to 10.75% with **mining** main skill

**Yellow Egg** - 0.02% (per 10 Stamina spent)

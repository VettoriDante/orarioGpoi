# progettoOrario
Progetto di prova per comandi git - commit - branch - merge

# GIT UNDO
- fino ad ora sono stati eseguiti 4 commit da giuseppe.senatore@itismeucci.com (Giuseppe)
- attualmente ci troviamo sul branch main
- index.html ha subito 8 modifiche e style.css ha subito 2 modifiche

## Git reset
Il comando si usa per spostare l'HEAD ovvero per scorrere ad un commit passato senza
però eliminare i commit "futuri" ovvero quelli realizzati dopo di esso
è rischioso perchè proprio come il checkout danno impressione di aver cancellato 
i commit futuri che in realtà esistono anc'ora

## Git revert
Con git revert si usa sostanzialmente un tranello andando a creare un commit identico 
ad uno passato dando così l'impressione di "essere andati avanti" nel lavoro,
sebbene questo serva solo perchè su git il numero dei commit non può main diminuire
ed è infatti questo il problema che si riscontra con reset e checkout (sembra che manchino commit)
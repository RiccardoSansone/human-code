# Fare la spesa seguendo una lista
## Fatti mandare dalla mamma a prendere il latte
Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra!
# Esecuzione
Aprire il frigorifero
Fare una lista di ciò che manca
Assicurarsi di aver inserito nella lista le crocchette
Controllare la validità del coupon
Se siamo entro la fine del mese corrente
    - il coupon è valido
Se è valido
    - lo metto nel portafoglio
Altrimenti
    - lo lascio a casa
Andare al supermercato convenzionato
Controlla ogni singolo scaffale fino al depennamento totale della lista
    Se nello scaffale è presente un elemento della lista
        - lo aggiungiamo al carrello
        - eliminiamo l'elemento dalla lista
    altrimenti controlla lo scaffale successivo
    Se la lista è tutta depennata
    - andare in cassa
    - effettuare pagamento
    -Se il totale del carrello è maggiore del valore coupon più il totale dei contanti nel portafoglio
        - Eliminiamo dal carrello gli snack extra
        Altrimenti
        - Proseguiamo col pagamento
    - Tornare a casa per mettere la spesa in frigo
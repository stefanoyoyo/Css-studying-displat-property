In questo progetto voglio imparare ad evitare display flex 
nel definire come disporre gli elementi nella pagina.

COSA HO IMPARATO: 
 • Solo i tipi di display "flex" e "grid" permettono di definire come 
   devono essere disposti gli elementi all'interno di un container: tutti
   gli altri invece lavorano sul singolo elemento su cui viene applicato il 
   display. 
   ESEMPIO: la classe flex all'interno di un container permette di indicare che
   tutto ciò che si trova al suo intenro deve essere posto al centro. 
   Idem per la classe grid. 
   Per gli altri tipi di display invece vale che il display usato stilizza 
   direttamente l'elemento su cui è posto. In particolare: 
      • block: indica che l'elemento sta sulla riga successiva a quello 
               precedente. Anche l'ememento dopo sarà sulla riga dopo. 
      • inline: l'elemento è posto sulla stessa riga dell'elemento precedente.
                Non è possibile applicare width e height. 
                Se ad esempio voglio porre un immagine nella stessa riga 
                dell'elemento precedente, è meglio non usare inline perchè 
                sarei costretto a farle avere la sua dimensione originale.  
      • inline-block: uguale ad inline ma ammette width ed height.
 • DISPLAY PREDEFINITI NEGLI ELEMENTI HTML: ogni elemento html possiede un display
  applicato di default. Segue un esempio di elementi:
      • div: possiede un display block di default. Provando infatti a scrivere 3 div
             e porvi dentro del testo, mi sccorgo che sono messi automaticamente uno 
             per riga. Avrò quindi 3 righe, ognuna contenente il suo testo. 
      • paragrafo: la stessa cosa di "div".
      • span: possiene un display inline di default. Questa è la ragione per cui degli
              span stanno sempre sulla stessa riga, quando ovviamente non viene modificato
              il loro display. 
      • 
 
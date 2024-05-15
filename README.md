# Random e Pseudo Random




### PRNG

I generatori di numeri pseudo-casuali (PRNG) producono sequenze che sembrano casuali, ma sono generate da formule matematiche o tabelle precalcolate, come il metodo congruenziale lineare. Rispetto ai generatori di numeri casuali veri e propri (TRNG), i PRNG generano sequenze predeterminate, simili a lanci di dado già registrati. Tuttavia, sono efficienti e deterministici, utili per applicazioni che richiedono molte iterazioni o riproducibilità. Sebbene periodici, i moderni PRNG hanno periodi lunghi che li rendono praticamente imprevedibili per molti scopi. Sono adatti per simulazioni e modellazioni ma non per crittografia o giochi d'azzardo, dove è cruciale l'imprevedibilità. L'affidabilità dei PRNG dipende dall'algoritmo e dall'implementazione. Ad esempio, PHP su GNU/Linux genera buoni numeri casuali, ma su Windows potrebbe fallire. È importante scegliere attentamente il PRNG in base alle esigenze specifiche dell'applicazione per evitare inconvenienti, come dimostrato da casi come la simulazione di infezioni virali su MacOS nel 2002.



### TRNG
I veri generatori di numeri casuali (TRNG) si differenziano dai PRNG perché estraggono casualità da fenomeni fisici, come variazioni nei movimenti del mouse o nel tempo tra la pressione dei tasti. Fonti come radioattività o rumore atmosferico sono utilizzate per garantire casualità autentica senza buffering del sistema operativo. Il servizio HotBits e RANDOM.ORG sono esempi di TRNG basati su radioattività e rumore atmosferico rispettivamente. Altri approcci includono l'uso del rumore di fondo o fenomeni visivi come lampade lava. Tuttavia, la generazione di numeri casuali reali richiede l'identificazione di piccoli cambiamenti imprevedibili nei dati. Rispetto ai PRNG, i TRNG sono inefficienti e non deterministici, producendo numeri senza possibilità di riproduzione e senza periodo definito.


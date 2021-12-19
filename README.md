# Vaja6-ADC-scan-mode-conversion-Nucleo-

⦁	Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. 
  To so pini PC0, PC1 in PC2. 
  
Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to?
  C.
  

⦁	Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? 
  ADC1_IN1, ADC1_IN2 in ADC1_IN3.
  
⦁	V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4 MHz. Koliko bo izbrana vrednost parametra?

  4 .
  
  
⦁	Čas vzorčenja Sampling Time izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah?_26,125._ Enačba za izračun: tvz = (tvz_cik + 12) / ftakta_pretvorbe


⦁	V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC1. Dolžina podatka pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width: _byte_ (tako za Peripheral in Memory). Increment Address omogočite le v registru Memory. V izbirnem polju za način delovanja Mode izberite Circular. Kliknite Ok. Sedaj tudi omogočite DMA Continuos Requests v oknu Parameter Setttings.


⦁	Kaj pomeni kratica DMA? 
  Direct memory access(neposredni dostop do pomnilnika).
  
  
KOMENTAR: naloga mi ne deluje. ko vdebug dam adcVal mi ne pokaže izmerjave.

# Vaja1-ADC-Single-Conversion-STM32F0
<h4> Glede na vašo razvojno ploščico in razširitveno vezje s tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? </h4>
<p> Izbrali smo pin Pc0. </p>
<h4> V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? </h4>
<p> Naša razvojna plošča ima 1 pretvornik. </p>
<h4> Izbran ADC pretvornik ima oznako s trikotnikom, kaj to pomeni? </h4>
<p> Trikotnik pomeni, da je pin zaseden. </p>
<h4> Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite. </h4>
<p> Pin ki je zaseden postavimo na reset state. Na zavihku ADC obkljukamo pa IN10. S tem smo nastavili pin Pc0, da je naš pretvornik. </p>
<h4> Razširite razdelek ADC. Koliko je vseh vhodnih kanalov? </h4>
<p> Vseh vhodnik kanalov je 16. </p>
<h4> Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? </h4>
<p> Poleg pina se izpiše ADC_IN10. </p>
<h4> V Configuration kliknemo ADC gumb. V parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 do 255. Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?. </h4>
<p> 8 bit, od 0 do 256. </p>
<p> 10 bit, od 0 do 1024. </p>
<p> 12 bit, od 0 do 4096. </p>
<h4> Komentar: </h4>
<p> 

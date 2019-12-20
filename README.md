# Vaja2-ADC-continuos-conversion-STM32F0

b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? Odgovor: PC0.

e) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? Odgovor: ADC_IN10.

f) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. Kaj opazite? Odgovor: Vse se spremeni na 16 MHz.

h) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? Odgovor: 4 MHz.

j) Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239,5 cikov. Pravi čas vzorčenja se nato poveča še za 12 ciklov.
Koliko znaša pravi čas vzorčenja t vz v mikro sekundah? (enačba: tvz = tvz_ciklih / fpreskalriana )? Odgovor: 62,875 µs.

Komentar: Ko sva hotela naložiti program nama je vedno javljalo, da se STMF0 obnaša kot nov strežnik.
Vse kar sva morala narediti je, da sva pritisnila dovoli in vse je potekalo naprej normalno.

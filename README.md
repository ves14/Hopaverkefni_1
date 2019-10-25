# Hópverkefni 1

## Hópur:
Ingibjörg Birgisdóttir inb32@hi.is  
Vigdís Erla Sigmundsdóttir ves14@hi.is  
Yrsa Ósk Finnbogadóttir yof3@hi.is  

## SíðurUppsetning verkefnis:
Forsíða: index.html  
Vörur: products.html  
Námskeið: course.html  
Starfsfólk: staff.html  
Karfa: cart.htmlscss   

## Skrár:
Forsíða: Forsida.scss  
Vörur: Products.scss  
Námskeið: Course.scss  
Starfsfólk: Staff.scss  
Karfa: Cart.scss  
Haus: header.scss  
Fótur: footer.scss  
*Scss skrár fara allar inní stylse.css skránna.

## Hópavinna:
Hópavinnan gekk mjög vel. Við skiptum á milli okkar síðunum og deildum skjölunum á Git (þó að það hafi gengið mjög erfiðlega) og áttum í samskiptum á slack. Git og node modules voru mikið að stríða okkur og fór dágóður tími í að reyna að fá það allt til að virka. Góður andi var samt í hópnum þrátt fyrir allt þetta óþarfa vesen sem við lentum í.

## Lýsing á verkefni:
Verkefninu okkar er skipit upp á þann hátt að allar .scss skrárnar okkar eru geymdar í möppunni scss og allar html skrárnar okkar eru geymdar í möppunni pages. Hver síða á vefsíðunni okkar hefur sér html skrá í pages möppunni og samsvarandi scss skrá í scss möppunni. Auk þess bjuggum við til sér scss skrár fyrir bæði footer og header, þeirra html er að finna innan allra grunn html skránna. Síðan höfum við importað öllum scss skránum okkar inn í scss skrá að nafninu styles.scss, en hún geymdir því scss kóðan í heild sinni. 
  
Í jason skránni okkar er að finna 6 node-modules scriptur, 5 sem við nýttum mismikið.
  - browser-sync: sem gerði okkur kleypt að fylgjast með breytingum á html + css kóðanum okkar.
  - sass: sem tók fyrir okkur styles.scss skránna og þýddi yfir í css sem að vefþjónninn skilur.
  - sass-watch: gerði okkur kleypt að þýða styles.css skránna strax og breytingar voru gerða í scss kóðanum.
  - dev: keyrði browser-syncið og sass-watchið á sama tíma. Með þessu gátum við séð allar þær breytingar sem gerðar voru á bæði html og scss kóðanum um leið og þær voru gerðar sem auðveldaði vinnuna gríðalega.
  - lint: las yfir kóðan okkar og lét okkur vita af þeim villum sem við gerðum.
  
  
Vefsíðunni okkar er skipt upp í 5 mismunandi parta:

1. Forsíðu: sem hefur 2 myndir sem tengjast fyrirtækinu + smá upplýsingum um það.
2. Vöru síðu: hefur myndir af klifurvörunum sem eru til sölu, möguleika á að velja fjöldan sem þú vilt af hlutnum og takka til þess að færa vörurnar í körfu.
3. Námskeiðasíðu: á henni er smá lýsing um námskeiðin auk forms sem að einstaklingar geta fyllt til að skrá sig á námskeiðin.
4. Starfsmannasíða: á henni eru myndir af starfsmönnunum 4 sem vinna í Prílihúsinu og hef mús er færð yfir myndirnar snúast þær við og sýna smá upplýsingar um hvern og einn.
5. Karfa: Í körfunni eru nú þegar komnir 2 hlutir, kalkpoki og bakpoki. Einning er að finna form sem þyrfti að fylla út ef að pannta ætti vörurnar.
  
Allar síðurnar hafa síðan header, á honum eru linkar sem fara með þig milli síða, og footer. Á footernum eru linkar sem að taka þig ekki neitt.



## Myndir

Myndir frá:

* [Innkaupakörfu fengin á iconfinder](https://www.iconfinder.com/icons/216460/cart_icon)
* [Aðrar myndir fengnar frá Unsplash](https://unsplash.com/photos/N4QTBfNQ8Nk)

---

> Útgáfa 0.1

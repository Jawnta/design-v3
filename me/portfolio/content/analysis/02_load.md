---
Title: Speedtest
---

Analys av hemsidors laddningstider.
=======================
</br>
</br>

Urval
-----------------------
Vi har valt att använda oss av en kategori till denna analys, resebyråer. 
De hemsidor vi har valt är [Tui](https://www.tui.se/){.paper-links}, [Apollo](https://www.apollo.se/){.paper-links} och [Ving](https://www.ving.se/){.paper-links}. Anledningen till att vi valde kategorin resebyråer är på grund av att dem brukar ha mycket content på sina hemsidor.
</br>
</br>

Metod
-----------------------

Vi använde oss utav [PageSpeed Insights](https://pagespeed.web.dev/){.paper-links} för att få ut en prestandaanalys av varje hemsida. Vi noterade prestandan för hemsidorna i mobilt läge och skrivbordsläge.
Vi tog fram ett medelvärde av hemsidornas laddningstider via devtools i webbläsaren chrome. Vi noterade ner resultaten tre gånger för varje hemsida och tog fram medelvärdet.
Via devtools noterade vi också ner hur mycket resurser som laddas in samt sidornas totala storlek.
</br>
</br>

Resultat
-----------------------

<div class="spreadsheet">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSc8mmHqwq1gZvsBdIy5v-Spg729J5mJnvrnWNYUuD48NzryxZ7I7F-EUxV5zKStSgaJLIKQCslK5jw/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>
</br>
</br>

###Tui
![Tui](../assets/img/tui.png)
Tui hade kunnat reducera laddningstiden genom att inte ladda in onödig javascript som inte används.
</br>
</br>

###Ving
![Ving](../assets/img/ving.png)
Ving hade kunnat reducera laddningstiden genom att inte ladda in onödig javascript som inte används.
</br>
</br>

###Apollo
![Apollo](../assets/img/apollo.png)
Apollo hade kunnat reducera laddningstiden genom att inte ladda in onödig javascript som inte används och använda sig av modernare filformat på sina bilder som t.ex. webp istället för jpeg och png.
</br>
</br>

Analys
-----------------------

Prestandan på mobila enheter är betydligt lägre än i skrivbordsläge för alla hemsidor som vi har analyserat. Av dessa tre hemsidor så har Apollo i snitt bäst score och snabbast laddningstid. På andra plats har vi Ving som hade bäst score i mobilt läge och på sista plats har vi Tui som hade lägst score och överlag den sämsta laddningstiden. Detta betyder dock inte att hemsidan är sämst då den är betydligt större än de andra två.

Vi har kommit fram till att de vanligaste felet som ökar laddningstiden är att mycket javascript laddas in som inte används och bilder inte används i rätt storlek.
</br>
</br>

Referenser
-----------------------

[PageSpeed Insights Tui](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.tui.se%2F){.paper-links}  
[PageSpeed Insights Apollo](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.apollo.se%2F){.paper-links}  
[PageSpeed Insights Ving](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.ving.se%2F){.paper-links}  
[Tui](https://www.tui.se/){.paper-links}  
[Apollo](https://www.apollo.se/){.paper-links}  
[Ving](https://www.ving.se/){.paper-links}  
</br>
</br>

Övrigt
-----------------------

Analys av: Jonatan Robertsson och Andreas Nilsson

---
title: Događaji
subtitle: Organizovanje događaja je važan oblik delovanja
img: events.jpg
---

<%= render '/_events.html', :evclass => 'events_inverse' %>

<div class="row" markdown="1">

![](/images/arrow1.png){: .right}[![](/images/meetup_logo.png){: .left}](http://www.meetup.com/HeapSpace/){: .invisible}
Sva naša okupljanja najavljujemo u okviru
[MeetUp HeapSpace](http://www.meetup.com/HeapSpace/) grupe. Prijave za
okupljanja su **obavezna**. Najlakše je da se uključite u
našu grupu!
{: .12u}

</div>

Učestvujte i <a href="/prijava.html">prijavite</a> vaše prezentacije!


## Tehnološki doručak
{: .stuff}

[Tehnološki doručak](/techdorucak) predstavlja mesečno okupljanje - svake _prve srede_ u mesecu -
sa ciljem brze razmene ideja i znanja među učesnicima, u prijatnoj atmosferi prve
jutarnje kafe.

<% events_old_of_kind('tekfast').each{ |it| %>

<%= render '/_event_small.html', :item => it %>

<%}%>


## Geek Nights
{: .stuff}

[GeekNight](/geeknight) se održava svakog _poslednjeg četvrtka_ u mesecu i
okuplja nas oko predstavljanja tehnološke priorode. Predavanja, paneli, radionice,
ali i više kratkih prezentacija - sva imaju za cilj konkretniju razmenu znanja
i iskustava.

<% events_old_of_kind('talk').each{ |it| %>

<%= render '/_event_small.html', :item => it %>

<%}%>


## Konferencije
{: .stuff}

<a href="https://voxxeddays.com/belgrade15">Voxxed Belgrade 2015</a>
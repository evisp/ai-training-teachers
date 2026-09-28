# Vlerësimi dhe komentet

:material-clipboard-check-outline: 6 prompte për të vlerësuar dhe për të dhënë komente
{ .page-meta }

IA ju ndihmon të përgatitni kuize, rubrika dhe komente shumë më shpejt. Por në vlerësim rregulla është e qartë: **IA përgatit, mësuesi vendos.** Çdo pyetje zgjidhet, çdo koment lexohet dhe çdo notë është e juaja.

!!! warning "Para se të filloni"
    Mos ngjitni kurrë punë me emrin, notat ose të dhënat e nxënësit. Kur ju duhet të vlerësoni një punë, hiqni emrin dhe çdo detaj që e identifikon.

<div class="prompt-card" markdown>

### Kuiz me alternativa

<span class="tag tag--te-gjitha">Të gjitha nivelet</span>

**Kur ta përdorni:** për një kontroll të shpejtë në fund të temës.

```text
Krijo 10 pyetje me 4 alternativa për temën [tema], për klasën e [klasa].
Vetëm një alternativë të jetë e saktë, dhe alternativat e gabuara
të bazohen në gabime që nxënësit bëjnë vërtet.
Në fund shto çelësin e përgjigjeve me një shpjegim të shkurtër.
```

**Vazhdimi:** *"Bëji 3 pyetjet e fundit më të vështira, që kërkojnë arsyetim."*

!!! warning "Kujdes"
    Zgjidhini vetë pyetjet para se t'i përdorni. IA ndonjëherë shënon si të saktë alternativën e gabuar.

</div>

<div class="prompt-card" markdown>

### Pyetje përmbyllëse të orës

<span class="tag tag--te-gjitha">Të gjitha nivelet</span>

**Kur ta përdorni:** në 3 minutat e fundit të orës, për të parë kush e kuptoi dhe kush jo.

```text
Krijo 3 pyetje përmbyllëse për fundin e orës për temën [tema], klasa e [klasa],
që nxënësit i përgjigjen në 3 minuta në një copë letër:
një pyetje për atë që mësuan, një për atë që ende nuk e kuptojnë
dhe një që e lidh temën me jetën e tyre.
```

**Vazhdimi:** *"Si t'i përdor përgjigjet për të planifikuar orën e nesërme?"*

</div>

<div class="prompt-card" markdown>

### Rubrikë vlerësimi

<span class="tag tag--te-gjitha">Të gjitha nivelet</span>

**Kur ta përdorni:** për projekte, ese, prezantime ose punë në grup.

```text
Krijo një rubrikë për [detyra], për klasën e [klasa], me 4 kritere
dhe pikë nga 1 deri në 4. Për çdo pikë shkruaj një përshkrim të shkurtër
e të qartë, që edhe nxënësit ta kuptojnë. Paraqite si tabelë.
```

**Vazhdimi:** *"Rishkruaje rubrikën me fjalë që i kupton një nxënës i klasës së [klasa], për vetëvlerësim."*

</div>

<div class="prompt-card" markdown>

### Draft komentesh për një ese

<span class="tag tag--ulet">I mesëm i ulët</span> <span class="tag tag--larte">I mesëm i lartë</span>

**Kur ta përdorni:** kur keni shumë ese dhe doni një pikënisje për komentet, jo vendimin përfundimtar.

```text
Më poshtë është një ese e një nxënësi të klasës së [klasa], pa emër.
Vlerësoje me rubrikën që të jap dhe shkruaj një koment për nxënësin:
2 pika të forta, 2 gjëra për t'u përmirësuar dhe një hap konkret për herën tjetër.
Toni të jetë inkurajues dhe i sinqertë.

Rubrika: [ngjitni rubrikën]
Eseja: [ngjitni esenë pa emër]
```

!!! warning "Kujdes"
    Lexojeni esenë vetë para se të lexoni komentin e IA-së. IA shpesh është më e butë se mësuesi dhe vë re gabimet gjuhësore më shumë se dobësitë e argumentit. Nota është gjithmonë e juaja.

</div>

<div class="prompt-card" markdown>

### Test nga një kapitull

<span class="tag tag--te-gjitha">Të gjitha nivelet</span> <span class="tag">NotebookLM</span>

**Kur ta përdorni:** kur doni një test që ndjek saktë kapitullin e librit që përdorni.

```text
Nga kapitulli që ngarkova, krijo një test me 10 pyetje për klasën e [klasa]:
6 me alternativa, 3 me përgjigje të shkurtër dhe 1 me zhvillim.
Për çdo pyetje trego pjesën e kapitullit nga vjen
dhe në fund shto çelësin e përgjigjeve.
```

!!! tip "Pa NotebookLM"
    Funksionon edhe në çdo asistent tjetër, nëse ngjitni tekstin e kapitullit pas promptit. NotebookLM ka avantazhin që tregon burimin e çdo pyetjeje. Më shumë te [NotebookLM](../bazat/mjetet-e-ia.md#notebooklm-ia-mbi-materialet-tuaja).

</div>

<div class="prompt-card" markdown>

### Rishkrimi i një detyre në epokën e IA-së

<span class="tag tag--ulet">I mesëm i ulët</span> <span class="tag tag--larte">I mesëm i lartë</span>

**Kur ta përdorni:** kur dyshoni se një detyrë mund të bëhet e tëra me IA në pak minuta.

```text
Kjo është një detyrë që u jap nxënësve të klasës së [klasa]: [detyra].
Rishkruaje që të jetë më e vështirë për t'u kryer tërësisht me IA:
shto një element personal ose lokal, një pjesë që bëhet në klasë
dhe një prezantim të shkurtër me gojë.
Propozo edhe nivelin e përdorimit të IA-së, nga 0 (pa IA) deri në 4 (IA e lirë),
me një fjali arsyetim.
```

<figure class="diagram">
--8<-- "assets/diagrams/shkalla-e-perdorimit.svg"
<figcaption>Shkalla e përdorimit të IA-së. Më shumë te <a href="../../bazat/etika-e-ia/#integriteti-akademik">Integriteti akademik</a>.</figcaption>
</figure>

</div>

<div class="summary" markdown>
<p class="summary__label">Me një fjali</p>

IA përgatit pyetjet, rubrikat dhe komentet; mësuesi i kontrollon dhe merr çdo vendim për notën.

</div>

<div class="next-page" markdown>

**Kategoria tjetër: Komunikimi**

Mesazhe për prindërit, kolegët dhe drejtorinë, me tonin e duhur.

[Vazhdo](komunikimi.md){ .md-button .md-button--primary }

</div>

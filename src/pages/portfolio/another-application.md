---
title: Another Application
subtitle: ''
excerpt: lorem-ipsum
date: '2019-12-19'
template: project
thumb_image: images/teekkarin-sekoilu-seikkailut-thumb.png
image: images/teekkarin-sekoilu-seikkailut.png
---
**Ohjelmointi 3** kurssin aikana tehtiin parityönä peli. Teimme pelin puhtaalta pöydältä täysin itse. Pelissämme *Teekkarin Sekoilu Seikkailut* on ideana viedä ruokaa nälkäisille teekkareille ennen kuin se jäähtyy piloille. Peli toteutettiin Qt:n [Graphics View Frameworkin](https://doc.qt.io/qt-5/graphicsview.html) avulla. Projektin kesto oli 9 viikkoa.

Työskentelyssä harjoiteltiin itsenäisesti **_ketterää ohjelmistokehitystä_**. Meillä oli 1 viikon mittainen sprintti/iteraatio ja joka viikon alussa käytiin läpi mitä oltiin saatu aikaseksi viime viikolla(retro) ja mitä tavoitellaan seuraavalta viikolta (planning). Backlogi oli myös käytössä, johon määriteltiin ominaisuuksia pelin muodostuessa.

Trelloa käytettiin hyväksi **_työskentelyn suunnitteluun ja työskentelyn seuraamiseen_**. Tauluina olivat jokaiselle iteraatiolle TODO, DOING, DONE ja RETRO. Tämän lisäksi backlog oli omana taulunansa. Puolivälissä projektia tehtiin myös Possible Features taulu, johon listattiin ideoita mitä saatettiin ottaa backlogiin.

**_[Linkki trelloon](https://trello.com/b/fkITJ1GB)_**, josta löytyy kollaasi jokaisen iteraation DONE ja RETRO tauluista ja tietysti myös tyhjä backlog. Bonuksena myös Possible Features taulu.

**_Branchejä_** käytettiin hyväksi versionhallinnassa. Aluksi oli tapana tehdä oma bränchinsä jokaiselle uudelle ominaisuudelle, mutta ihan projektin viimeisellä viikolla ryhdyin käyttämään devT bränchiä, jossa tein ominaisuudet, jotka sitten mergettiin masteriin.

Aluksi tehtiin **_prototyyppi_**, jossa vaatimuksina oli pelaajan liikkuminen pysäkiltä toisille bussien avulla. Ekat pari viikkoa tuli luettua dokumentaatiota lähinnä [Graphics Itemin](https://doc.qt.io/qt-5/qgraphicsitem.html) käytöstä [Graphics Scenen](https://doc.qt.io/qt-5/qgraphicsscene.html) kanssa.

Prototyypin jälkeen saatiin idea tehdä **_ruuankuljetuspeli_**, jota tehtiin viikko kerrallaan. Tavoitteena oli saada peruspeli valmiiksi.

Alla näkyy ohjelman luokkakaavio. Signaalit edustavat Qt:n [Signals & Slots](https://doc.qt.io/qt-5/signalsandslots.html) mekanismia.

![Luokkakaavio](/images/luokkakaavio.png)

Lisätietoja projektista [Gitistä](https://github.com/Temez1/ohj3-projekti)
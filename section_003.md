# Basisindeling plannen, visies en besluiten {#6CD31C9F}

In dit hoofdstuk is voor de drie verschillende groepen ruimtelijke instrumenten de volgorde in planteksten aangegeven met behulp van tabellen. Elk TekstObject is benoemd onder de kolom objectType. Hoeveel keer het TekstObject mag voorkomen is aangegeven in de kolom Aantal. Tot slot is in de kolom “Mag voorkomen onder” aangegeven onder welk TekstObject dit TekstObject kan vallen.<br/>
## Basisindeling plannen {#6CD31CA1}

Voor een bestemmingsplan, beheersverordening, inpassingsplan, rijksbestemmingsplan, wijzigingsplan en uitwerkingsplan kan de plantekst op een vaste wijze worden ingedeeld. Planteksten voor deze groep plannen kan in eerste plaats worden verdeeld in regels, bijlagen bij regels, toelichting, bijlagen bij toelichting. Ieder van deze onderdelen wordt verdeeld in hoofdstukken, paragrafen et cetera. De <a href='https://docs.geostandaarden.nl/ro/svbp' target='_blank'>SVBP2012</a> schrijft de indeling van de hoofdstukken en paragrafen van de regels voor. Figuur 3 geeft de indeling voor de regels conform de SVBP2012. In de volgende tabellen wordt de indeling gegeven voor de bijlagen bij de regels (<a href='#T006'>Tabel 6</a>), toelichting (<a href='#T007'>Tabel 7</a>) en de bijlagen bij de toelichting (<a href='#T008'>Tabel 8</a>). In afwijking van deze tabellen mogen bijlagen ook beschikbaar gesteld worden in separate bronbestanden conform <a href='https://docs.geostandaarden.nl/ro/stri' target='_blank'>STRI2012</a>.<br/>
<figure><img src='media/hierarchie_objecttypen.jpg' alt='Afbeelding met de getrapte hiërarchie van de objecttypen bij planteksten.' style='width: 81.32071115215885%;'></img>
<figcaption>Hiërarchie objecttypen bij planteksten</figcaption></figure>

<table style='width: 100%;' id='T006'><caption>Tabel 6 Basisindeling planteksten plannen: bijlagen bij regels</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen bij regels<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>document, regels<br/>
</td>
</tr>
<tr><td align='left'>bijlage bij regels<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen bij regels<br/>
</td>
</tr>
<tr><td align='left'>deel <br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij regels<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij regels, Deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T007'><caption>Tabel 7 Basisindeling planteksten plannen: toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>toelichting<br/>
</td>
<td align='left'>1<br/>
</td>
<td align='left'>document<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T008'><caption>Tabel 8 Basisindeling planteksten plannen: bijlagen bij toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen bij toelichting<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>document, toelichting<br/>
</td>
</tr>
<tr><td align='left'>bijlage bij toelichting<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen bij toelichting<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

## Basisindeling Visies {#6CD31E7C}

Structuurvisies kennen in vergelijking met de plannen een vrijere basisindeling. Planteksten voor deze groep visies kan in eerste plaats worden verdeeld in beleidstekst, bijlagen, toelichting, bijlagen bij toelichting. Ieder van deze onderdelen wordt verdeeld in hoofdstukken, paragrafen et cetera. <a href='#T009'>Tabel 9</a> geeft de indeling voor de beleidstekst. In de volgende tabellen wordt de indeling gegeven voor de bijlagen (<a href='#T010'>Tabel 10</a>), toelichting (<a href='#T011'>Tabel 11</a>) en de bijlagen bij de toelichting (<a href='#T012'>Tabel 12</a>). In afwijking van onderstaande tabellen mogen bijlagen ook beschikbaar gesteld worden in separate bronbestanden conform <a href='https://docs.geostandaarden.nl/ro/stri' target='_blank'>STRI2012</a>.<br/>
<table style='width: 100%;' id='T009'><caption>Tabel 9 Basisindeling planteksten visies: beleidstekst</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>document<br/>
</td>
<td align='left'>1<br/>
</td>
<td align='left'></td>
</tr>
<tr><td align='left'>beleidstekst<br/>
</td>
<td align='left'>1<br/>
</td>
<td align='left'>document<br/>
</td>
</tr>
<tr><td align='left'>band<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>beleidstekst<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>beleidstekst, band<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>beleidstekst, band, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>hoofdstuk</span><br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T010'><caption>Tabel 10 Basisindeling planteksten visies: bijlagen</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>document, beleidstekst<br/>
</td>
</tr>
<tr><td align='left'>bijlage<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen<br/>
</td>
</tr>
<tr><td align='left'>deel <br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T011'><caption>Tabel 11 Basisindeling planteksten visies: toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'><b>Toegestane Bovenliggende objecten</b><br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>toelichting<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>document<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T012'><caption>Tabel 12 Basisindeling planteksten visies: bijlagen bij toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'><b>Toegestane Bovenliggende objecten</b><br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen bij toelichting<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>document<br/>
</td>
</tr>
<tr><td align='left'>bijlage bij toelichting<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen bij toelichting<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting, deel, hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf<br/>
</td>
</tr>
</tbody>
</table>

## Basisindeling Besluiten {#6CD31F2F}

Besluiten kennen in vergelijking met de plannen een vrijere basisindeling. Planteksten voor deze groep besluiten kunnen in eerste plaats worden verdeeld in besluittekst, bijlagen, toelichting, bijlagen bij toelichting. Ieder van deze onderdelen wordt verdeeld in hoofdstukken, paragrafen et cetera. <a href='#T013'>Tabel 13</a> geeft de indeling voor de besluittekst. In de volgende tabellen wordt de indeling gegeven voor de bijlagen (<a href='#T014'>Tabel 14</a>), regels (<a href='#T015'>Tabel 15</a>), bijlagen bij regels (<a href='#T016'>Tabel 16</a>), toelichting (<a href='#T017'>Tabel 17</a>) en bijlagen bij de toelichting (<a href='#T018'>Tabel 18</a>). In afwijking van onderstaande tabellen mogen bijlagen ook beschikbaar gesteld worden in separate bronbestanden conform <a href='https://docs.geostandaarden.nl/ro/stri' target='_blank'>STRI2012</a>.<br/>
<table style='width: 100%;' id='T013'><caption>Tabel 13 Basisindeling planteksten besluiten: besluittekst</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>besluitdocument<br/>
</td>
<td align='left'>1<br/>
</td>
<td align='left'></td>
</tr>
<tr><td align='left'>besluittekst<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>besluitdocument<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>besluittekst</span><br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>besluittekst, deel</span><br/>
</td>
</tr>
<tr><td align='left'>titel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>hoofdstuk</span><br/>
</td>
</tr>
<tr><td align='left'>afdeling<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>titel</span><br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>besluittekst, hoofdstuk, titel, afdeling</span><br/>
</td>
</tr>
<tr><td align='left'>artikel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>besluittekst, hoofdstuk, paragraaf<br/>
</td>
</tr>
<tr><td align='left'>lid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>artikel<br/>
</td>
</tr>
<tr><td align='left'>onderdeel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>lid<br/>
</td>
</tr>
<tr><td align='left'>subonderdeel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>onderdeel<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>besluittekst, deel, hoofdstuk, titel, afdeling, paragraaf, artikel, lid, onderdeel, subonderdeel, overig<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T014'><caption>Tabel 14 Basisindeling planteksten besluiten: bijlagen</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>besluitdocument<br/>
</td>
</tr>
<tr><td align='left'>bijlage<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage, hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage, deel, hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf, overig<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T015'><caption>Tabel 15 Basisindeling planteksten besluiten: regels</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>regels<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>besluitdocument<br/>
</td>
</tr>
<tr><td align='left'>titel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>regels<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>regels, titel<br/>
</td>
</tr>
<tr><td align='left'>artikel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>regels, titel, hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>lid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>artikel<br/>
</td>
</tr>
<tr><td align='left'>sublid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>lid<br/>
</td>
</tr>
<tr><td align='left'>subsublid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>sublid<br/>
</td>
</tr>
<tr><td align='left'>subsubsublid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsublid<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, artikel, lid, sublid, subsublid, subsubsublid, overig<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T016'><caption>Tabel 16 Basisindeling planteksten besluiten: bijlagen bij regels</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen bij regels<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>besluitdocument, regels<br/>
</td>
</tr>
<tr><td align='left'>bijlage bij regels<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen bij regels<br/>
</td>
</tr>
<tr><td align='left'>deel <br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij regels<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij regels, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf, overig<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T017'><caption>Tabel 17 Basisindeling planteksten besluiten: toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>toelichting<br/>
</td>
<td align='left'>1<br/>
</td>
<td align='left'>besluitdocument<br/>
</td>
</tr>
<tr><td align='left'>deel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, Deel<br/>
</td>
</tr>
<tr><td align='left'>titel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>hoofdstuk</span><br/>
</td>
</tr>
<tr><td align='left'>afdeling<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'><span style='color: #000000;'>titel</span><br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, hoofdstuk, titel, afdeling<br/>
</td>
</tr>
<tr><td align='left'>artikel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, hoofdstuk, paragraaf<br/>
</td>
</tr>
<tr><td align='left'>lid<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>artikel<br/>
</td>
</tr>
<tr><td align='left'>onderdeel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>lid<br/>
</td>
</tr>
<tr><td align='left'>subonderdeel<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>onderdeel<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>toelichting, deel, hoofdstuk, titel, afdeling, paragraaf, artikel, lid, onderdeel, subonderdeel, subparagraaf, subsubparagraaf, subsubsubparagraaf, overig<br/>
</td>
</tr>
</tbody>
</table>

<table style='width: 100%;' id='T018'><caption>Tabel 18 Basisindeling planteksten besluiten: bijlagen bij toelichting</caption>
<colgroup><col id='col1' style='width: 38.09203896540141%;'>
<col id='col2' style='width: 9.528608218564552%;'>
<col id='col3' style='width: 52.37935281603404%;'>
</colgroup>
<thead valign='top'><tr><th align='left'>objectType<br/>
</th>
<th align='left'>Aantal<br/>
</th>
<th align='left'>Mag voorkomen onder<br/>
</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left'>bijlagen bij toelichting<br/>
</td>
<td align='left'>0..1<br/>
</td>
<td align='left'>besluitdocument<br/>
</td>
</tr>
<tr><td align='left'>bijlage bij toelichting<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlagen bij toelichting<br/>
</td>
</tr>
<tr><td align='left'>deel <br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting<br/>
</td>
</tr>
<tr><td align='left'>hoofdstuk<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting, deel<br/>
</td>
</tr>
<tr><td align='left'>paragraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>hoofdstuk<br/>
</td>
</tr>
<tr><td align='left'>subparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>paragraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subparagraaf<br/>
</td>
</tr>
<tr><td align='left'>subsubsubparagraaf<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>subsubparagraaf<br/>
</td>
</tr>
<tr><td align='left'>overig<br/>
</td>
<td align='left'>0..n<br/>
</td>
<td align='left'>bijlage bij toelichting, deel, hoofdstuk, paragraaf, subparagraaf, subsubparagraaf, subsubsubparagraaf, overig<br/>
</td>
</tr>
</tbody>
</table>


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Во следната задача треба да изградите бинарно дрво со N јазли, за кое ќе треба да одговорите на Q прашања од видот „колку јазли со точно две деца има во поддрвото на избран јазол“.

Секој јазол ќе има уникатно име. Името на коренот на дрвото секогаш ќе ви биде дадено прво. 

Влезот ќе содржи N+Q редови од видот

	-root ime - Треба да го поставите коренот на дрвото да биде јазелот со име ime

	-add parent_name child_name - Треба да додадете дете јазел со име child_name на јазелот со име parent_name

	-ask node_name - Треба да го одговориме прашањето за поддрвото на јазелот со име node_name

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| Input | Result |
|-------|--------|
| <div align="left">11 9<br>root bravo<br>add bravo echo LEFT<br>add echo beard LEFT<br>ask beard<br>ask bravo<br>add bravo foxtrot RIGHT<br>add beard hotel LEFT<br>add beard india RIGHT<br>ask echo<br>add foxtrot golf LEFT<br>add golf juliet RIGHT<br>add india sierra RIGHT<br>ask foxtrot<br>ask bravo<br>ask beard<br>add echo mike RIGHT<br>add foxtrot tango RIGHT<br>ask echo<br>ask bravo<br>ask foxtrot</div> | <div align="left">0<br>0<br>1<br>0<br>2<br>1<br>2<br>4<br>1</div> |






Објаснување: 

	Прикажано е изгледот на дрвото при секоја од 4те групи прашања во влезот
	
| | | | | 
|---|---|---|---|
| <img src="https://github.com/petrovskys/APS2025/blob/f89ed4c418bb9ab27d52fa1b4f58c8ab42c6aa72/Trees/Drva_Zadaca_3/Sliki/1.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/f89ed4c418bb9ab27d52fa1b4f58c8ab42c6aa72/Trees/Drva_Zadaca_3/Sliki/1.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/f89ed4c418bb9ab27d52fa1b4f58c8ab42c6aa72/Trees/Drva_Zadaca_3/Sliki/1.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/f89ed4c418bb9ab27d52fa1b4f58c8ab42c6aa72/Trees/Drva_Zadaca_3/Sliki/1.png?raw=true" width="200" height="300" /> |

| Input | Result |
|-------|--------|
| <div align="left">12 19<br>root oscar<br>add oscar kilo LEFT<br>add kilo charlie RIGHT<br>add oscar zulu RIGHT<br>ask oscar<br>ask kilo<br>ask charlie<br>ask zulu<br>add kilo victor LEFT<br>add charlie romeo RIGHT<br>add zulu lima RIGHT<br>add victor delta LEFT<br>add delta alpha LEFT<br>ask oscar<br>ask kilo<br>ask charlie<br>ask zulu<br>ask victor<br>ask romeo<br>ask lima<br>ask delta<br>ask alpha<br>add victor uniform RIGHT<br>add zulu papa LEFT<br>ask kilo<br>add romeo quebec LEFT<br>ask oscar<br>ask kilo<br>ask charlie<br>ask zulu<br>ask victor</div> | <div align="left">1<br>0<br>0<br>0<br>2<br>1<br>0<br>0<br>0<br>0<br>0<br>0<br>0<br>2<br>4<br>2<br>0<br>1<br>1</div> |



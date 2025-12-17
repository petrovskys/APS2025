-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Во следната задача треба да изградите неподредено (општо) дрво со N јазли, за кое ќе треба да одговорите на Q прашања од видот „колку лисја има поддрвото на избран јазол“.

Секој јазол ќе има уникатен индекс од 1 до N. Коренот на дрвото секогаш ќе има индекс 1. Сите деца ќе имаат индекси поголеми од индексите на родителите.

Влезот ќе содржи N+Q редови од видот:

  -root 1 - Треба да го поставите коренот на дрвото да биде јазелот со индекс 1

  -add parent_index child_index - Треба да додадете дете јазел со индекс child_index на јазелот со индекс parent_index

  -ask node_index - Треба да одговорите колку листови има во поддрвото на јазелот со индекс node_index

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| Input | Result |
|-------|--------|
| <div align="left">11 5<br>root 1<br>add 1 2<br>add 2 3<br>ask 1<br>add 1 4<br>add 2 5<br>add 3 6<br>ask 2<br>add 3 7<br>ask 1<br>add 1 8<br>add 4 9<br>add 2 10<br>add 4 11<br>ask 2<br>ask 1</div> | <div align="left">1<br>2<br>4<br>4<br>7</div> |





Објаснување: 

	прашање 1: ask 1: Во поддрвото на јазелот 1 има 1 лист.
	прашање 2: ask 2: Во поддрвото на јазелот 2 има 2 листови.
	прашање 3: ask 1: Во поддрвото на јазелот 1 има 4 листови.
	прашање 4: ask 2: Во поддрвото на јазелот 2 има 4 листови
	прашање 5: ask 1: Во поддрвото на јазелот 1 има 7 листови
	
| | | | | |
|---|---|---|---|---|
| <img src="https://github.com/petrovskys/APS2025/blob/92ee5ef90c83e378c7f40811ab0285910540c1ec/Trees/Drva_Zadaca_1/Sliki/1.PNG?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/92ee5ef90c83e378c7f40811ab0285910540c1ec/Trees/Drva_Zadaca_1/Sliki/2.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/92ee5ef90c83e378c7f40811ab0285910540c1ec/Trees/Drva_Zadaca_1/Sliki/3.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/92ee5ef90c83e378c7f40811ab0285910540c1ec/Trees/Drva_Zadaca_1/Sliki/4.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/92ee5ef90c83e378c7f40811ab0285910540c1ec/Trees/Drva_Zadaca_1/Sliki/5.png?raw=true" width="200" height="300" /> |

| Input | Result |
|-------|--------|
| <div align="left">12 18<br>root 1<br>add 1 2<br>add 2 3<br>add 1 4<br>ask 1<br>ask 2<br>ask 3<br>ask 4<br>add 2 5<br>add 1 6<br>add 4 7<br>add 5 8<br>add 8 9<br>ask 1<br>ask 2<br>ask 3<br>ask 4<br>ask 5<br>ask 6<br>ask 7<br>ask 8<br>ask 9<br>add 5 10<br>add 4 11<br>add 2 12<br>ask 1<br>ask 2<br>ask 3<br>ask 4<br>ask 5</div> | <div align="left">2<br>1<br>1<br>1<br>4<br>2<br>1<br>1<br>1<br>1<br>1<br>1<br>1<br>7<br>4<br>1<br>2<br>2</div> |




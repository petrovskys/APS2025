-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Дадено ви е бинарно пребарувачко дрво со N цели броеви.

Напишете функција со која за бинарно пребарувачко дрво и избран елемент Т од дрвото:

	-ќе најдете колку елементи во дрвото се поголеми од T
Ќе треба да ја искористите таа функција Q пати при градењето на дрвото.

Влезот ќе содржи N+Q редови од видот 

	-insert value - Треба да ја вметнете вредноста value во дрвото.

	-ask value - Треба да одговорите колку елементи во дрвото имаат вредност поголема од value

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| Input | Result |
|-------|--------|
| <div align="left">10 7<br>insert 6<br>insert 3<br>insert 7<br>ask 3<br>ask 6<br>insert 4<br>insert 1<br>insert 2<br>insert 5<br>insert 9<br>ask 3<br>ask 9<br>insert 8<br>insert 10<br>ask 8<br>ask 4<br>ask 5</div> | <div align="left">2<br>1<br>5<br>0<br>2<br>6<br>5</div> |





Објаснување: 

	Прикажано е изгледот на дрвото при секое од 7те прашања во влезот
	
| | | |  
|---|---|---|
| <img src="https://github.com/petrovskys/APS2025/blob/61948c11a64db4eb894086385e28c580d8f0f413/Trees/Drva_Zadaca_6/Sliki/1.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/61948c11a64db4eb894086385e28c580d8f0f413/Trees/Drva_Zadaca_6/Sliki/2.png?raw=true" width="200" height="300" /> | <img src="https://github.com/petrovskys/APS2025/blob/61948c11a64db4eb894086385e28c580d8f0f413/Trees/Drva_Zadaca_6/Sliki/3.png?raw=true?raw=true" width="200" height="300" /> |

| Input | Result |
|-------|--------|
| <div align="left">19 13<br>insert 92<br>insert 95<br>insert 85<br>insert 77<br>ask 95<br>ask 85<br>ask 77<br>insert 47<br>insert 31<br>insert 32<br>insert 52<br>insert 50<br>ask 92<br>ask 95<br>ask 47<br>ask 52<br>insert 76<br>insert 99<br>insert 29<br>insert 41<br>insert 11<br>insert 91<br>insert 38<br>ask 85<br>ask 76<br>ask 38<br>insert 21<br>insert 17<br>insert 28<br>ask 95<br>ask 29<br>ask 28</div> | <div align="left">0<br>2<br>3<br>1<br>0<br>6<br>4<br>4<br>6<br>11<br>1<br>14<br>15</div> |

| Input | Result |
|-------|--------|
| <div align="left">81 66<br>insert 44<br>insert 90<br>insert 37<br>insert 100<br>insert 16<br>ask 16<br>insert 82<br>ask 82<br>insert 9<br>ask 9<br>insert 5<br>ask 5<br>ask 16<br>insert 49<br>ask 49<br>ask 82<br>insert 20<br>ask 20<br>ask 9<br>insert 4<br>ask 4<br>ask 5<br>insert 10<br>ask 10<br>ask 49<br>insert 71<br>ask 71<br>ask 20<br>insert 66<br>ask 66<br>ask 4<br>insert 45<br>ask 45<br>ask 10<br>insert 63<br>ask 63<br>ask 71<br>insert 48<br>ask 48<br>ask 66<br>insert 35<br>ask 35<br>ask 45<br>insert 72<br>ask 72<br>ask 63<br>insert 79<br>ask 79<br>ask 48<br>insert 80<br>ask 80<br>ask 35<br>insert 2<br>ask 2<br>ask 72<br>insert 74<br>ask 74<br>ask 79<br>insert 59<br>ask 59<br>ask 80<br>insert 75<br>ask 75<br>ask 2<br>insert 70<br>ask 70<br>ask 74<br>insert 98<br>ask 98<br>ask 59<br>insert 27<br>ask 27<br>ask 75<br>insert 1<br>ask 1<br>ask 70<br>insert 93<br>insert 78<br>ask 98<br>insert 40<br>insert 43<br>ask 27<br>insert 69<br>insert 94<br>ask 1<br>insert 61<br>insert 12<br>insert 64<br>insert 87<br>insert 51<br>insert 24<br>ask 24<br>insert 73<br>insert 84<br>insert 13<br>insert 26<br>ask 90<br>ask 10<br>ask 2<br>ask 78<br>ask 51<br>ask 26<br>insert 15<br>insert 14<br>insert 58<br>insert 33<br>insert 3<br>insert 67<br>insert 53<br>insert 42<br>insert 8<br>insert 81<br>insert 23<br>insert 22<br>insert 30<br>insert 25<br>insert 62<br>insert 88<br>insert 65<br>insert 86<br>insert 97<br>insert 18<br>insert 55<br>insert 39<br>insert 83<br>insert 34<br>insert 36<br>insert 56<br>insert 7<br>insert 60<br>insert 19<br>insert 6<br>insert 57<br>insert 89<br>insert 68<br>insert 96<br>insert 54<br>insert 46<br>ask 100<br>ask 10<br>ask 70<br>ask 40<br>ask 73<br>ask 67<br>ask 86<br>ask 19<br>ask 46</div> | <div align="left">4<br>2<br>6<br>7<br>5<br>3<br>2<br>6<br>8<br>10<br>9<br>8<br>3<br>3<br>7<br>4<br>13<br>6<br>11<br>5<br>3<br>7<br>4<br>11<br>8<br>3<br>6<br>3<br>9<br>3<br>14<br>21<br>5<br>5<br>4<br>10<br>3<br>5<br>24<br>9<br>6<br>1<br>13<br>20<br>6<br>28<br>10<br>1<br>24<br>34<br>31<br>4<br>39<br>43<br>10<br>23<br>33<br>0<br>71<br>23<br>49<br>20<br>26<br>10<br>64<br>44</div> |





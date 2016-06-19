# Real-Madrid-data-mining

The project aims to get insights from the matches Real Madrid played in the Spanish league *La Liga* during the 2015-16 season.

## DATABASE

The database consolidates information from the 38 matches played during the 2015-16 season.  

Won	| Opponent	| Table Pos	| Local |	Goals For	| Goals Against	| Manager	| Keylor Navas	| Casilla	| Varane	| Sergio Ramos	| Marcelo	| Danilo	| Carvajal	| Pepe	| Arbeloa	| Nacho	| Kovacic	| Kroos	| Modric	| Isco	| James	| Casemiro	| Lucas Vázquez	| Bale	| Cristiano	| Benzema	| Jesé	| Mayoral	| Cheryshev	| Marcos Llorente
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
1	|Barcelona	|1	|0	|2	|1	|Zidane	|GK0	|	|	|DF0	|DF0	|	|DF0	|DF0	|	|	|	|MD0	|MD0	|	|	|MD0	|FW1	|FW0	|FW0	|FW0	|FW1		
1	|Eibar	|14	|1	|4	|0	|Zidane	|	|GK0	|	|	|	|DF1	|DF0	|DF0	|DF0	|DF0	|MD1	|	|	|MD0	|MD0	|MD0	|MD0	|	|FW0	|	|FW0	|FW1	
1	|Getafe	|19	|0	|5	|1	|Zidane	|GK0	|	|DF0	|	|DF0	|	|DF0	|DF0	|	|DF1	|	|MD0	|	|MD0	|MD0	|	|FW1	|FW0	|FW0	|FW0	|FW1		
1	|Villareal	|4	|1	|3	|0	|Zidane	|GK0	|	|DF0	|DF0	|DF0	|DF0	|	|	|	|	|	|MD0	|MD0	|MD1	|MD1	|MD0	|MD0	|	|FW0	|FW0	|MD1
1	|Rayo	|18	|0	|3	|2	|Zidane	|GK0	|	|DF0	|	|DF0	|DF0	|	|DF0	|	|	|MD0	|MD0	|FW1	|MD0	|MD1	|	|FW1	|FW0	|	|FW0	|FW0	|	|	

- Won: If Real Madrid won the match (doesn`t count draws)
- Opponent: The opponent team
- Table Pos: Position of the opponent team in the classification table at the end of the season (2015-2016)
- Local:	Whether Real Madrid played at home or away
- Goals For: Goals scored by Real Madrid	
- Goals Against: Goals scored by the opponent team
- Manager: Real Madrid manager. Benitez or Zidane
- _\<Player\>_: The position of the player in the field and whether they played as starters or substitutes.

The position of the player is defined as follows:
* GK Goalkeeper
* DF Defender
* MD Midfielder
* FW Forward
* 0 Starter
* 1 Substitute

The database was taken and adapted from: http://resultados.as.com/resultados/futbol/primera/2015_2016/calendario

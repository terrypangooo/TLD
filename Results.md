# Performance evaluation on TLD dataset measured by Precision / Recall / F-measure

Sequence      |Frames	|OpenTLD(MatLab)           | # 2 | # 3 | # 4 | # 5
:-----:       |:-----:	|:-----------:  	| :-----------: | : --: | :--: | :--:
1.David      |761 	|**1.00 / 1.00 / 1.00**|0.99 / 0.99 / 0.99|**1.00 / 1.00 / 1.00**|BAD|0.99 / 0.99 / 0.99
2.Jumping    |313 	|**1.00 / 1.00 / 1.00**|0.85 / 0.85 / 0.85|0.92 / 0.92 / 0.92|0.79 / 0.88 / 0.83|1.00 / 0.996 / 0.998
3.Pedestrian 1|140	|**1.00 / 1.00 / 1.00**|0.52 / 0.42 / 0.47|0.68 / 0.55 / 0.61|1.00 / 0.65 / 0.79|1.00 / 0.99 / 0.996
4.Pedestrian 2|338	|0.89 / 0.92 / 0.91|0.47 / 0.41 / 0.44|1.00 / 0.30 / 0.46|-|**0.93 / 0.97 / 0.95**
5.Pedestrian 3|184	|**0.99 / 1.00 / 0.99**|1.00 / 0.41 / 0.58|1.00 / 0.42 / 0.59|-|0.97 / 0.50 / 0.66
6.Car		|945	|0.92 / 0.97 / 0.94		|0.92 / 0.99 / 0.95|**0.94 / 0.98 / 0.96**|0.92 / 0.99 / 0.95|0.93 / 0.97 / 0.95
7.Motocross	|2665	|**0.89 / 0.77 / 0.83**| - | - | - | 0.72 / 0.84 / 0.78
8.Volkswagen|8576	|**0.80 / 0.96 / 0.87**| - | - | - | 0.76 / 0.96 / 0.85 [^1]
9.Carchase	|9928	|**0.86 / 0.70 / 0.77**| - | - | - | -
10.Panda	|3000	|**0.58 / 0.63 / 0.60**| - | - | - | 0.49 / 0.53 / 0.51

[^1]: This is not the latest result. (Runned with small size of NN examples set)
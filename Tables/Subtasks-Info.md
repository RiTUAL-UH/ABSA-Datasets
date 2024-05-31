# Subtasks Info

[back to README.md](../README.md)

This table gives a list of all the introduced Subtasks of ABSA since its evolution. 
If you want to add any new tasks or change any information, please create a fork of the master repository and create a pull request, so that we can verify it and commit the change.

| **Index** 	| **Year** 	|      **Paper**      	|            **CommonName**           	| **Acronym** 	|                                     **Input**                                    	|                               **ExpectedOutput**                              	|
|:---------:	|:--------:	|:-------------------:	|:-----------------------------------:	|:-----------:	|:--------------------------------------------------------------------------------:	|:-----------------------------------------------------------------------------:	|
|        12 	|     2021 	| Zhang etal., 2021a  	| Aspect Sentiment QuadPrediction     	| ASQP        	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, Food, positive, very yummy), (place, Ambience, negative, weird smell) 	|
|        11 	|     2019 	| Fan etal., 2019     	| Target Opinion Word Extraction      	| TOWE        	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, very yummy), (place, weird smell)                                     	|
|        10 	|     2020 	| Wan etal., 2020     	| Target Aspect Sentiment Detection   	| TASD        	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, Food, positive), (place, Ambience, negative)                          	|
|         9 	|     2020 	| Peng etal., 2020    	| Aspect Sentiment Triplet Extraction 	| ASTE        	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, very yummy, positive), (place, weird smell, negative)                 	|
|         8 	|     2018 	| Li etal., 2018      	| Target Sentiment Joint Detection    	| TSD         	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, positive), (place, negative)                                          	|
|         7 	|     2018 	| Schmitt etal., 2018 	| Aspect Sentiment Joint Detection    	| ASD         	| "The pasta was very yummy but the place has some weird smell."                   	| (Food, positive), (Ambience, negative)                                        	|
|         6 	|     2014 	| Pontiki etal., 2014 	| Target Aspect Detection             	| TAD         	| "The pasta was very yummy but the place has some weird smell."                   	| (pasta, Food), (place, Ambience)                                              	|
|         5 	|     2015 	| Pontiki etal., 2015 	| Target Detection                    	| TD          	| "The pasta was very yummy but the place has some weird smell."                   	| pasta, place                                                                  	|
|         4 	|     2015 	| Pontiki etal., 2014 	| Aspect Category Sentiment Analysis  	| ACSA        	| "The pasta was very yummy but the place has some weird smell.", (Food, Ambience) 	| positive, negative                                                            	|
|         3 	|     2014 	| Pontiki etal., 2014 	| Aspect Category Detection           	| ACD         	| "The pasta was very yummy but the place has some weird smell."                   	| Food, Ambience                                                                	|
|         2 	|     2004 	| Hu and Liu, 2004a   	| Aspect Term Sentiment Analysis      	| ATSA        	| "The pasta was very yummy but the place has some weird smell.", (pasta, place)   	| positive, negative                                                            	|
|         1 	|     2004 	| Hu and Liu, 2004a   	| Aspect Term Extraction              	| ATE         	| "The pasta was very yummy but the place has some weird smell."                   	| pasta, place                                                                  	|

[back to README.md](../README.md)

# V0.5 #


Additions in this version of the project:
User now has an option to choose between existing or generated files.
Added table of analysed timers of each program.
Updated algorithm of division point search.

## Usage ##
 Every folder contains independent program with different data structures.
 
 _v04.cpp_ file has the main function.
 _v04funkcijos.cpp_ file has the functions used in main.
 _generator.cpp_ file has the function to generate new files.
 _antrastes.h_ file has prototypes of functions and used directories.
 _analize.cpp_ file has the function for analysing programs work.

## Program Testing ##

Number of grades: 5;

   #### Duomenų nuskaitymas

  | Student count | Data structure   	| Time (s)   	|
  |--------------	|------------------	|------------	|
  | 1000         	| Vector           	| 0.008703    |
  |              	| Deque            	| 0.007113   	|
  |              	| List             	| 0.027285   	|
  |              	|                  	|            	|
  | 10000        	| Vector           	| 0.041365  	 |
  |              	| Deque            	| 0.03226    	|
  |              	| List             	| 0.059282  	 |
  |              	|                  	|            	|
  | 100000       	| Vector           	| 0.287954   	|
  |              	| Deque            	| 0.291207 	  |
  |              	| List             	| 0.37059  	  |
  |              	|                  	|            	|
  | 1000000      	| Vector           	| 2.8036  	   |
  |              	| Deque            	| 2.87365  	  |
  |              	| List             	|  3.28074   	|
  |              	|                  	|            	|
  | 10000000     	| Vector           	| 28.761  	   |
  |              	| Deque            	| 42.2874  	  |
  |              	| List             	| 34.9019    	|

  #### Dalijimas i dvi dalis
  
  | Įrašų kiekis 	| Duomenų strukūra 	| Trukmė (s) 	|
  |--------------	|------------------	|------------	|
  | 1000         	| Vector           	| 0.002305   	|
  |              	| Deque            	|  0.005348  	|
  |              	| List             	| 0.000718   	|
  |              	|                  	|            	|
  | 10000        	| Vector           	| 0.017539   	|
  |              	| Deque            	| 0.048986   	|
  |              	| List             	| 0.00885  	  |
  |              	|                  	|            	|
  | 100000       	| Vector           	| 0.204198   	|
  |              	| Deque            	| 0.542224   	|
  |              	| List             	| 0.129268  	 |
  |              	|                  	|            	|
  | 1000000      	| Vector           	|2.56121  	   |
  |              	| Deque            	| 7.26168  	  |
  |              	| List             	| 1.47823  	  |
  |              	|                  	|            	|
  | 10000000     	| Vector           	| 30.5022    	|
  |              	| Deque            	| 49.2346  	  |
  |              	| List             	| 20.2182  	  |

  #### Levekai isvedimas
  
  | Įrašų kiekis 	| Duomenų strukūra 	| Trukmė (s) 	|
  |--------------	|------------------	|------------	|
  | 1000         	| Vector           	| 0.017916 	  |
  |              	| Deque            	| 0.010466  	 |
  |              	| List             	| 0.006007    |
  |              	|                  	|            	|
  | 10000        	| Vector           	| 0.035988  	 |
  |              	| Deque            	| 0.047747  	 |
  |              	| List             	| 0.047978  	 |
  |              	|                  	|            	|
  | 100000       	| Vector           	| 0.419225   	|
  |              	| Deque            	| 0.421703 	  |
  |              	| List             	| 0.12926  	  |
  |              	|                  	|            	|
  | 1000000      	| Vector           	| 2.91622     |
  |              	| Deque            	| 3.19607    	|
  |              	| List             	| 3.40588    	|
  |              	|                  	|            	|
  | 10000000     	| Vector           	| 26.9167    	|
  |              	| Deque            	| 28.6852  	  |
  |              	| List             	| 29.7182    	|

  #### Ketekai isvedimas
  
  | Įrašų kiekis 	| Duomenų strukūra 	| Trukmė (s) 	|
  |--------------	|------------------	|------------	|
  | 1000         	| Vector           	| 0.006318  	 |
  |              	| Deque            	|  0.010766  	|
  |              	| List             	| 0.048581  	 |
  |              	|                  	|            	|
  | 10000        	| Vector           	| 0.03809  	  |
  |              	| Deque            	| 0.046056   	|
  |              	| List             	| 0.048581   	|
  |              	|                  	|            	|
  | 100000       	| Vector           	| 0.28657    	|
  |              	| Deque            	| 0.338569  	 |
  |              	| List             	| 0.321852  	 |
  |              	|                  	|            	|
  | 1000000      	| Vector           	| 3.3089  	   |
  |              	| Deque            	| 3.5264     	|
  |              	| List             	| 3.62349    	|
  |              	|                  	|            	|
  | 10000000     	| Vector           	| 28.3497    	|
  |              	| Deque            	| 32.9531  	  |
  |              	| List             	| 34.3291  	  |
  
  #### Bendras laikas
  
  | Įrašų kiekis 	| Duomenų strukūra 	| Trukmė (s) 	|
  |--------------	|------------------	|------------	|
  | 1000         	| Vector           	| 0.035242  	 |
  |              	| Deque            	| 0.033693  	 |
  |              	| List             	| 0.040733  	 |
  |              	|                  	|            	|
  | 10000        	| Vector           	| 0.132982  	 |
  |              	| Deque            	| 0.175049  	 |
  |              	| List             	| 0.164691   	|
  |              	|                  	|            	|
  | 100000       	| Vector           	| 1.19795    	|
  |              	| Deque            	| 1.5937  	   |
  |              	| List             	| 1.11342    	|
  |              	|                  	|            	|
  | 1000000      	| Vector           	| 11.5899  	  |
  |              	| Deque            	| 17.0633  	  |
  |              	| List             	| 11.7884  	  |
  |              	|                  	|            	|
  | 10000000     	| Vector           	| 114.53     	|
  |              	| Deque            	| 153.1603  	 |
  |              	| List             	| 119.167  	  |
  
  System:
  Processor	Intel(R) Pentium(R) CPU G4560 @ 3.50GHz, 3504 Mhz, 2 Core(s), 4 Logical Processor(s)
  Installed Physical Memory (RAM)	8.00 GB
  SSD
  
  


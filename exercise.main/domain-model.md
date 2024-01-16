| Classes        	| Methods                                	| Scenarios                                                                                 	| Outputs                         	|
|----------------	|----------------------------------------	|-------------------------------------------------------------------------------------------	|---------------------------------	|
| Bagel          	|                                        	|                                                                                           	|                                 	|
| Basket         	| Add(Bagel)                             	| Basket is not full                                                                        	| "Added bagel to basket!"        	|
|                	| Remove(Bagel)                          	| Basket is full                                                                            	| "Basket is already full!"       	|
|                	| IncreaseCapacity()                     	| Manager wants to increase capacity                                                        	| "Increased the capacity"        	|
| BagelOrder     	|                                        	|                                                                                           	|                                 	|
| BagelInventory 	| GetCost(string bagelType)              	| Customer wants to know the cost of a bagel before adding it to basket.                    	| Cost of the bagel               	|
|                	| GetFillingsCost(List<string> fillings) 	| Customer wants to know the cost of chosen fillings for a bagel before adding it to basket 	| Cost of the selected fillings   	|
| Customer       	|                                        	|                                                                                           	|                                 	|
| OrderManager   	| ChangeBasketCapacity(int newCapacity)  	| Bobs' manager wants to change the basket capacity                                         	| "Basket capacity has updated!"  	|
|                	| GetTotalCost(Basket basket)            	| Customer wants to know the total cost of the items in basket                              	| Total cost of items in basket   	|
|                	| IsItemInInventory(string item)         	| Customer wants to know is item is in the basket                                           	| True/False                      	|
|                	| GetBagelCost(string bagelType)         	| Customer wants to know the cost of an item before  adding it to the basket                	| Cost of bagel                   	|
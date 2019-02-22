# CASH PROGRAM

##Goal : Convert one currency to other ones in real time

Installation  :
1) Fork the project 
2) Clone the project in your workspace 
3) In the cmd : 

	$ cd path_to_workspace
	$ node cash.js

Several commands :

	$ cash <amount> <from> <to>
	$ cash <options>
	
Options
	 			
	$ --set -s
	
	Set default currencies

Examples

	$ cash 10 usd eur pln
	$ cash --set usd aud
	
Program steps :
1) The program is looking to the API adress in the constants.js file. 
2) It's going to check the actual currencies rate on internet in real time. 
3) It's also setting currency goal default in an array. 
4) The program is using the convert method in node libraries to convert the currency. 
5) If you havn't specified any currency goal or/and origin, it will convert you 1 USD in Euro, Britsh Pound, and Japanese Yen.

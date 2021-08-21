Apriori Algorithm

Our youtube channel: BMDersleri

Link: https://www.youtube.com/channel/UCIdYgV-XFjv9q0IHtzUTtQw

Related Youtube Video Link:https://www.youtube.com/watch?v=GvKvWCadyHE

Kısa Bağlantı: https://bit.ly/32k9MnJ

Our githup address: https://github.com/bmdersleri

Prepared: Melek Yılmaz

What is association  teory concept?
•	Association rule inference is the theory that tries to extract semantic relational values from the database..

What is apriori algorithm?
•	The Apriori algorithm looks at the frequency of the actions in the system, how much they correspond as a percentage and eliminates those below a certain value.

What is event frequency?
•	it is a concept that works over frequency. 
•	It is based on the combination of the most advantageous actions by eliminating the actions below a certain frequency value.

What is the logic of the apriori algorithm?
•	We use the list containing the products in the cart as parameters, minimum support, minimum confidence, minimum lift and minimum width for the products in the list .
•	For this, we initially create an empty list named t.
•	
•	We need to use each operation in a list, for this we use the list of list structure .
•	
•	The outside list contains all the shopping lists made.
•	
•	The inside list contains the list of products a person has bought.
•	
•	So we will list each line in the cart file
•	
•	We will then make a single list containing the lists on all rows.
•	
•	We will use a nested for loop for this.
•	
•	In the first for loop, the variable i navigates through each shopping list.
•	
•	Since there are seven thousand five hundred and one shopping lists in our basket file, the variable i takes a value between zero and seven thousand five hundred one.
•	
•	In the second for loop, the j variable allows to hover over the products in a shopping list .
•	
•	The variable j is between zero and twenty because there is a maximum of 20 items in a shopping list .
•	
•	We will take values from the data to add each product to our empty t-list.

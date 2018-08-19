#NYC Cafes
This is just me trying to learn d3!

The chart is the top 100 largest sidewalk cafes in NYC (ordered by number of tables). 

This is a very basic d3 bar chart, where I am playing around with learning tool-tips and setting colors on hover. 

##Notes:
- Accidentally used d3 v3 for this first viz, because I was following an old tutorial. 
- Data of all sidewalk cafes in NYC comes from [Enigma Public](https://public.enigma.com/datasets/new-york-city-sidewalk-cafe-licenses/4cae64c2-e309-4ee9-94d5-93ed99818bba), modified in shape to make it easier for a d3 noob to work with. I used just the top 100 restaurants, ordered by number of tables, removing a few duplicates. I also filled in dba business name where it was missing, because that's more interesting to see that the official business name. 
- I choose to order by number of tables rather than square footage of space because number of tables colmn was always filled and the sq. ft was missing for a few businesses. 
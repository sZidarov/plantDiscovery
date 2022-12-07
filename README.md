# plantDiscovery

On the first line of input, the program will receive a number n. On the next n lines, it will be given some information about the plants that I have discovered in the format: "{plant}<->{rarity}". The program stores that information for later. If the program receives a plant more than once, it updates its rarity.
After that, until the program receives the command "Exhibition", it will be given some of these commands:
•	"Rate: {plant} - {rating}" – add the given rating to the plant (store all ratings)
•	"Update: {plant} - {new_rarity}" – update the rarity of the plant with the new one
•	"Reset: {plant}" – remove all the ratings of the given plant
Note: If any given plant name is invalid, prints "error"
After the command "Exhibition", the program prints the information that you have about the plants in the following format:
"Plants for the exhibition:
- {plant_name1}; Rarity: {rarity}; Rating: {average_rating}
- {plant_name2}; Rarity: {rarity}; Rating: {average_rating}
…
- {plant_nameN}; Rarity: {rarity}; Rating: {average_rating}"
The average rating is formatted to the second decimal place.

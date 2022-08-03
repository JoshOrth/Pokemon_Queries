# Pokemon Query Assigment
I wrote a SQL script that contains queries for a Pokemon database containing their names, statistics and abilities. The data used was sourced from *Bulbapedia*  (https://bulbapedia.bulbagarden.net/wiki/Main_Page) and *Pokemon DB* (https://pokemondb.net/). These queries were written for a homework assignment in my Database Management class at The University of Iowa where I achieved a grade of 106% (including extra credit).

## Query Prompts
I was assigned to write the following queries:

**1.** Pokemon represent a diverse set of types. Write a simple query that returns the type and total number of Pokemon belonging to each type. Only include types that have at least 5 Pokemon in the results. Make sure to rename any new, calculated fields.

**2.** All members of the Bulbasaur family have names ending in “saur”. Write a simple query that returns summary statistics for the HP of Pokemon in this family, specifically the maximum and average HP. Round the average to a whole number (0 decimal places). Make sure to rename any new, calculated fields.

**3.** Assume that calculating BMI (body mass index) works the same in the Pokemon universe as in our own, using the following formula:
𝐵𝑀𝐼=𝑊𝑒𝑖𝑔ℎ𝑡 (𝑘𝑔)𝐻𝑒𝑖𝑔ℎ𝑡 (𝑚)2
Write a join query that returns the top 10 Pokemon with the highest BMI. For each, return their ID, name, BMI (rounded to one decimal place), and the name of their evolution (i.e., the Pokemon they evolve into). Make sure to rename any new, calculated fields.

**4.** Some Pokemon belong to multiple types, but is this more common in base evolution Pokemon or evolved Pokemon? Write a compound query that returns the name and speed rating for each evolved Pokemon that belongs to both the poison type and any other secondary type.

**5.** Pokemon may possess a “hidden” ability. Write a subquery that returns the name of each Pokemon with a hidden ability, plus the name and description of the ability. Only include Pokemon whose defense rating is greater than the median over all Pokemon.

**6.** (*Extra Credit*) Does evolution yield stronger Pokemon? Write a join query that returns the name and attack rating for each evolved Pokemon, plus the name of their direct ancestor (i.e., the Pokemon they evolved from). In addition, return the difference in attack strength between them (attack rating of Pokemon – attack rating of ancestor). Sort the results so that the Pokemon with the highest attack ratings are listed at the top. Make sure to rename any new, calculated fields.

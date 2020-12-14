# Nutrient Profiling model 
This repository contains notebooks on scrapped products,product scoring and data.
(i)Script for scrapping data from wholefoodsmarket,vitaminshoppe,iwonorganics.
(ii)product scoring of organic label products
(iii)comaparison of iwon organics with other snacks brands

Methodology of Nutrition scoring:
Overall score = negative factors - positive factors
negative_factors are sugars,salt,saturated_fat and energy
positive factors are protein,fibers,fruits and nuts and vegetables.

#calculating overall score

#If a food scores less than 11 ‘A’ points then the overall score is calculated as follows:
#Total ‘A’ points (energy + saturated fat + sugars + sodium) Minus Total ‘C’ points (fruit, veg and nuts + fibre + protein)

#If a food scores 11 or more ‘A’ points but scores 5 points for fruit, vegetables and nuts then the overall score is calculated as follows:
#Total ‘A’ points (energy + saturated fat + sugars + sodium)  Minus Total ‘C’ points (fruit, veg and nuts + fibre + protein)

#If a food scores 11 or more ‘A’ points, and less than 5 points for fruit, vegetables and nuts, then the overall score is calculated as follows :
#Total ‘A’ points (energy + saturated fat + sugars + sodium) Minus Points for fibre + points for fruit, vegetables and nuts (not allowed to score for protein)


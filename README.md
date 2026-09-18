# Assignment-1

## Overview of the exercises

## Exercise 1
This exercise takes a business revenue and cost as input, calculates profit as revenue minus cost, and then computes the profit margin as a percentage of revenue. It also checks whether the revenue is valid; if the revenue is not greater than zero, it prints an “Invalid revenue” message.

## Exercise 2
This exercise evaluates a credit score and determines the likely loan outcome. It uses a simple rule-based system:

below 300 or above 850 = invalid score
750 = approved
700–749 = approved with review
600–699 = conditional
below 600 = denied

## Exercise 3
This exercise formats a user’s full name into a friendly greeting. It trims extra whitespace, handles empty names by falling back to a default greeting, capitalizes the first name, and returns a message like “Hello, Alex (Customer)!”

## Exercise 4
This exercise assigns an income level to a tax bracket and estimates the tax owed based on simplified rates:

under 50,000 = low bracket (10%)
50,000–99,999 = medium bracket (20%)
100,000+ = high bracket (30%)
It also includes a basic deduction check
based on whether the income is even.

## Exercise 5
This exercise classifies a product into a margin category based on product name keywords. It recognizes categories such as electronics/gadgets as high margin, clothing/apparel as medium margin, and food/grocery as low margin. If none match, it marks the item as “Uncategorized - Review Needed.”

## Bonus
This exercise checks whether a business is profitable based on revenue versus cost and then recommends an action. If the business is profitable, it suggests reinvesting or expanding depending on the category; if not, it suggests reducing costs or re-evaluating the strategy.

## Assumptions made
Inputs are entered as numeric values where required, with basic validation only.
Credit scores are assumed to be integers in the range 300–850.
Revenue, cost, and income values are treated as simple floats.
Product category names are normalized to lowercase before comparison.
Tax brackets and loan decisions are simplified examples rather than real financial or banking rules.
The code assumes these are teaching exercises rather than production-grade business logic.
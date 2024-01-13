
# market basket analysis

Key features of the data:

Products:  Nestlé MUNCH chocolate bars, MILKMAID condensed milk, and EVERYDAY Ghee.

Quantities:  Range from 4 to 15 items per purchase.

Prices: Vary depending on the product.

Customer IDs: Linked to each transaction, enabling potential customer segmentation analysis.

Bill Number: Indicates that multiple items were purchased together within a single transaction, providing the basis for association rule  mining.

process you can follow for the task of Market Basket Analysis :

Gather transactional data, including purchase history, shopping carts, or invoices.

Analyze product sales and trends.

Use algorithms like Apriori or FP-growth to discover frequent item sets and generate association rules.

Interpret the discovered association rules to gain actionable insights.

Develop strategies based on the insights gained from the analysis.
## build with 
python ( numpy,pandas,matplotlib,seaborn ) 


## Documentation

 association rules for market basket analysis:

Antecedents :

they are the "if" items that start a rule, while consequents are the "then" items that tend to be purchased along with them.

Support:
 measures how often a combination of items appears together in transactions.

Confidence:
 tells you the probability of buying the consequent item when the antecedent is already in the basket.

Lift:
 reveals the strength of the association between items, considering their independent purchase probabilities. A lift greater than 1 suggests a positive association, meaning they're more likely to be bought together.


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project

Create your Feature Branch (git checkout -b "")

Commit your Changes (git commit -m "")

Push to the Branch (git push origin"/")

Open a Pull Request


## License

Distributed under the MIT License. See LICENSE.txt for more information.


## Acknowledgements

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

https://github.com/RandolphVI/Next-Basket-Recommendation

https://github.com/adwansyed/Market-Basket-Analysis-Apriori


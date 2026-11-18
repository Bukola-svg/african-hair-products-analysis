# Black Hair Products in Africa: What Drives Value, Sales and Buying Decisions

A four-phase data science project comparing black hair care products, starting with Nigeria and expanding across Africa and Europe, ending with a buyer's guide.

## Project question

Do African-owned black hair care brands offer better value (ratings per naira) than international brands, and what predicts sales and purchase decisions: price, brand origin, ingredients or reviews?

## Phases

| Phase | Focus | Status |
| --- | --- | --- |
| 1 | Nigerian products compared with each other | In progress |
| 2 | Nigeria vs. other African countries | Not started |
| 3 | Africa vs. Europe | Not started |
| 4 | Buyer's guide: how to choose a product that works | Not started |

## Data

- **Product data:** listings collected from online marketplaces and brand websites (name, brand, category, price, rating, review count, ingredients, origin, platform, date collected). See `data/products_template.csv` for the columns.
- **Survey data:** an anonymous Google Forms survey of Nigerian consumers about what they buy, what they pay, and what they would buy again. No names or emails are collected, and no personal data is published.

## Approach

1. Collect and clean product and survey data
2. Explore: price vs. rating, price vs. review count, African vs. international brands
3. Predict sales (review count as a proxy) with linear regression and random forest
4. Predict purchase decisions with logistic regression and random forest
5. Evaluate with a train/test split and report limitations honestly

## Limitations

- Review counts are a proxy for sales, not actual sales.
- Ratings are not proof that a product works.
- The survey is online and self-selected, so results describe internet-connected Nigerian consumers, not everyone.

## Repository structure

```
data/        raw and cleaned data (no personal details)
notebooks/   one notebook per phase
README.md
```

## Author

Built as part of my data science portfolio after completing the WorldQuant University Data Science Lab. Feedback is welcome.

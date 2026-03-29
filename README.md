# pokemon-status-predictor
This is a machine learning pipeline I developed to identify the statistical factors that define "Special" Pokémon status (Legendary, Sub-Legendary, and Mythical) across all nine generations of game data. Using a Random Forest Classifier, the model I developed achieved a 95.1% peak test accuracy and a **92.6% cross-validated mean score**, demonstrating strong stability and generalizability. Furthermore, I performed a feature importance analysis which revealed that Special Attack, Speed, and Height are the strongest predictors of this 'Special' status, suggesting that these types of Pokémon are tied to greater offensive capabilities and larger physical builds than their normal counterparts.

The dataset used for this analysis is included in the repository, titled "pokemon.csv".

**Tech stack:** Python, Scikit-Learn, Pandas, Matplotlib, Seaborn.

# Goal
This repository aims to provide the datasets used in [1].

# Contents
Each data file contained in this repository is explained below:
- [data_cars_original.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_cars_original.csv): data on car crash fatalities from the nassCDS dataset via the ["DAAG" R package](https://cran.r-project.org/web/packages/DAAG/index.html) from [2]
- [data_cars_binary.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_cars_binary.csv): data on car crash fatalities after transforming the original categorical variables from [data_cars_original.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_cars_original.csv) into binary variables. Details about such transformations are available in [1] (Section 6.2.1, Table 10)
- [data_spotify_original.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_spotify_original.csv): data on musical tastes in Spotify from the last.fm dataset via [[3]](https://medium.com/radon-dev/item-item-collaborative-filtering-with-binary-or-unary-data-e8f0b465b2c3)
- [data_spotify_75.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_spotify_75.csv): data on musical tastes in Spotify considering only the 75 most listened-to artists from data_spotify_original.csv. Details about such artists are available in [1] (Section 6.3.2, Table 19)
- [data_spotify_15.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_spotify_15.csv): data on musical tastes in Spotify considering only the 15 most listened-to artists from data_spotify_original.csv. Details about such artists are available in [1] (Section 6.3.2, Table 19)
- [data_bank_original.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_bank_original.csv): data on bank term deposit subscriptions from the dataset Bank Marketing via [[4]](https://doi.org/10.24432/C5K306) from [5]
- [data_bank_binary.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_bank_binary.csv): data on bank term deposit subscriptions after transforming the original variables from [data_bank_original.csv](https://github.com/LauraDavilaPena/GT-based_IM/blob/main/data_bank_original.csv) into binary variables. Details about such transformations are available in [1] (Section 6.4.1, Table 28).



# References
[1] Davila-Pena, L., Saavedra-Nieves, A., and Casas-Méndez, B. (2024). On the influence of dependent features in classification problems: a game-theoretical perspective. _arXiv preprint_. [https://doi.org/10.48550/arXiv.2408.02481](https://doi.org/10.48550/arXiv.2408.02481)


[2] Maindonald, J. H. and Braun W. J. (2021). Data analysis and graphics using R. An example-based approach (3rd edition). Cambridge University Press, Cambridge. _The DAAG package was created to support this text. [https://CRAN.R-project.org/package=DAAG](https://cran.r-project.org/web/packages/DAAG/index.html) [R package version 1.25.6.]_

[3] Item-item collaborative filtering with binary or unary data, 
[https://medium.com/radon-dev/item-item-collaborative-filtering-with-binary-or-unary-data-e8f0b465b2c3](https://medium.com/radon-dev/item-item-collaborative-filtering-with-binary-or-unary-data-e8f0b465b2c3). Accessed: 17 July 2024

[4] Moro, S., Rita, P., and Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C5K306](https://doi.org/10.24432/C5K306).

[5] Moro, S., Laureano, R., and Cortez, P. (2011). Using Data Mining for bank direct marketing: An application of the CRISP-DM methodology. In P. Novais et al. (Eds.), _Proceedings of the European Simulation and Modelling Conference - ESM'2011_ (pp. 117-121). EUROSIS: Guimarães, Portugal.



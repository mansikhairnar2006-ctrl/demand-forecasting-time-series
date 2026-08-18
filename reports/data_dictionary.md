# Data Dictionary

## Train Dataset

| Column | Description | Data Type | Role |
|---|---|---|---|
| Store | Unique identifier for each store | Integer | Feature |
| DayOfWeek | Day of the week (1 = Monday, 7 = Sunday) | Integer | Feature |
| Date | Date of the observation | Date | Time Feature |
| Sales | Daily sales of the store | Integer | Target |
| Customers | Number of customers visiting the store | Integer | Feature |
| Open | Indicates whether the store was open | Integer | Feature |
| Promo | Indicates whether a promotion was active | Integer | Feature |
| StateHoliday | Indicates the type of state holiday | Categorical | Feature |
| SchoolHoliday | Indicates whether a school holiday was active | Integer | Feature |

## Test Dataset

| Column | Description | Data Type | Role |
|---|---|---|---|
| Id | Unique identifier for the test observation | Integer | Identifier |
| Store | Unique identifier for each store | Integer | Feature |
| DayOfWeek | Day of the week | Integer | Feature |
| Date | Date of the observation | Date | Time Feature |
| Open | Indicates whether the store was open | Integer | Feature |
| Promo | Indicates whether a promotion was active | Integer | Feature |
| StateHoliday | Indicates the type of state holiday | Categorical | Feature |
| SchoolHoliday | Indicates whether a school holiday was active | Integer | Feature |

## Store Dataset

| Column | Description |
|---|---|
| Store | Unique store identifier |
| StoreType | Type of store |
| Assortment | Level/type of product assortment |
| CompetitionDistance | Distance to nearest competitor |
| CompetitionOpenSinceMonth | Month when competition opened |
| CompetitionOpenSinceYear | Year when competition opened |
| Promo2 | Indicates whether the store participates in Promo2 |
| Promo2SinceWeek | Week when Promo2 started |
| Promo2SinceYear | Year when Promo2 started |
| PromoInterval | Months when Promo2 is repeated |
# lmis
African Labor Market Information library(tidyverse)
library(lubridate)
library(forecast)
library(scales)

# Create the basic historical dataset
plateau_finance <- tibble(
  year = 1976:2026,
  total_revenue = NA_real_,
  igr = NA_real_,
  federal_allocation = NA_real_,
  grants = NA_real_,
  recurrent_expenditure = NA_real_,
  capital_expenditure = NA_real_,
  total_expenditure = NA_real_,
  domestic_debt = NA_real_,
  external_debt = NA_real_,
  debt_service = NA_real_,
  population = NA_real_,
  gdp = NA_real_
)

# Display structure
print(plateau_finance)

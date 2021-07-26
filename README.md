# GDELT
GDELT and ACS data by county-year with CCES

The code is in the four R Markdown files. Open them and step through them in order (don't try to knit them).

Don't forget to register and install a Census API key before proceeding!

  * Go to [https://api.census.gov/data/key_signup.html] to get one if you don't have it
  * Enter `tidycensus::census_api_key("`_<your key>_`", install=TRUE)` to install your key

`here::here()` is supposed to point to the directory where the `.Rmd` files live. If you have trouble:

  * Set your working directory there with `setwd()`.
  * Rewrite those satements as needed with `paste0(getwd(), "/", `_<the required path>_`)`.

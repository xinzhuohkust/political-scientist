# Collection of R and Python resources for political scientist #

As a political scientist, you may find the following collection of R and Python resources to be useful for your research and data analysis.

## Geographic data computation
- [book: Geocomputation with R](https://ereg.ets.org/ereg/public/jump?_p=GRI)

## Blogs
- https://rweekly.org/#RintheRealWorld

## Quarto 
how to publish .qmd file to bookdown:
```
rsconnect::addConnectServer("https://bookdown.org", "bookdown.org")
rsconnect::connectApiUser(
  account = "", server = "bookdown.org",
  apiKey = Sys.getenv("CONNECT_API_KEY")
)
quarto::quarto_publish_site(
  name = "data-analysis-in-action", render = "none",
  server = "bookdown.org",
  account = "",
  title = "Data Analysis in Action"
)
```
## Tidy series
- [tidyPython](https://tidypolars.readthedocs.io/en/latest/)
- [tidyJulia](https://github.com/TidierOrg/Tidier.jl)

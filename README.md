# Collection of R and Python resources for political scientist #

As a political scientist, you may find the following collection of R and Python resources to be useful for your research and data analysis.

## Data Wrangling
- [larger than memory data](https://arrow.apache.org/cookbook/r/index.html)

## Geographic data computation
- [book: Geocomputation with R](https://ereg.ets.org/ereg/public/jump?_p=GRI)
- [SpatialEcon](https://github.com/mauricio1986/Spbook/blob/main/SpatialEconometrics.pdf)
- [weather data](https://www.wunderground.com)
- [weather](https://cloud.tencent.com/developer/article/1633211)

## Blog
- https://rweekly.org/#RintheRealWorld

## Quarto 
### publish
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
### shiny
[shiny and quarto](https://appsilon.com/interactive-quarto-report-translation-tutorial/)
[shiynlive](https://quarto-ext.github.io/shinylive/)
## Tidy series
- [tidyPython](https://tidypolars.readthedocs.io/en/latest/)
- [tidyJulia](https://github.com/TidierOrg/Tidier.jl)

## Marginal Effects
- [marginal effects](https://www.andrewheiss.com/blog/2022/05/20/marginalia/)
- [marginal effects of mixed effect model](https://www.andrewheiss.com/blog/2022/11/29/conditional-marginal-marginaleffects/index.html#marginal-effects-or-effect-of-a-variable-across-clusters-on-average)

## NLP
- [wordembedding introduction](https://aistudio.baidu.com/aistudio/projectdetail/6030731?channelType=0&channel=0)
- [Supervised Machine Learning for Text Analysis in R
](https://smltar.com/)

## Causal Inference
- [causal inference with R](https://www.r-causal.org/)
- [causal panel data](https://yiqingxu.org/tutorials/panel.html)

## Blogger
- [Andrew](https://www.andrewheiss.com/)
- [Kurz](https://solomonkurz.netlify.app/)
- [Isabella](https://ivelasq.rbind.io/)
- [michael decrescenzo](https://mikedecr.netlify.app/)
- [mockup](https://themockup.blog/)
- [Milz](https://beamilz.com/)
## Github action with R
- [github action with R](https://beamilz.com/posts/series-gha/2022-series-gha-1-what-is/en/index.html)
- https://rfortherestofus.com/2023/05/github-actions/

## Visualization

### table
[reactable](https://yuanfan.rbind.io/project/dt-wwc/)




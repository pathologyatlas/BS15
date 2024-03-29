







```
r language BS15, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis endometriozis, kolon duvarı TR, echo = (language == "TR")
## BS15 - endometriozis, kolon duvarı {#sec-BS15 }
```


```
asis endometriosis, colon wall EN, echo = (language == "EN")
## BS15 - endometriosis, colon wall {#sec-BS15 }
```






```
r BS15 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS15-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS15/HE.html",
  file = "./screenshots/BS15-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS15/HE.html](https://images.patolojiatlasi.com/BS15/HE.html)





```
asis, echo = (language == "TR")

**endometriozis, kolon duvarı**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS15-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS15/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS15/HE.html)
```

```
asis, echo = (language == "EN")

**endometriosis, colon wall**

[![Click for Full Screen WSI](./screenshots/BS15-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS15/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS15/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS15/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS15/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

endometriozis, kolon duvarı

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

endometriosis, colon wall

:::

```









:::::










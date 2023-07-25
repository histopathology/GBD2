# GBD2



**GBD2 for pathology atlas repositories**




```{r language GBD2, echo=FALSE, include=TRUE}
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```




```{asis, echo = (language == "TR")}
## pediatrik otopsi {#sec-GBD2}
```


```{asis, echo = (language == "EN")}
## pediatric autopsy {#sec-GBD2}
```


```{r GBD2 screenshot, eval=TRUE, include=FALSE}
if (!file.exists("./screenshots/GBD2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/GBD2/HE.html",
  file = "./screenshots/GBD2_screenshot.png"
)
}
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
knitr::include_url(url = "https://images.patolojiatlasi.com/GBD2/HE.html")
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
#| label: GBD2_screenshot
#| fig-cap: "pediatrik otopsi"
knitr::include_graphics("./screenshots/GBD2_screenshot.png")
```


::: {.content-hidden when-format="html"}
pediatrik otopsi
:::

::: {.content-visible when-format="pdf"}
pediatrik otopsi
:::



```{asis, echo = (language == "TR")}

**pediatrik otopsi**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD2/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD2/HE.html)
```


```{asis, echo = ((language=="TR") & (output_type=="html"))}
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD2/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment} 
asis, echo = (language == "TR")

**pediatrik otopsi**


[![İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD2/HE_annotated.html) [İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD2/HE_annotated.html)

İşaretlenmiş mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD2/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment}
asis, echo = (language == "TR")



<button id="tani-case-GBD2-btn">Tanıyı Göster</button>
<div id="answer-GBD2" style="display: none;">pediatrik otopsi</div>

<script>
  const showAnswer-GBD2Btn = document.getElementById('tani-case-GBD2-btn');
  const answer-GBD2 = document.getElementById('answer-GBD2');

  showAnswer-GBD2Btn.addEventListener('click', () => {
    if (answer-GBD2.style.display === 'none') {
      answer-GBD2.style.display = 'block';
      showAnswer-GBD2Btn.textContent = 'Tanıyı Gizle';
    } else {
      answer-GBD2.style.display = 'none';
      showAnswer-GBD2Btn.textContent = 'Tanıyı Göster';
    }
  });
</script>

```

```{comment}
asis, echo = ((language=="TR") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="TR") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```





```{asis, echo = (language == "EN")}

**pediatric autopsy**

[![Click for Full Screen WSI](./screenshots/GBD2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD2/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/GBD2/HE.html)


```



```{asis, echo = ((language == "EN") & (output_type=="html"))} 

See Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD2/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```


```{comment}
asis, echo = (language == "EN")

**pediatric autopsy**

[![Click for Full Screen Annotated WSI](./screenshots/GBD2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD2/HE_annotated.html) [Click for Full Screen Annotated WSI](https://images.patolojiatlasi.com/GBD2/HE_annotated.html)


See Annotated Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD2/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>



```

```{comment}
asis, echo = (language == "EN")

<button id="dx-case-GBD2-btn">Show the Diagnosis</button>
<div id="answer-GBD2" style="display: none;">pediatric autopsy</div>

<script>
  const showAnswer-GBD2Btn = document.getElementById('dx-case-GBD2-btn');
  const answer-GBD2 = document.getElementById('answer-GBD2');

  showAnswer-GBD2Btn.addEventListener('click', () => {
    if (answer-GBD2.style.display === 'none') {
      answer-GBD2.style.display = 'block';
      showAnswer-GBD2Btn.textContent = 'Hide the Diagnosis';
    } else {
      answer-GBD2.style.display = 'none';
      showAnswer-GBD2Btn.textContent = 'Show the Diagnosis';
    }
  });
</script>

```


```{comment}
r, eval=TRUE, echo=FALSE, include=FALSE, error=TRUE
if (!file.exists("./screenshots/GBD2_screenshot.png")) {

url <- "https://img.youtube.com/vi/U9glkfQLTm4/maxresdefault.jpg"
download.file(url, destfile = "./screenshots/GBD2_screenshot.png", mode = "wb")
}

**pediatrik otopsi**

[![Video İçin Tıklayın](./screenshots/GBD2_screenshot.png){width="25%"}](https://www.youtube.com/watch?v=) [Video İçin Tıklayın](https://www.youtube.com/watch?v=)

```




```{comment}
asis, echo = ((language=="EN") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="EN") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```


```{comment}
=html
<iframe src="https://images.patolojiatlasi.com/GBD2/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>
```

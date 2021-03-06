---
title: cirospat mkdocs-style 
---

![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)  <br>
<img alt="undefined" src="https://img.shields.io/github/last-commit/cirospat/mkdocs-style.svg?&label=ultimo_aggiornamento"> <br>
![GitHub](https://img.shields.io/github/license/cirospat/mkdocs-style)


# cirospat mkdocs-style
![](https://raw.githubusercontent.com/cirospat/mkdocs-style/main/docs/img/logo2.png)
Modello per la creazione di un progetto di documentazione online


## Cosa è
Modello per la creazione di un progetto di documentazione online, creato con lo strumento [MKDocs](https://squidfunk.github.io/mkdocs-material/). Le pagine per inserire contenuti vengono redatte utilizzando il linguaggio **MarkDown** (`.MD`).

Lavoro realizzato con il prezioso supporto tecnico di [@gbvitrano](https://github.com/gbvitrano), [@aborruso](https://github.com/aborruso) e [#opendatasicilia](https://github.com/opendatasicilia) a cui va un caro ringraziamento e un grande grazie per la pazienza.


## Compilazione con Github pages
[GitHub ghpages](https://squidfunk.github.io/mkdocs-material/publishing-your-site/#with-github-actions) 


## Link al progetto creato su pagine di Github
[cirospat mkdocs-style](https://cirospat.github.io/mkdocs-style/)

---


## Strumenti integrati nel progetto
- **Addthis** per la condivisione sui social, e stampa pagine del progetto. Loghi social visualizzabili nella parte destra della pagina web su desktop e in basso su dispsitivi mobile. IL codice di Addthis si inserisce nel file `main.html` che si trova al seguente percorso `mkdocs-style/docs/overrides/main.html`
- **Disqus** per permettere di inserire commenti in ogni singola pagina, tranne nell'home page. L'istruzione per inserire il codice di Disqus viene data nel file `mkdocs.yml` 
- **Strumento di generazione dei contenuti del progetto in formato PDF**, indicato in ogni pagina con il simbolo della stampante posizionato in alto a destra
- **feed RSS** per avere un link per gli aggiornamenti automatici dei contenuti del progetto di documentazione. L'istruzione per inserire l'integrazione dell feed RSS viene data nel file `mkdocs.yml`

Questi strumenti sono opzionali e possono non essere inclusi nella visualizzazione del progetto di documentazione online che si intende creare

## Cosa deve cambiare l'utente per generare progetti di documentazione online con MKDocs a partire da questo modello
- i parametri del file `mkdocs.yml`
- i contenuti nel file `index.md` che si trova nella directory `docs`
- i contenuti dei file `.md` che si trovano dentro la cartella madre `docs` (ed eventualmente sotto cartelle) e che rappresentano il nome dei capitoli o sezioni del documento. Ogni file `.md` è la pagine web del progetto di documentazione
- inserire le immagini nella cartella `img` che si trova nel percorso `mkdocs-style/docs/img/`
- inserire il favicon che si trova al seguente percorso `mkdocs-style/docs/overrides/.icons/favicon.png`. E' facoltativo e non è importante
- inserire i dati nel file `docs/manifest.webmanifest`

---


## Search Icons + Emojis
:ant:
[**icons-emojis**](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#icons-emojis)
:butterfly:

<iframe width="100%" height="550" src="https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/" frameborder="1" allow="autoplay; encrypted-media" allowfullscreen></iframe>

---

## Inserire servizio commenti Disqus

esempio di codice

```
<script id="dsq-count-scr" src="//guida-readthedocs.disqus.com/count.js" async></script>
<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = PAGE_URL;  
this.page.identifier = PAGE_IDENTIFIER; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://guida-readthedocs.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
```

## Simboli 

codici per i simboli

esempi: `simbols` =  :blue_heart:  &#10024; &#x1F310; &#128194; &#128187; &#10233; 

link per i simboli:

- [**https://www.webfx.com/tools/emoji-cheat-sheet**](https://www.webfx.com/tools/emoji-cheat-sheet);
- [**https://sphinxemojicodes.readthedocs.io**](https://sphinxemojicodes.readthedocs.io);
- [**https://www.w3schools.com/charsets/ref_emoji.asp**](https://www.w3schools.com/charsets/ref_emoji.asp) Emoji Unicode Reference in html

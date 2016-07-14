# Programming languages genealogical tree

![diagram](https://raw.githubusercontent.com/stereobooster/programming-languages-genealogical-tree/gh-pages/img/diagram.png)

Source: [rigaux.org](http://rigaux.org/language-study/diagram.html)

Basic idea behind project reconstruct diagram above in [D3](https://d3js.org/):

  - to be able to edit data easily. Simply send PR to this repo and everyting, else will be updated
  - to use html5 instead of plain image, for better perfomance, for vector graphics, to enable text search via `Ctrl + F` and copy/paste
  - add interactivity to diagram, for example: select one node and it will show all "ancestors" and "children"

There are a lot of similar efforts and all of them have one big flow from my point of view. It is not very clear what influence-links mean. There are different relationship possible between languages. For example:

**Superset or subset**.

  - [sass](http://sass-lang.com/) (sccs) is superset of [css](https://www.w3.org/Style/CSS/Overview.en.html)
  - SIMULA is superset of ALGOL 60. Source: [link](http://www.edelweb.fr/Simula/#7)

**Inspiration or ideas**

  - JavaScript took it's idea of prototypal inheritance from [Self](https://en.wikipedia.org/wiki/Self_(programming_language))
  - Ruby took it's OOP concepts from SmallTalk: objects communicate  via messages, everything is an object (even classes)
  - C++ took it's OOP concepts from Simula [citation required]

**Similar syntax**

  - C, C++, Java, JavaScript
  - LISP, Scheme

Many links between languages in simillar projects not provide information on what kind of relation it is and lacks credibility. So they tends to be more confusing rather than helpfull. I want to add this type of information.

Other side of this project is to show in what language concept (idea, paradigm, technique) first appeared. See [link](http://rigaux.org/language-study/concepts-history.html). So if similar concept appears in other language it is can be considered as inspired by original source. But this not alway true: Simula considered to be first object-oriented language (even though there was idea of object before [citation required]), but idea of object-oriented language presented in SmallTalk is completley different and both languages appeared with small time difference, so I do not consider that one was inspired by another. Yes, both languages talk about object, but OOP-ideas behind them are comletley different.

## Similar projects

 - http://archive.oreilly.com/pub/a/oreilly/news/languageposter_0504.html Most beautiful timeline with reasonable number of languages ([pdf](http://cdn.oreillystatic.com/news/graphics/prog_lang_poster.pdf)). SmallTalk have Simula as influencer which is misleading, but also have LISP which is fair enough.
 - http://rigaux.org/language-study/diagram.html Timeline with big number of languages
 - https://www.levenez.com/lang/ Timeline with very big number of languages ([pdf](https://www.levenez.com/lang/lang.pdf)).
 - http://www.digibarn.com/collections/posters/tongues/ Have some serious misleading links between languages (example: Fortran -> LISP), but like its idea on marking status of language: Active, Protected, Endangered, Extinct.
 - https://blog.ouseful.info/2012/07/03/mapping-how-programming-languages-influenced-each-other-according-to-wikipedia/ Big graph based on semantic data, but not very useful
 - https://exploringdata.github.io/info/programming-languages-influence-network/ Big beautiful graph, but not very useful

## More ideas

Add info about authors to programming languages.

Add concpets and their connection to languages.

Add links to scientific papers behind language concepts.
  - http://bibliography.selflanguage.org/
  - https://github.com/rust-lang/rust-wiki-backup/blob/master/Note-research.md

It is possible to add mathematical theories which were preceding programing languages, like lambda calculus can be considered as parent of  s-expressions (LISP) [citation required]. Haskell has roots in category theory [citation required].

## Other links

 - [Syntaxation. Douglas Crockford](https://www.youtube.com/watch?v=Nlqv6NtBXcA)
 - http://www.ibm.com/developerworks/library/l-linux-shells/
 - https://www.emacswiki.org/emacs/EmacsHistory
 - http://www.moolenaar.net/vimstory.pdf
 - http://www.linfo.org/vi/history.html
 - https://www.levenez.com/unix/unix.pdf
 - https://www.levenez.com/unix/
 - https://commons.wikimedia.org/wiki/File:Unix_history-simple.png
 - http://i.stack.imgur.com/NZx8g.png

## D3 examples of timelines and similar graphs

 - [Exploring Family Trees (Beta)](https://learnforeverlearn.com/ancestors/)
 - [Behind the Scenes: ChronoZoom](http://research.kraeutli.com/index.php/2014/01/behind-the-scenes-chronozoom/)
 - [Comic Book Narrative Charts (d3)](http://csclub.uwaterloo.ca/~n2iskand/?page_id=13)
 - [Narrative Charts Tell the Tale…](https://blog.ouseful.info/2014/04/07/narrative-charts-tell-the-tale/)
 - http://bl.ocks.org/bunkat/2338034
 - http://bl.ocks.org/bunkat/1962173
 - http://bl.ocks.org/tnightingale/4718717










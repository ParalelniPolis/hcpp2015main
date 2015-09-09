# Jak opravim text na webu ?

Vetsina textu je definovana v souboru [website_text.yaml](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_data/website_text.yaml)

# Jak upravim text recnika ?

* Kazdy recnik ma dva soubory ve slozce [_posts](https://github.com/ParalelniPolis/hcpp2015main/tree/gh-pages/_posts)
* Jeden pro Ceskou verzi webu s ```_cz``` v nazvu a druhy bez pro Anglickou verzi
* Napriklad soubor pro [Ceskou verzi](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_posts/2015-08-28-cz_braun.md) a [Anglickou verzi](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_posts/2015-08-28-braun.md) recnika Franka Brauna
* Text vykreslovany na hlavni strance s fotkou recnika je definovany v sekci ```speakers``` v souboru [website_text.yaml](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_data/website_text.yaml#L366)
* Recnik ma take svuj zaznam v kalendari, opet v souboru [webiste_text.yaml](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_data/website_text.yaml#L110)

# Jak upravim HTML sablonu ?

* Stranka titulni trany je definovana v [default.html](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_layouts/default.html)
* Stranka recnika je v [speaker.html](https://github.com/ParalelniPolis/hcpp2015main/blob/gh-pages/_layouts/speaker.html)

# Jak si zobrazim stranku lokalne, bez commitovani na Github ?

* [Nainstalujes si Jekyll](http://jekyllrb.com/docs/installation/)
* Stahnes si tento repozitar na PC
* Vstoupis do slozky repozitare
* Spustis ```jekyll serve```
* Otevres v browseru ```http://127.0.0.1:9001/```

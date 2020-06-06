Projekt na předmět KAJ - aplikace malování v prohlížeči

**Cíl projektu:** Cílem projektu je tvorba webové aplikace malování, ve které si uživatel může kreslit, psát, nahrávat tam fotky apod.

**Postup tvorby:** Nejprve jsem vytvořil základní html strukturu s canvasem. Dále jsem přidával jednotlivé funkce malování.

**Popis funkčnosti:**

1. Tužka: 
    *  Kreslení libovolných náčrtů
    *  Libovolná barva, šířka a průhlednost
2. Text:
    *  Umístění textu kdekoliv na kreslící ploše
    *  Text může mít libovolnou barvu výplně (možnost bez výplně), barvu ohraničení, průhlednost a tloušťku ohraničení
    *  Text může být stylem Times New Roman nebo Arial
3. Rovná čára
    *  Vytvoření rovné čáry kdekoliv na kreslící ploše
    *  Libovolná barva, šířka a průhlednost
4. Guma
    *  Gumovací nástroj (bílá tužka :D)
    *  Libovolná šířka
5. Obdelník
    *  Nakreslení obdelníku
    *  Libovolná barva výplně a ohraničení, šířka ohraničení a průhlednost
6. Kruh
    *  Nakreslení kruhu (kružnice při zvolení bez výplně)
    *  Libovolná barva výplně a ohraničení, šířka ohraničení a průhlednost
7. Fotka
    *  Upload fotografie z počítače - přes tlačítko nebo přes Drag and drop
    *  Libovolná průhlednost
8. Přesun objektů
    *  Možnost přesouvání textu, obdelníků, kruhů a fotek po kreslící ploše
9. Mazání objektů
    *  Po využití přesunu objektu lze objekt smazat klávesou delete
10. Export canvasu jako jpg


**Manuál:**
1.  Tužka:
    1.  Kliknout na tlačítko Tužka
    2.  Zvolit barvu, tloušťku a průhlednost podle svých preferencí
    3.  Stisknout levé tlačítko myši v libovolném místě na kreslící ploše, následně tahem myši se tvoří čára
    4.  Kreslení se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
2.  Text:
    1.  Kliknout na tlačítko Text
    2.  Zvolit barvu výplně, ohraničení, tloušťku ohrančení, průhlednost a styl textu
    3.  Kliknout na libovolné místo na kreslící ploše, objeví se malá linka
    4.  Napsat text
    5.  Psaní textu se ukončí kliknutím na kreslící plochu
3.  Rovná čára:
    1.  Kliknout na tlačítko Rovná čára
    2.  Zvolit barvu, tloušťku a průhlednost podle svých preferencí
    3.  Stisknout levé tlačítko myši v libovolném místě na kreslící ploše, následně tahem myši se tvoří rovná čára
    4.  Kreslení se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
4.  Tužka:
    1.  Kliknout na tlačítko Guma
    2.  Zvolit tloušťku podle svých preferencí
    3.  Stisknout levé tlačítko myši v libovolném místě na kreslící ploše, následně tahem myši se gumuje
    4.  Gumování se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
5.  Obdelník:
    1.  Kliknout na tlačítko Obdelník
    2.  Zvolit barvu výplně, ohraničení, tloušťku ohrančení a průhlednost
    3.  Stisknout levé tlačítko myši v libovolném místě na kreslící ploše, následně tahem myši se tvoří obdelník
    4.  Kreslení se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
6.  Kruh:
    1.  Kliknout na tlačítko Kruh
    2.  Zvolit barvu výplně, ohraničení, tloušťku ohrančení a průhlednost
    3.  Stisknout levé tlačítko myši v libovolném místě na kreslící ploše, následně tahem myši se tvoří kruh
    4.  Kreslení se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
7.  Fotka:
    1.  Kliknout na tlačítko Vložit foto a vybrat fotku ze souborového systému nebo využít možnost Drag and drop
    2.  Pro Drag and drop stačí přetáhnout fotku kamkoliv na stránku
    3.  Bezprostředně po uploadu lze provést jeden přesun fotky, následné přesuny se musí provést přes přesun objektů
8.  Přesun objektů:
    1.  Kliknout na tlačítko Přesun objektů
    2.  Stisknout levé tlačítko myši na některém z podporovaných objektů (vše kromě čar), následně tahem myši se objekt přesouvá
    4.  Přesun se ukončí při uvolnění tlačítka myši nebo opuštění kreslící plochy
9.  Mazání objektů:
    1.  Mazat lze stejné objekty jako přesouvat
    2.  Objekt se smaže při stisknutí delete po přesunu
10.  Export canvasu:
    1.  Kliknout na tlačítko Exportovat img
    2.  Vybrat místo umístění v souborovém systému

**Požadované funkcionality, které nemusí být hned viditělné:**
*  CSS transformace - při najetí myší na tlačítka
*  CSS transitions - při zakliknutí ,,Bez výplně"
*  Zvuky z JS - při nakreslení čehokoliv
*  Aplikace funguje offline
*  Drag and drop - možnost uploadu fotky přes Drag and drop






## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/nacovfil/malovani/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nacovfil/malovani/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

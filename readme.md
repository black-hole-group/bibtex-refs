Black hole group BibTeX database
======================

This is the BibTeX database for the [Black Hole Group](https://rodrigonemmen.com/group/) @ IAG USP, with over 1000 references in black hole and high energy astrophysics as well as an auxiliary TeX file with abbreviations of common astrophysics journals. 

It is *strongly recommended* to adopt BibTeX in your academic documents, papers and proposals (trust me, this will save you a lot of time in the long run).


# Files

```
refs.bib    
│
└───journals.tex
```

* *journals.tex* - abbreviations of journals for bibliography
* *refs.bib* - bibtex file

# How to use the database


Simply include the following line at the end of your latex document:

    \bibliography{refs}
    
# Contributing to the database

Everybody is welcome to add references to the database and keep it growing. :smile:

Just add papers to the database in the usual bibtex way, commit your file and push to this repo. 

### Guidelines for updating the bibtex file

#### 1. Keep the consistent notation for `bibtexkey` and journal code

The notation for the `bibtexkey` field is *Last Name of First Author + last two digits of year of publication*. 

Examples: 

> Yuan, F.; Lin, J.; Wu, K. & Ho, L. C.
A magnetohydrodynamical model for the formation of episodic jets. MNRAS, 2009, 395, 2183

becomes

* bibtexkey = `Yuan09`
* journal = \apj

> F Yusef-Zadeh, R. Arendt, H. Bushouse, W. Cotton, D. Haggard, M. W. Pound, D. A. Roberts, M. Royster, and M. Wardle. A 3 pc SCALE JET-DRIVEN OUTFLOW FROM SGR A*. The Astrophysical Journal Letters, 2012, Volume 758, Number 1

becomes

* bibtexkey = `Yusef-Zadeh12`
* journal = \apjl



#### 2. Recommended apps for managing the database


Some useful apps you can use to manage the database: 

- [jabref](http://www.jabref.org)
- [mendeley](https://www.mendeley.com/newsfeed/)
- [bibdesk](http://bibdesk.sourceforge.net) (macOS only)
- [papers](http://www.papersapp.com) (macOS only)

#### 3. Easily grabbing bibtex info from a paper in NASA ADS, arXiv or DOI

Every search engine for references includes ways of copying the bibtex info for a paper.

Alternatively, for convenience, it is suggested to use the [adspaste](https://github.com/rsnemmen/adspaste) command-line tool. Some examples:

```
adspaste 1998ApJ...500..525S	# from ADS
adspaste 10.1093/mnras/stv260	# from DOI
adspaste 1411.4682	# from arXiv
```
In each case, the full bibtex info will be copied to the clipboard and ready to be inserted in database.


&nbsp;

---

![](https://rodrigonemmen.files.wordpress.com/2016/03/black-hole-logo-group-iag-transparent.png?w=474) 

New to Git? [Check this out](https://github.com/rsnemmen/Git-for-busy-people).

[Black Hole Group](https://rodrigonemmen.com/group/) @ IAG USP


# 1word — base de contenu dérivée (CC BY-SA 4.0)

Ce dépôt publie la base de contenu **dérivée** servie par le jeu 1word, en
application de la clause **« partage à l'identique »** (décision D2, 2026-08-12).

## Licence

L'ensemble de ce dépôt est publié sous **Creative Commons Attribution -
Partage dans les Mêmes Conditions 4.0** (CC BY-SA 4.0) :
https://creativecommons.org/licenses/by-sa/4.0/deed.fr

## Sources et attribution

Les définitions et citations proviennent des projets **Wiktionnaire** et
**Wikiquote** (éditions par langue), publiés sous CC BY-SA par leurs
contributeurs, via les extractions Kaikki/Wiktextract. Chaque ligne JSONL porte
sa `source`, sa `licence` et, quand elle existe, l'`url` d'origine.

## Contenu

- `mots/` — 1 264 384 entrées (mot + définition) : cs 25 679 · de 62 287 · el 42 223 · en 254 275 · es 45 153 · fr 132 266 · id 14 053 · it 27 350 · ja 36 181 · ko 274 906 · la 1 401 · nl 74 509 · pl 45 729 · pt 38 706 · ru 108 432 · tr 42 414 · vi 15 597 · zh-Hans 11 610 · zh-Hant 11 613
- `citations/` — 80 330 entrées (citations et idiomes) : cs 3 187 · de 2 710 · el 1 520 · en 5 951 · es 7 322 · fr 6 253 · id 11 · it 3 508 · ja 2 744 · ko 11 113 · nl 548 · pl 2 901 · pt 8 155 · ro 350 · ru 11 009 · sv 963 · tr 5 069 · vi 727 · zh-Hant 6 289

Format : un objet JSON par ligne (JSONL), UTF-8.

## Régénération

Ce dossier est produit par `tools/export-ccbysa.mjs` du dépôt principal, à
partir du contenu réellement servi (les entrées écartées ou en attente de
validation n'y figurent pas). Republier après chaque évolution notable du
contenu servi.

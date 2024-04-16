# Bible cross-reference tools 
Data from [openbible.info](https://www.openbible.info/labs/cross-references/), www.openbible.info CC-BY 2024-03-11

`cross_references_expanded.csv` was derived from openbible.info original data table, and parsed and expanded for added flexibility and sortability.

[`openbible_from_verse_libraries_BibleGateway_query.ipynb`](https://github.com/shandran/openbible/blob/main/openbible_from_verse_libraries_BibleGateway_query.ipynb) creates dataframe dictionaries of every chapter in every book of the Bible. Then, for a *from verse* query of interest, you can generate Bible Gateway scripture links (in ESV by default, but this can be changed) to every *to verse* cross-referenced to the query verse.

[`openbible_from_verse_libraries_treemap.ipynb`](https://github.com/shandran/openbible/blob/main/openbible_from_verse_libraries_treemap.ipynb) generates an interactive plotly treemap of all 344,799 *from verse* cross-references.

![treemap of all cross-references in the Bible via openbible.info dataset](openbible_crossreferences_plotly_treemap.png "treemap of all cross-references in the Bible via openbible.info dataset")

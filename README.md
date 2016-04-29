# ln2sql

ln2sql is a tool to query a database in natural language, as described in the following French paper (also available in this repository) :

<i><a rel="license" href="https://www.researchgate.net/publication/278965118_fr2sql_Interrogation_de_bases_de_donnees_en_francais"> Benoît Couderc and Jérémy Ferrero. fr2sql : Database Query in French. (fr2sql : Interrogation de bases de données en français [in French]). In Proceedings of 17th RECITAL (join with 22th TALN Conference). June 2015. Caen, France. ATALA. pp.1-12 </a></i>

In view to learn Python, I recently decided to implement our originally PHP project in Python. In addition, that will allow me to share the tool with the English-speaking community by making it public available.

### Features

- [X] Import a database schema from sql dump
- [X] Import a thesaurus from LibreOffice thesaurus template
- [X] Import stopword lists
- [X] Match database keywords with input sentence
- [ ] Parse input sentence in query sections
- [ ] Parse sections
- [ ] Print query structure in XML schema
- [ ] Print query structure in JSON
- [ ] Product query
- [ ] Exception and error handling
- [ ] User Interface
- [ ] Multi threading

### SQL statement supported

- [ ] one-column select
- [ ] multi-column select
- [ ] table select
- [ ] count
- [ ] multi-count
- [ ] join
- [ ] inner join
- [ ] where
- [ ] junction
- [ ] disjunction
- [ ] cross-constraint
- [ ] comparison
- [ ] aggregate
- [ ] between
- [ ] order by
- [ ] group by
- [ ] multi query
- [ ] Date support
- [ ] Negation support

<br/>

### <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /> License

This tool is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
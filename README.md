# SelRa
## Grammars in Understanding Software

### Project
Development of a domain-specific language designed to implement a teacher support system that allows them to choose a suitable learning resource for a given student to teach a given programming concept in order to maximize the effectiveness of the teaching process /learning in an Introduction to Programming course. This language was a way to express the solution to the proposed problem in a simpler and more direct way than the use of a specific programming language.

### Contextualization
As previously mentioned, a language was developed, being necessary to describe the structure of sentences and words in natural language. For this, a **Attributes Grammar** was used because it allows the local definition of the meaning of each symbol in a declarative style. Furthermore, the attribution of the value of each symbol is local.

### Language
Based on the basic concepts in the SelRA developed language presented, the system should propose the most adequate resources for this, we propose the following [language](SelRA.g4).

### Results
After the entire process of construction, settlement and implementation of the system, it was necessary to present the results obtained according to our convictions: brief, clear and succinct. For this purpose, a [server](___server___/server.js) was built in *Node.js* that provides HTML pages upon requests made in the browser. It should be noted that the built structures originate a [JSON file](___server___/db.json) because with the help of the *JSON-Server* it facilitated the presentation of information.

### Team
![Gonçalo Pinto][grp-pic] | ![Diogo Pereira][diogo-pic] | ![Francisco Lopes][chico-pic] | ![Luís Ribeiro][luis-pic]
:---: | :---: | :---: | :---:
[Gonçalo Pinto][grp] | [Diogo Pereira][diogo] | [Francisco Lopes][chico] | [Luís Ribeiro][luis]

[grp]: https://github.com/GRP99
[grp-pic]: https://github.com/GRP99.png?size=120
[diogo]: https://github.com/dpereira7
[diogo-pic]: https://github.com/dpereira7.png?size=120
[chico]: https://github.com/chico2911
[chico-pic]: https://github.com/chico2911.png?size=120
[luis]: https://github.com/luis1ribeiro
[luis-pic]: https://github.com/luis1ribeiro.png?size=120

<div align="center">
  <sub>September 2020 - January 2021</sub>
</div>
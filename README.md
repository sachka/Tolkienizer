# Tolkienizer
## A J.R.R. Tolkien Based Text Annonymizer
This program uses the Stanford CoreNLP API to detect Named Entities NE from a text file, it then generates an equivalent for each entity based on the universe of Middle Earth (The Hobbit, The Lord of The Rings and The Silmarilion).

### EXAMPLE

```
"Scott Kennedy works for General Electric, his email is scott_kennedy@ge.com, he lives in New York."
```
coul be annonimized as follows:
```
"Bilbo Baggins works for Dwarves from Moria inc., his email is bilbo_baggins@moria.com, he lives in Bag End."
```

This program was created in order to annonymize the Eron email dataset.

## Built With

* [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) - The NLP framework used
* [Groovy](https://groovy-lang.org/) - Programming Language


## Authors

* **Hermes Martinez** - *Computational Linguist* - [Sachks](https://github.com/Sachks)
* **Timothée Mickus** - *Computational Linguist* - [dugongdingo](https://github.com/dugongdingo)
* **Xining Li** - *Computational Linguist* - [abaoli](https://github.com/abaoli)

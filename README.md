# Igbo Dictionary
*Igbo is the principal native language of the Igbo people, an ethnic group of southeastern Nigeria, and is spoken by approx 45 million people in at least 20 different dialects.*

This repo parses the words, word classes, definitions, and more from the Columbia University paper [*Dictionary of Ònìchà Igbo*](http://www.columbia.edu/itc/mealac/pritchett/00fwp/igbo/IGBO%20Dictionary.pdf).

## Start the API

To start the dev API server run the following command:

```
yarn dev
```

Navigate to [localhost:8080](http://localhost:8080/) to see the API

### Build a Dictionary

Even though the Igbo dictionary files are already available in this repo, you can still run the script that's responsible for parsing the Columbia paper and creating the `.json` and `.txt` files.

`dictionary.html` is an HTML representation of the Columbia PDF.

To parse `dictionary.html` and build a dictionary, run the following command:

```
yarn build
```

This will produce three different files in the `ig` directory:

[dictionaries/dictionary.txt](./ig/dictionaries/dictionary.txt)
[dictionaries/dictionary_compressed.json](./ig/dictionaries/dictionary_compressed.json)
[dictionaries/dictionary_expanded.json](./ig/dictionaries/dictionary_expanded.json)

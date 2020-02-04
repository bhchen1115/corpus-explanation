# Corpus Explanation

- [Interrogation](###Interrogation)
- [Mafiascum](###Mafiascum)
- [Phishing](###Phishing)

## Details

### Interrogation

This dataset is provided by Taiwan Ministry of Justice Investigation Bureau, containing transcript files of real-world polygraph tests.

- Filename: **interrogation-json.zip**  
Last update: Feb. 3rd  
Description:
  - Contains 496 original json files, from case id 001 to 498. We don't have files of case id 106 and 156.
  - Consists of 226 deceptive cases and 270 honest cases.
  - Meaning of fields of each json file is described [here](interrogation-field-explanation.md).
  - Caution that all "numbers" in json files are not numbers. They are strings actually.
- Filename: **interrogation-ws.zip**  
Last update: Feb. 3rd  
Description:
  - We extract conversations from json files and then segment words (via [CKIP](https://github.com/ckiplab/ckiptagger)) in each sentence.
  - Results are in txt format.
  - Each line follows the format:  
  `<q_or_a> <q_type> <word_1> <word_2> ... <word_n>`

### Mafiascum

- Filename: **mafiascum.json**  
Last Update: Feb. 3rd  
Description:
  - A collection of 700 games of Mafia.
  - Detailed in paper [The Mafiascum Dataset: A Large Text Corpus for Deception Detection](https://arxiv.org/abs/1811.07851).

![Samples of Mafiascum Corpus](https://raw.githubusercontent.com/bhchen1115/corpus-explanation/master/screenshots/mafiascum.png)

### Phishing

- Filename: **phishing.json**  
Last Update: Feb. 3rd  
Description:
  - Detailed in paper [Learning to Detect Phishing Emails](https://wwwconference.org/www2007/papers/paper550.pdf)

![Samples of Phishing Corpus](https://raw.githubusercontent.com/bhchen1115/corpus-explanation/master/screenshots/phishing.png)

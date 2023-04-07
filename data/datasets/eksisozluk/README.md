# Site Description

[Ekşi Sözlük](https://eksisozluk.com/) is a collaborative hypertext dictionary based on the concept of Web sites built up on user contribution. Founded in 1999, it can be thought of a mix between Reddit and UrbanDictionary.

It is by far the most popular internet forum for the Turkish language. [Stats from the year 2022](https://eksisozluk2023.com/entry/147008116) show that the website has seen 363 million unique visitors with over 8 billion individual page visits, with around 3.5 million daily visits on average.

As an online public sphere, Ekşi Sözlük is not only utilized by thousands for information sharing on various topics ranging from scientific subjects to everyday life issues, but also used as a virtual socio-political community to communicate disputed political contents and to share personal views. As such, the subjects discussed there ranges anywhere from politics to science and relationships.

# Creating the dataset

## Eksipy

There exists several APIs to crawl Eksisozluk data, however from my previous experience [eksipy](https://github.com/yusufusta/eksipy) seems to be a simple and effective solution. It allows easy retrieval of each user entry for any given topic.
One can create a automated script to crawl through different topics and create snapshots of .parquet data every so often. Also a Job can be created which runs daily to crawl that given day's discussions for up-to-date data.

Let me know what you think! Looking forward to your feedback and opinions before I get to work.

Overall, with the current state of [Open-Assistant Stats](https://open-assistant.io/en/stats) showing a significant lack of data in the Turkish language, I believe Eksisozluk will provide a great amount of naturally generated data, ranging from serious to casual.
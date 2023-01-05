## project logs

### 12.03.2022
Done today: mostly research & brainstorming around the project. As we are free to create a corpus around any topic, we are allowed to be as creative as we wish! Thinking of building a corpus with articles on a fandom.
Questions: database format? how to process wiki markup content?

### 12.04.2022
* New docs in `/data` : *kpop* & *citypop* wiki articles. (.txt files)
* First tries with `markovify` module : quick model implementation & text generation.
* Issues: how to deal with images? templates used in wikipages? (how to process data before training?)

### 01.04.2023
Managed to run to prof's python script to process wikipedia xml data! When working with xml data exported from fandom wiki, pre-processing needed (`<origin>` tag to delete, otherwise script does not work. might want to review said script)
* themes ideas: to gather a smaller corpus, pick a category within Dune universe (ex.: Sardaukar, Fremen, characters from House Artreides, Bene Gesserit etc...). should get about 20 wiki articles, but Dune is wide franchise: the categories cited above, have around 60+ articles each.
* reading: *The Hundred-page Machine Learning Book* by Andry Burkov. 

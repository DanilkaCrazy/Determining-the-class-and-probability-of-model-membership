# Determining the class and probability of model membership

Воспользуйтесь моделью [aychang/roberta-base-imdb](https://huggingface.co/aychang/roberta-base-imdb), которая обучена на датасете [imdb](https://huggingface.co/datasets/stanfordnlp/imdb). Это датасет, содержащий 50000 комментариев к фильмам на платформе IMDB, отзывы пользователей классифицируются на два класса - положительные (label - neg) и отрицательные (label - pos). С помощью импортированной модели определите настроение следующего отзыва:

\```
text_cls = """This film was probably inspired by Godard's Masculin, féminin and I urge you to see that film instead.
The film has two strong elements and those are, the realistic acting the impressive, undeservedly good, photo. 
Apart from that, what strikes me most is the endless stream of silliness. 
Lena Nyman has to be most annoying actress in the world. She acts so stupid and with all the nudity in this film,...it's unattractive. 
Comparing to Godard's film, intellectuality has been replaced with stupidity. 
Without going too far on this subject, I would say that follows from the difference in ideals between the French and the Swedish society.
A movie of its time, and place."""
\```

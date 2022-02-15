<h1 align="center">Welcome to np-word2vec-vue</h1>

> A Flask + Vue webapp to find similar words of a word, similarity score of two words and finding odd word among a group of words..

### 🏠 [Live Site](https://word2vec-incor.herokuapp.com/)


npm run build

yarn serve (para rodar no local)

(rodar backend antes na porta 5000)


Salvar nesse formato:

from gensim.models import Word2Vec, KeyedVectors   
model.wv.save_word2vec_format('model.bin', binary=True)

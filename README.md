# SYS843_Experimentation
code pour les expérimentations du projet de SYS843

papier XLNet : https://arxiv.org/pdf/1906.08237.pdf 
papier BERT : https://arxiv.org/pdf/1810.04805.pdf
papier ULMFiT : https://arxiv.org/pdf/1801.06146.pdf

Pour les datasets, la librairie datasets de huggingface à été utilisé : https://huggingface.co/docs/datasets/
Pour BERT et XLNet la librairie transformers fournit les codes pour les modèles, tokenizer... : https://huggingface.co/docs/transformers/index
Pour ULMFiT la librairie fastai fournit les codes nécessaires : https://github.com/fastai/fastai

Pour faire lancer les codes, il faut d'abord executer les codes dans get_data_imdb.ipynb et get_data_sst5.ipynb pour obtenir les datasets partitionnés (train, val, test).
Ensuite, pour chaque modèle et chaque dataset il suffit de voir le notebook associé, les résultats sont déjà présents mais nous pouvons les réexecuter.

Tous les codes ont été developpé en se basant sur des tutoriels, notamment : https://huggingface.co/docs/transformers/training pour BERT et XLNet; et https://github.com/fastai/fastai/blob/master/dev_nbs/course/lesson3-imdb.ipynb pour ULMFiT

Cascades from the paper "A study on information disorders on social networks during the Chilean social outbreak and COVID-19 pandemic", Mendoza et al. [2023].
Each file comprises an information cascade retrieved from Twitter. The cascades are organized into false, true and imprecise units of content. For each cascade, 
we provide the tweetID and the interaction between them. The format of each file is as follows:

raiz: ['854495625911685120','0.0']->['ROOT','0.0']
reply: ['854497037059989505','337.0']->['854495625911685120','0.0']
reply: ['854498539484971013','695.0']->['854495625911685120','0.0']
reply: ['854500249099960320','1102.0']->['854495625911685120','0.0']
reply: ['854500370009247745','1131.0']->['854495625911685120','0.0']

The longint var indicates the tweetID. The second component indicates the time elapsed from the parent tweet to the child tweet. 
For instance, reply: ['854497037059989505','337.0']->['854495625911685120','0.0'] indicates that the tweet 854497037059989505 replies 
854495625911685120 337 seconds after the parent post.

If you use these data, please cite our work:

Mendoza, M.; Valenzuela, S.; Núñez-Mussa, E.; Padilla, F.; Providel, E.; Campos, S.; Bassi, R.; Riquelme, A.; Aldana, V.; López, C. A Study on Information Disorders on Social Networks during the Chilean Social Outbreak and COVID-19 Pandemic. Appl. Sci. 2023, 13, 5347. https://doi.org/10.3390/app13095347


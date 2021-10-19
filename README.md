Projets : Le tour de France des musées !
  
Le tour de France des musées !
Ca y est, tu es déjà armé pour être Data Analyst, niveau junior. Tu vas aujourd'hui analyser ton premier fichier csv 👀

1. Introduction
Tu viens d'être recruté en tant que stagiaire Data Analyst par le Ministère de la Culture. Le précédent stagiaire avait réussi à récolter le maximum d'informations sur les musées français.
Comme première mission, ton manager te demande d'analyser avec Python le fichier csv obtenu et d'essayer de trouver des informations intéressantes dans ce fichier.

En fait, la 17ème Nuit européenne des musées a eu lieu le samedi 3 juillet 🏛🏛🏛 Pour revenir sur cet événement annuel, la personne responsable de la communication a été sollicitée pour écrire un article -je cite- "qui balance des infos insolites sur les musées en France".
Mais elle ne sait pas vraiment quoi raconter ... Elle espère que ton analyse de données l'aidera à se lancer dans la rédaction de son article 🙄🙄

2. Le projet
2.1. Télécharger le fichier csv et l'ouvrir sur ton notebook
Le travail réalisé par le stagiaire précédent a été mis en ligne sur la plateforme Opendata du gouvernement : data.gouv.fr. Tu peux retrouver son travail ici et télécharger le fichier csv concernant les musées de France métropolitaine.

Si tu es curieux, n'hésite pas à aller regarder le script Python qui a été réalisé et pourquoi il a fait cela. Cela te permettra de t'imprégner de la mentalité open source et de voir le genre de scripts que tu sauras faire à la fin de la formation.

2.2. Répondre aux questions posées par ton manager
Ton manager t'a donné une liste de questions pour te rendre la tâche plus concrète. Il t'a demandé de répondre à ces questions dans un premier temps en laissant apparentes tes requêtes sur le Notebook.

Combien y-a-t-il de musées en France métropolitaine ?
Dans quelle(s) ville(s) y-a-t-il de plus de musées ?
Quel est le nombre moyen de musées par ville ?
Quel est le nombre médian de musées par ville ?
Comment sont répartis les musées par type (en pourcentage) ?
Combien y-a-t-il de musées dont le nom commence par "Château" ?
Pour combien de musées dispose-t-on de l'adresse du site web ?
Quel département français possède le plus de musées sur son territoire ?
Quel département français possède le moins de musées sur son territoire ?
Combien de musées ont "Napoléon" dans leur nom ?
2.3. Proposer deux axes d'analyse supplémentaires
Tu rends la réponse aux 10 questions mais ton manager n'est pas totalement satisfait. Il trouve que cela manque encore d'informations vraiment croustillantes pour le grand public.

Il te demande alors un nouveau travail : peux-tu proposer deux sources de données complémentaires qui pourraient enrichir le fichier ? Les développeurs se chargeront de récupérer les données quand tu auras identifiées les sources.

Par exemple, si tu trouves un site qui donne la fréquentation de tous les musées français, je pense que la responsable de la communication sera contente de pouvoir ajouter dans son article un top 5 des musées les plus fréquentés, ainsi qu'un flop 5 de ceux où personne ne va jamais 👹👹

Ajoute à la suite de ton fichier Jupyter une cellule au format Markdown qui détaille les deux sources de données existantes qu'il serait utile d'ajouter au fichier csv initial, sur quel site on peut les obtenir et ce qu'elles apporteraient dans l'analyse.

Cela permettra à ton manager d'évaluer tes capacités de prise d'initiative et de recherche sur le web.

3. Rendu attendu
Un beau fichier Jupyter qui alterne entre code et texte et contient les 3 étapes du projet 🍹🍹



_________________________________





Projets : Le tour du monde des universités !
  
Le tour du monde des universités !
Tu t'es fait la main sur les musées de France. Tu cherches maintenant à monter en gamme et à étudier des données internationales. Rien de mieux pour cela que de se frotter aux fameux classements internationaux des universités 🎓🎓

1. Introduction
Suite à ton stage au ministère de la Culture, tu es embauché par l'Université de Strasbourg dans l'équipe data.

Leur enjeu du moment est de bien comprendre les différents classements internationaux des universités et en particulier, voir comment ils pourraient améliorer leur place dans ces derniers.

Pour te mettre à l'aise dans ta première mission, la directrice de l'équipe data te laisse une demi-journée pour te familiariser avec les jeux de données dont ils disposent et répondre à une liste de huit questions 🤓🤓

2. Le projet
2.1. Télécharger les fichier csv et les ouvrir sur ton notebook
Les fichiers que t'a demandé de télécharger ta directrice sont disponibles sur Kaggle. Tu dois d'abord te créer un compte sur la plateforme pour pouvoir télécharger les données.

😑😑 Kaggle, kezako ? 😑😑

Kaggle est une plateforme web qui organise des compétitions en data science. Pour cette raison, on trouve énormément de jeux de données sur cette plateforme. Tu seras amené plusieurs fois au cours de la formation à aller cette plateforme. Nous te recommandons d'utiliser Kaggle sans modération.

2.2. Répondre aux questions posées par ton manager
Donne un aperçu de chaque fichier csv et décris en une phrase son contenu.
Quelles années sont prises en charge par chaque classement ?
Combien d'universités sont prises en compte annuellement par chaque classement en moyenne ? Il s'agit ici de donner le nombre moyen d'universités prises en compte par chaque classement lors d'une année.
Quels sont les rankings obtenus par l'Université de Strabourg dans chacun des 3 classements disponibles ?
Selon le classement du Times, quels sont les 20 meilleures universités en 2016 ? Quelle est la part d'universités américaines ?
Combien chaque pays possède d'universités dans le classement de Shanghai en 2015 ? Range la liste par ordre décroissant. Pense à t'aider de la table université - pays pour réaliser cette requête.
Quelles sont les universités françaises présentes dans le classement du Center for WUR ?
Quels pays ont les plus faibles ratios (Dépenses dans les Institutions du Supérieur (Privées et Publiques) en 2011) / Nombre d'universités dans le classement du Times en 2011 ? Range cette liste par ordre croissant.
2.3. Trouver des informations intéressantes
Tu as réussi à trouver une réponse à toutes ces questions ?
Il est temps maintenant que tu t'habitues à fonctionner en pleine autonomie 👉👉

La directrice de l'équipe data te demande de lui apporter 5 informations intéressantes qui pourraient très utiles à la direction de l'Université pour orienter leur stratégie dans les années à venir. Par exemple, tu pourrais calculer que "les 20 meilleures universités au classement du Times ont un taux de parité relativement peu élevé (30% vs 45% en moyenne)". Ou alors que "l'université de Strasbourg fait partie du 10% des universités présentes dans le classement qui ont le moins d'étudiants internationaux".
❌ Ces dernières données sont erronnées, à toi de chercher ce qui est intéressant dans tous ces fichiers et de renvoyer les bonnes données !

3. Rendu attendu
Un beau fichier Jupyter qui alterne entre code et texte et contient les 3 étapes du projet 🍹🍹
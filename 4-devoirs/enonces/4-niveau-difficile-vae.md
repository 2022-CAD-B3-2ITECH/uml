# Exercice Centre de validation des acquis de l'académie

[Source de l'énoncé](https://prive.iutenligne.net/VzpOxD8Vwz2LTExl/informatique/langages/kettaf/UML/exercices/exercice01.html)

## Énoncé

Toute personne qui a exercé pendant 5 ans une activité professionnelle en rapport avec l'objet de sa demande peut demander l'obtention d'un diplôme de l'enseignement technologique et professionnel auprès du Centre de validation des Acquis de l'Académie de son domicile.

Le salarié obtient un dossier vierge auprès du Centre de validation des Acquis de l'Académie (CAVA). Après avoir complété le dossier, le salarié l'envoie au CAVA. Le dossier contient l'état civil du candidat (nom, prénom, adresse), une description de ses activités professionnelles depuis 5 ans, le diplôme demandé. Les dossiers sont enregistrés dans la base de données du CAVA (un numéro de référence leur sont automatiquement affecté).

Le CAVA envoie le dossier au domicile de l'inspecteur d'Académie responsable du diplôme concerné. L'inspecteur vérifie si le dossier est recevable. C'est à dire, si le diplôme demandé correspond aux activités professionnelles du candidat depuis au moins 5 ans. L'inspecteur communique sa décision aux CAVA qui l'enregistre dans sa base de données. Si le dossier est recevable, un accusé de réception est envoyé au candidat ; sinon le dossier est retourné au candidat avec un courrier lui indiquant les raisons du refus du dossier.

Il y a un jury par diplôme. Un jury est composé de l'inspecteur d'Académie responsable du diplôme et d'enseignants. Le CAVA connaît les coordonnées des enseignants membres d'un jury. Chaque jury se réunit trois fois par an.

Le planning des réunions d'un jury est établi par l'inspecteur d'Académie responsable du diplôme concerné, en début d'année scolaire. Trois semaines avant une réunion d'un jury, le CAVA convoque les membres du jury ainsi que les candidats ayant un dossier de demande de diplôme en suspens (concernant le diplôme sous la responsabilité du jury).

A la fin d'une réunion, le jury établit un procès-verbal où les décisions du jury sont récapitulées (acceptation ou refus du diplôme). En fonction de ce procès-verbal, le CAVA envoie une attestation de diplôme aux candidats ou un refus de diplôme.

## Travail à réaliser

1. Modélisez le système à l'aide d'un diagramme de cas d'utilisation.
2. Modélisez le système à l'aide d'un diagramme de classes.
# Projet de scrapping du site de tracteur
1.	Contexte du projet
Dans le cadre de notre projet d’analyse du marché des camions tracteurs d’occasion et neufs, nous avons étudié un site spécialisé dans la vente de véhicules industriels.
Notre analyse préliminaire a montré que le site contient plus de 6 000 camions tracteurs disponibles. Cependant, l’interface du site limite la navigation à 8 pages visibles, avec 25 annonces par page, ce qui empêche l’accès direct à l’ensemble des données via une simple navigation.
Afin de réaliser une analyse complète du marché des camions tracteurs dans différents pays, il est nécessaire de mettre en place un processus de scraping permettant d’extraire automatiquement les informations clés présentes dans les annonces.

2.	Données collectées
Les informations extraites sont organisées en quatre catégories principales.

2.1 Basic Data (Données de base)
Information	Description	Utilité pour l’analyse
Manufacturer	Marque ou constructeur du camion (ex : Volvo, Scania, Mercedes-Benz).	Permet d’analyser la popularité des marques et leur présence sur le marché.
Year of construction	Année de fabrication du véhicule.	Sert à estimer l’âge du véhicule et à analyser la relation entre âge et prix.
Condition	État du camion (neuf, occasion, reconditionné, etc.).	Permet de segmenter le marché selon la qualité et l’état des véhicules.

2.2 Price & Location (Prix et localisation)
Information	Description	Utilité pour l’analyse
Fixed price + VAT	Prix du véhicule hors taxes auquel s’ajoute la TVA.	Utile pour les entreprises qui récupèrent la TVA et pour comparer les prix nets.
Fixed price gross	Prix total incluant la TVA.	Représente le coût réel payé par l’acheteur final.
Location	Pays ou ville où se trouve le camion.	Permet d’analyser la distribution géographique du marché et les différences de prix selon les pays.

2.3 Technical Details (Détails techniques)
Information	Description	Utilité pour l’analyse
Mileage	Kilométrage total parcouru par le camion.	Indicateur clé de l’usure du véhicule et facteur important dans la détermination du prix.

2.4 Details about the Offer (Informations sur l’annonce)
Information	Description	Utilité pour l’analyse
Listing ID	Identifiant unique de l’annonce sur le site.	Permet d’éviter les doublons et de suivre une annonce spécifique.
Update	Date de dernière mise à jour de l’annonce.	Permet d’analyser la durée de présence des annonces sur le marché et la dynamique des ventes.

3.	Objectif de l’exploitation des données
Les données collectées permettront de :
•	analyser les tendances de prix des camions tracteurs
•	comparer les marchés entre différents pays
•	étudier l’influence de l’âge et du kilométrage sur les prix
•	identifier les marques les plus présentes sur le marché
•	suivre la dynamique des annonces (mise à jour, disponibilité)
Cette base de données constituera ainsi une source fiable pour l’analyse du marché des camions tracteurs.


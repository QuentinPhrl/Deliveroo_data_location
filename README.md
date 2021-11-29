# Deliveroo_data_location
Projet visant à mettre en forme les données de localisation provenant de la plateforme Deliveroo rider (livreur à vélo).
Ce projet utilise les positions GPS du livreur à chaque fois qu'il a accepté une commande, ce qui permet de tracer grossièrement les trajets réalisés par le livreur.
Pour visualiser les données, le projet utilise la librairie OSMNX en python qui permet de générer un graphique représentant les routes d'une ville en se basant sur les données d'OpenStreetMap.
Le projet est exécuté via Jupyter Notebook.

Configuration de Jupyter Notebook sous Debian pour OSMNX


conda update -n base conda

conda config --prepend channels conda-forge

conda create -n ox --strict-channel-priority osmnx jupyterlab

conda activate ox

jupyter lab



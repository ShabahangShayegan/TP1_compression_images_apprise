# TP1 — Compression d’images apprise

Implémentation et évaluation de méthodes de compression d’images par apprentissage profond avec PyTorch et CompressAI.

## Objectifs

- Construire un compresseur neuronal simplifié avec quantification et codage entropique rANS.
- Évaluer des modèles pré-entraînés de CompressAI : `bmshj2018-factorized` et `cheng2020-anchor`.
- Comparer les codecs appris à JPEG, HEVC (x265) et VVC (VVenC).
- Mesurer les performances débit-distorsion à l’aide du PSNR, du MS-SSIM et du BD-rate.
- Affiner un modèle pré-entraîné pour explorer différents compromis entre débit et qualité.

## Prérequis

- Python et PyTorch
- CompressAI
- Google Colab (GPU recommandé)
- FFmpeg avec le support x265
- VVenC pour les comparaisons VVC facultatives

## Utilisation

Ouvrir le notebook dans Google Colab, activer l’accélération GPU si disponible, puis exécuter les cellules dans l’ordre. Compléter les exercices et analyser les résultats obtenus.

## Jeu de données

Les expériences utilisent le jeu de données d’images Kodak, avec des images distinctes pour l’entraînement et les tests.

## Résultats

Le notebook génère des courbes débit-distorsion, des comparaisons entre codecs, des mesures de débit, des reconstructions visuelles et des évaluations de la complexité de calcul.

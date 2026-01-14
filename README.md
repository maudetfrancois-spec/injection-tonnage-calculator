Injection Tonnage Simulator

Un simulateur léger et interactif pour estimer la force de verrouillage (tonnage) nécessaire pour l'injection de pièces plastiques.

🚀 Utilisation

L'outil calcule le tonnage en fonction de :

La Surface Projetée (cm²)

L'Épaisseur de la pièce (mm)

Le Nombre de points d'injection (réduction de 20% de la pression par point supplémentaire)

La Famille de matière (PP, ABS, PC, etc.)

🧮 Méthode de calcul

Le simulateur utilise la formule suivante :
Tonnage = Sproj * (K_matière * C_épaisseur * C_injection) * 1.1

C_épaisseur : Ajustement automatique si l'épaisseur est différente de 3mm.

C_injection : Réduction de la pression de 20% pour chaque point d'injection ajouté.

1.1 : Marge de sécurité standard de 10%.

🛠 Installation locale

Clonez le dépôt : git clone https://github.com/votre-utilisateur/nom-du-repo.git

Ouvrez index.html dans votre navigateur.

📄 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

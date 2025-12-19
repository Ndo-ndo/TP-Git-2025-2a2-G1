Réflexion sur le TP Git
Structure du projet
Notre projet contient une branche main et trois branches personnelles avec plusieurs merges, rebases et reverts créant un historique complexe.

git fetch vs git pull
fetch télécharge les modifications sans les fusionner. pull fait fetch puis merge automatiquement. fetch est préférable pour examiner les changements avant de les intégrer.

git reset vs git revert
reset supprime l'historique (destructif), revert crée un commit d'annulation (non-destructif). Utiliser reset --hard sur une branche partagée risque des pertes de données pour l'équipe.

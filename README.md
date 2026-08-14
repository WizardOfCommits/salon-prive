# Le Salon Privé · PWA

Roulette européenne 3D, 100% hors ligne une fois installée.

## Déploiement GitHub Pages
    git init -b main && git add -A && git commit -m "Salon Privé PWA"
    gh repo create salon-prive --public --source=. --push
    gh api -X POST repos/$(gh api user -q .login)/salon-prive/pages -f "source[branch]=main" -f "source[path]=/"

URL: https://VOTRE_LOGIN.github.io/salon-prive/

## iPhone
Safari → ouvrir l'URL → laisser charger un tour complet → Partager → Sur l'écran d'accueil.
Ensuite: fonctionne en mode avion.

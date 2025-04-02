---
layout: default
title: Bienvenue sur mon site !
---

# Bonjour, je suis Naxyn 👋

Bienvenue sur ma page GitHub Pages ! Je suis un passionné par d'IT, de Sécu , et d'Astro (oui oui Naxyrius, c'est en lien avec Sirius, une étoile )  
Voici une sélection de mes projets publics hébergés sur mon GitHub. Une première pierre à l'édifice !

---

## 🌟 À propos de moi

Je suis actuellement étudiant en TSSR et souhaite poursuivre en AIS ! 
Je travaille actuellement sur divers projets, et j'apprends à scripter quelques actions pour gagner du temps durant la création de mes labs
N'hésitez pas à explorer mes dépôts ci-dessous !

---

## 🚀 Mes Projets Publics 

- [Auto-Deploy](https://github.com/Naxyrius/auto_deploy) : mes scripts de déploiement semi-auto pour gagner du temps :)
- [Injection de users dans un AD](https://github.com/Naxyrius/user_injector_ad) : Script d'injection de users dans un AD, très utiles pour faire rapidement des tests


---

Et la totalités de mes repos ! 🐥

{% for repo in site.github.public_repositories %}
- [{{ repo.name }}]({{ repo.html_url }})  
  *{{ repo.description | default: "Pas de description disponible." }}*
{% endfor %}

---

Merci de visiter ma page ! Pour plus d'informations, consultez mon [profil GitHub](https://github.com/{{ site.github.owner_name }}).

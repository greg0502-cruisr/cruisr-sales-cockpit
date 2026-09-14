# Cruisr · cockpit de vente

Outils HTML autonomes, un fichier chacun, ouverts dans le navigateur pendant les appels.

| Fichier | Qui | Quand |
|---|---|---|
| `cockpit_coldcall_vXX.html` | SDR | Cold call, séquence de relance, courriels |
| `cockpit_fitcall_vXX.html` | SDR | Fit Call 15 min → brief pour le closer |

URL de base : `https://greg0502-cruisr.github.io/cruisr-sales-cockpit/` + nom du fichier

## Règles
- Le numéro de version est dans le nom du fichier. On ne modifie pas une version publiée : on dépose la nouvelle, on supprime l'ancienne, on envoie le nouveau lien.
- Le profil et les notes se sauvegardent dans le navigateur (localStorage), sur cet ordinateur seulement. Le CRM reste la source : « copier → CRM » ou « copier le brief » après chaque appel.
- Les notes de modif s'exportent par « copier les notes » et se collent dans ClickUp. C'est le canal pour améliorer les documents.
- Si l'URL de base change un jour, les sauvegardes locales ne suivent pas : exporter les notes avant.

## Utilisation
1. Régler industrie, âge, revenus à droite — le hook, les pains et les questions suivent.
2. Naviguer par situation : onglets 1-4 (cold call) · 1-2 (Fit Call), flèches ↑↓.
3. Cold call : bloc-notes pendant l'appel, « copier → CRM » après.
4. Fit Call : profil complet et drapeaux pendant l'appel, « copier le brief » après. « Coller les notes du cold call » recharge ce qui a déjà été capturé.
5. Un mot qui sonne faux, une objection qui manque : « + note de modif ».

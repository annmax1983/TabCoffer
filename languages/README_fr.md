# TabCoffer

Français | [English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Español](README_es.md)

Un gestionnaire de sessions d’onglets local-first. Enregistrez vos onglets ouverts dans un coffre nommé et retrouvez-les en un clic.

> Chrome · Edge · Firefox · Manifest V3 · Local-first · No account · No tracking

---

## Free vs Pro

| Fonctionnalité | Gratuit | Pro |
|----------------|---------|-----|
| Sessions enregistrées | **3** | 100 |
| Onglets par session | **20** | 200 |
| Enregistrer / restaurer en un clic | ✅ | ✅ |
| Renommer, supprimer, trier | ✅ | ✅ |
| Export JSON | ✅ | ✅ |
| Rechercher sessions et onglets | — | ✅ |
| Import JSON (fusion, dédup) | — | ✅ |
| Restauration : ignorer les doublons / seulement les onglets non ouverts | — | ✅ |

**Enregistrer, restaurer et exporter des sessions est gratuit et complet — la seule limite est de 3 sessions × 20 onglets.** Pro relève les plafonds et ajoute la recherche, l’import et deux options de restauration précise. La licence est facultative ; l’offre gratuite ne la demande jamais.

---

## How to use

1. Ouvrez les onglets que vous voulez garder ensemble.
2. Cliquez sur l’icône TabCoffer, saisissez un nom et choisissez **Enregistrer la session**.
3. Fermez les onglets : la session reste dans le coffre.
4. Plus tard, ouvrez le popup et choisissez **Ouvrir dans une nouvelle fenêtre** ou **Ajouter à cette fenêtre**.

---

## Privacy

Les sessions, titres, adresses et icônes restent dans `chrome.storage.local` de cet appareil. TabCoffer ne lit aucun contenu de page et n’envoie aucune analyse. La seule requête réseau est la vérification facultative de licence lors de l’activation de Pro, envoyée à `api.annmax1983.com` avec votre clé, un ID d’installation aléatoire et des métadonnées du navigateur — jamais vos sessions.

---

## Source

> Ce dépôt sert à la présentation du projet ; le code source complet n’est pas publié. Installez depuis les boutiques officielles.

---

## Licence

Get a licence: `https://annmax1983.com/checkout?plugin=tabcoffer`

Activate it: TabCoffer popup → ⚙ → enter the key.

Copyright © 2026 TabCoffer. All rights reserved. Closed source.

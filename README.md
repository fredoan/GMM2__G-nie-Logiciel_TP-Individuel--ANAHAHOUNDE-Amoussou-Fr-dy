# TP Individuel — Génie Logiciel

**Étudiant :** ANAHAHOUNDE Amoussou Frédy  
**Filière :** GMM2 — Génie Logiciel  
**Date :** Novembre 2026  
**Année académique :** 2025–2026

---

## 🎯 Contexte du TP

En 2025, l'UNSTIM a enregistré **4 cas de vol de moto**. La présidente des étudiants des universités a lancé un **hackathon** visant à concevoir un dispositif de **sécurisation de moto par démarrage biométrique**.

Le principe retenu : remplacer la clé mécanique par une **empreinte digitale**. Sans empreinte reconnue, le moteur ne peut pas démarrer.

Le travail demandé consiste à réaliser la modélisation du dispositif à travers **5 diagrammes UML** : cas d'utilisation, classes, activités, séquence et composants.

---

## 📌 Les 5 diagrammes UML

Tous les diagrammes sont accessibles via **un seul lien Lucid.app** :

👉 **[CLIQUEZ ICI POUR OUVRIR LES 5 DIAGRAMMES](https://lucid.app/lucidchart/5622a804-50cf-4e7f-96f3-127b52abae7a/edit)**

| # | Diagramme | Règle du cours respectée |
|---|---|---|
| 1 | Cas d'utilisation | Acteurs **hors du système** |
| 2 | Classes | Attributs + méthodes + relations |
| 3 | Activités | **2 niveaux de décision** (empreinte → compte actif) |
| 4 | Séquence | **Bloc `alt`** succès / échec |
| 5 | Composants | **3 couches** (équipement / traitement / données) |

---

## 🧩 Composants du dispositif et leurs rôles

| Composant | Rôle |
|---|---|
| **Lecteur biométrique** | Capturer l'empreinte et transmettre le résultat au système central |
| **Unité centrale** | Contrôler le flux et autoriser ou refuser le démarrage |
| **Antidémarrage** | Recevoir l'ordre du contrôle d'accès ; verrouillé, puis reverrouillé après démarrage |
| **Alarme** | Alerter les utilisateurs en cas d'intrusion |
| **Base de données** | Enregistrer les entrées (ID, date, heure) |

---

## 📋 Scénario pratique

1. L'utilisateur se présente devant la moto.
2. Il pose son doigt sur le lecteur biométrique.
3. L'unité centrale vérifie l'empreinte dans la base de données.
4. Si l'empreinte est reconnue, l'antidémarrage est déverrouillé.
5. L'accès est automatiquement enregistré dans la base.
6. À l'arrêt du moteur, l'antidémarrage se reverrouille.
7. En cas d'échec, l'accès est refusé et l'événement est journalisé.

---

## 🎁 Bonus — Chambre d'hôtel et petit-déjeuner

**Énoncé :** Une chambre d'hôtel plus petit-déjeuner coûte **160 £**. Le petit-déjeuner coûte **120 £ de moins** que la chambre. Décanter la somme des deux.

Posons :
- **C** = prix de la chambre
- **P** = prix du petit-déjeuner

Système :
```
C + P = 160
P = C − 120
```

Résolution :
```
C + (C − 120) = 160
2C = 280
C = 140 £
P = 140 − 120 = 20 £
```

Vérification : `140 + 20 = 160` ✓ et `140 − 20 = 120` ✓

**Résultat :**
- Chambre = **140 £**
- Petit-déjeuner = **20 £**
- Somme des deux = **160 £**

---

## 📄 Rapport complet

Le rapport complet est disponible dans le fichier **`GMM2__Génie_Logiciel_TP_Individuel__ANAHAHOUNDE_Amoussou_Frédy.pdf`** à la racine du dépôt.

Il contient :
- Page de garde
- Introduction et contexte
- Démarche méthodologique (analyse, composants, scénario)
- Modélisation UML (5 sections)
- Bonus résolu
- Conclusion

Le lien vers les diagrammes est répété dans le PDF avec un encadré **« CLIQUEZ ICI »**.

---

## 🔗 Accès rapide

**[▶ Ouvrir les 5 diagrammes sur Lucid.app](https://lucid.app/lucidchart/5622a804-50cf-4e7f-96f3-127b52abae7a/edit)**

**[📄 Télécharger le rapport PDF](GMM2__Génie_Logiciel_TP_Individuel__ANAHAHOUNDE_Amoussou_Frédy.pdf)**

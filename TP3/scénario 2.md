# 📄 **Fiche Scénario – Projet VERBATIM : IA de classification de tickets clients**

## 🧠 Contexte général

### 📍 Le projet

Vous êtes membres du projet **VERBATIM**, une solution d’**intelligence artificielle pour l’analyse sémantique et la classification automatique des tickets de support client**.

Objectif :

- Réduire le temps de tri et d’assignation des tickets entrants
- Accélérer la résolution des demandes clients
- Analyser les motifs récurrents de contact pour en extraire des recommandations business

Le projet est porté par le service client d’un grand groupe de télécom, avec une première version de l’outil **déjà livrée** et **en cours de déploiement dans 4 centres d’appel pilotes**.

---

### 👥 L’équipe projet

| Rôle                     | Nom / Fonction | Site          |
| ------------------------ | -------------- | ------------- |
| Responsable produit      | Théo           | Lyon (Client) |
| Data Scientist           | Hind           | Bordeaux      |
| Développeur API          | Hugo           | Nantes        |
| UX/UI Designer           | Mélanie        | Paris         |
| Responsable Support      | Célia          | Strasbourg    |
| Analyste métier          | Karim          | Lyon          |
| Chef de projet technique | Isabelle       | Paris         |

**Cadence projet :** bihebdomadaire – mise à jour toutes les 2 semaines
**Canaux :** Slack #verbatim-core / Docs sur Notion / Jira pour les tâches

---

## 📅 Situation actuelle

- La **v1 de l’outil est en production**, mais uniquement sur 2 centres pilotes
- Une **formation courte à l’outil a été faite**, mais peu suivie
- Plusieurs agents terrain ont commencé à **bypasser le système** et à classer les tickets manuellement
- Les résultats de classification sont bons (85 % de précision), mais **mal perçus sur le terrain**
- Certains superviseurs locaux disent **ne pas comprendre les règles de l’algorithme**
- Les tickets "ambiguës" ou "borderline" semblent mal traités, mais personne ne centralise les retours
- Les mises à jour de l’outil ont été communiquées par email, sans trace écrite claire dans le Notion

---

## 🧩 Tensions implicites

- Hind (data scientist) pense que "le problème vient surtout du manque d’adhésion".
- Hugo (dev) a intégré des règles correctives, mais n’a pas été consulté sur les retours utilisateurs.
- Karim (analyste métier) est inquiet car **aucun atelier de retour terrain** n’a encore été organisé.
- Théo (client) continue à dire que “les KPIs techniques sont bons”, mais semble **déconnecté de l’usage réel**.
- Célia (support) commence à perdre patience, car les superviseurs s’énervent et **remontent en direct les problèmes** à la DSI.

---

## 📂 Ressources disponibles

- Tableau de suivi Jira (mais incomplet)
- Guide utilisateur en PDF (v0.8)
- Fichiers d’étiquetage initial (training set annoté)
- Liste des incidents déclarés par mail (non structurée)
- Tableur Excel partagé avec les centres pilotes

---

# 📨 **Déclencheur de réunion – Projet VERBATIM**

## 🧭 Message de Isabelle (cheffe de projet technique)

> **Objet : Réunion spéciale – retours terrain & gouvernance classification** > **Date : \[à insérer selon la session]** > **Expéditeur :** Isabelle Roux (Cheffe de projet technique – VERBATIM)
> **Destinataires :** Équipe projet Verbatim + Théo (Responsable produit client)
> **Copie :** Célia (Support), Karim (Métier)

---

Bonjour à tous,

Nous avons désormais **2 semaines de recul sur le déploiement de VERBATIM** dans les centres pilotes.
Plusieurs éléments m’amènent à convoquer une réunion exceptionnelle :

---

## 🚨 Points de vigilance :

1. Plusieurs agents terrain **ignorent ou contournent l’outil** → à comprendre
2. Les superviseurs locaux **remontent leur incompréhension des critères de classement**
3. Les retours terrain sont **dispersés entre mails, Excel et Slack**, sans vision consolidée
4. Aucune synthèse de remontée des tickets “mal classés” n’a été formalisée
5. La documentation utilisateur reste partielle (v0.8, non versionnée)

---

## 🎯 Objectifs de la réunion

- **Faire le point sur les blocages terrain** et les retours utilisateurs
- Clarifier **qui collecte / analyse / intègre les feedbacks**
- Statuer sur les **prochaines mises à jour fonctionnelles**
- Mettre à jour la méthode de communication vers les centres pilotes
- Identifier les **zones grises** non couvertes par l’IA actuelle

---

📌 **Format proposé :**

- 45 min max
- Merci de désigner un animateur, un timekeeper, et un secrétaire
- Préparez en amont vos constats et vos propositions concrètes

Nous devons sortir de cette réunion avec **une vision claire du plan d’action**, et **un message à transmettre aux centres pilotes avant vendredi**.

Merci à tous pour votre engagement,
**Isabelle**

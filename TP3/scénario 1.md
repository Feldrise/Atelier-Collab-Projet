# 📄 **Fiche Scénario – Projet ATLAS : IA pour l’optimisation logistique**

## 🧠 Contexte général

### 📍 Le projet

Vous faites partie de l’équipe projet **ATLAS**, une solution d’**optimisation des tournées de livraison** pour un grand groupe de transport européen.
L’objectif est de développer une IA capable de :

- Proposer des trajets plus efficaces selon les contraintes terrain (trafic, fenêtres horaires, capacité des véhicules…)
- Réduire les coûts de carburant et le nombre de kilomètres parcourus
- Générer automatiquement un planning optimisé chaque matin

Ce projet est stratégique pour le client final (un opérateur de transport B2B), et fait l’objet d’un **pilote dans deux régions** avant déploiement national.

---

### 👥 L’équipe projet

| Rôle                   | Nom / Fonction              | Localisation   |
| ---------------------- | --------------------------- | -------------- |
| Chef de projet         | Marc (DSI groupe client)    | Paris          |
| Product Owner          | Clara (consultante externe) | Paris          |
| Développeurs IA        | Lucie & Sami                | Lyon           |
| DevOps & intégration   | Quentin                     | Nantes         |
| UX Designer            | Awa                         | Dakar (remote) |
| Testeuse fonctionnelle | Jade (junior)               | Paris          |
| Data analyst           | Youcef (alternant)          | Lyon           |

**Mode de travail :** hybride – réunions hebdos sur Teams, daily par Slack (canal #atlas-daily), documentation sur Notion.

---

## 📅 Avancement

- 🔁 **Sprint 4/6** en cours
- 🎯 MVP prévu dans 3 semaines
- ✅ Livraison initiale partielle réalisée, tests en cours
- 🚧 Plusieurs fonctionnalités critiques restent instables (gestion des retards, itinéraires multi-dépôts)

---

## ⚠️ Éléments récents à prendre en compte

1. Le client a **modifié plusieurs critères métier** (ajout de pénalités en cas de retard, nouvelle règle de chargement) → impact à clarifier.
2. Clara (PO) centralise les échanges client, mais n’a pas encore mis à jour le backlog partagé.
3. Les retours terrain des chauffeurs ont été **partagés par mail uniquement au chef de projet**, qui ne les a pas encore transmis à l’équipe.
4. Plusieurs bugs critiques sont identifiés mais **ne sont pas encore priorisés** dans Jira.
5. Awa (UX) a fait une **nouvelle proposition d’interface**, mais elle n’a été vue que par Lucie (informellement sur Slack).
6. La réunion d’équipe précédente a été **annulée**, faute de disponibilité du chef de projet et de Quentin.

---

## 📂 Ressources à disposition

- Backlog Jira partagé (mais peu mis à jour)
- Page Notion "Suivi projet ATLAS" (accès variable selon les rôles)
- Canal Slack #atlas-daily (actif mais peu structuré)
- Mail hebdo de Clara résumant les avancées (envoi le vendredi)

---

## 💬 Ambiance d’équipe

- Les échanges restent cordiaux, mais certaines tensions apparaissent :
  → Awa se sent peu consultée
  → Lucie pense que l'équipe avance "à l’aveugle"
  → Jade ne sait plus clairement quelles versions elle doit tester
  → Clara est très sollicitée et répond souvent avec 24–48h de délai

---

# 📨 **Déclencheur de réunion – Projet ATLAS**

## 🧭 Message de Clara (Product Owner)

> **Objet : Réunion d’alignement urgente – Sprint 4** > **Date : \[à insérer selon la session]** > **Expéditeur :** Clara Dupuis (PO)
> **Destinataires :** Équipe projet ATLAS
> **Copie :** Marc (Chef de projet), Quentin (Intégration), Jade (QA)

---

Bonjour à toutes et tous,

Je vous propose de **planifier rapidement une réunion d’équipe** suite à plusieurs remontées récentes. Voici un point synthétique :

---

## 🚨 Sujets critiques identifiés :

1. **Modifications de critères côté client** (retards, pénalités, volumes chargés) → à intégrer dans l’algorithme + à voir côté UX
2. **Interface proposée par Awa** : retours non encore centralisés
3. **Bugs fonctionnels** non priorisés → plusieurs tickets non catégorisés dans Jira
4. **Retours chauffeurs** reçus par Marc, mais pas encore partagés à tous
5. **Tests QA** en attente de clarification sur les versions valides

---

## 🎯 Objectifs de la réunion :

- Faire un point clair sur **ce qui est prêt / pas prêt**
- Identifier **ce qui doit remonter en priorité dans Jira**
- Clarifier **les prochaines étapes du sprint**
- Décider qui prend quoi en charge pour la suite

---

Je vous laisse **préparer un ordre du jour et proposer un déroulé efficace**. Nous avons **45 minutes maximum**.
Merci d’indiquer aussi **qui se propose comme animateur / secrétaire / timekeeper**.

> PS : Le client attend un livrable intermédiaire pour lundi prochain – donc il nous faut repartir synchronisés.

À très vite,
**Clara**

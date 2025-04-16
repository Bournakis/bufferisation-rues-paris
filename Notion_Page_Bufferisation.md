# Convertir les lignes de rues en zones géographiques (polygones) avec IA

🎯 **Objectif**  
Transformer un fichier `.geojson` contenant des lignes (rues) en polygones, exploitables dans une application ou une carte.

---

🧰 **Outil prêt à l’emploi**  
> Ouvrir ce notebook dans Google Colab pour tout faire sans coder :

🔗 [Ouvrir dans Google Colab](https://colab.research.google.com/github/nicolas-ai-tools/public-ai-tools/blob/main/Bufferisation_Rues_Paris.ipynb)  
📎 Ou télécharge ici : `Bufferisation_Rues_Paris.ipynb` (à importer ensuite dans Google Colab)

---

🧭 **Instructions pas à pas**

1. Cliquez sur **“Exécuter tout”** (`Ctrl + F9`)
2. Importez votre fichier `.geojson` contenant des **lignes de rues**
3. Le traitement automatique génère une **zone tampon** (≈ 6 m autour de chaque ligne)
4. Téléchargez le nouveau fichier `.geojson` contenant les **polygones des rues**

---

📂 **Exemples d’usage**
- Créer une zone géographique par rue à Paris
- Détection de présence d’un utilisateur dans une rue (via GPS)
- Affichage de **rues comme surfaces interactives** sur une carte

---

🧠 **Bonus**  
Ça fonctionne aussi avec :
- Chemins, pistes cyclables, canaux
- Zones de livraison, de patrouille, d’analyse géographique

---

🧩 **Fichier à importer dans Colab :**
- Bufferisation_Rues_Paris.ipynb

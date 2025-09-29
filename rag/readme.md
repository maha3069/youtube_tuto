# RAG Complet

## Regardez la video sur youtube 👇:
## Plan de Tuto:
**Installation:** Installer les bibliothèques nécessaires (groq, langchain, chromadb, pypdf).

**Clés API:** Saisir en toute sécurité les clés API Groq et Hugging Face.

**Préparation des données:**

Charger les données à partir d'un fichier PDF.

Diviser le document en morceaux plus petits (chunks).

Créer des embeddings pour les morceaux de texte.

Indexer les embeddings dans une base de données vectorielle ChromaDB.

**RAG - Étape 1: Récupération (Retriever):** Définir une fonction pour récupérer les morceaux de document pertinents en fonction d'une requête.

**RAG - Étape 2: Augmentation:** Créer un modèle de prompt pour augmenter la requête avec le contexte récupéré.

**RAG - Étape 3: Génération:**

Initialiser un modèle linguistique (LLM) à l'aide de Groq.

Générer une réponse à l'aide du prompt augmenté et du LLM.

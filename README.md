# MasterDeck: Multilingual Core Vocabulary Dataset

A comprehensive, curated linguistic dataset designed to provide open access to core vocabulary across major world and auxiliary languages, structured for language acquisition, spaced repetition systems (SRS), and computational linguistics.

---

## 1. Overview & Philosophy

Language learning should not be restricted behind proprietary paywalls. The core building blocks of human communication belong to humanity.

This dataset focuses on high-impact frequency lexicons. Linguistic research consistently shows that mastering the core ~2,000 to ~9,000 most frequent lemmas allows a learner to comprehend **upwards of 95% of daily conversations, media, and general literature**.

---

## 2. Dataset Partitions & Interactive GitHub Previews

To enable fast loading and seamless interactive table rendering directly within GitHub's web interface without file size limits, the dataset is split into modular 2-level partitions alongside the consolidated master file:

| Partition File | Levels Included | Cards Count | Approximate CEFR Stage | Pedagogical Scope |
| :--- | :--- | :--- | :--- | :--- |
| [`masterDeck_level_00_01.tsv`](./masterDeck_level_00_01.tsv) | Level 0 & 1 | 142 | **A1 (Introductory / Survival)** | Essential survival phrases, fundamental greetings, politeness markers, and core numbers. |
| [`masterDeck_level_02_03.tsv`](./masterDeck_level_02_03.tsv) | Level 2 & 3 | 891 | **A1 - A2 (Foundational)** | Routine nouns, common adjectives, immediate surroundings, and high-frequency action verbs. |
| [`masterDeck_level_04_05.tsv`](./masterDeck_level_04_05.tsv) | Level 4 & 5 | 1,976 | **A2 (Elementary)** | Daily routine interactions, workplace basics, travel navigation, and standard social exchanges. |
| [`masterDeck_level_06_07.tsv`](./masterDeck_level_06_07.tsv) | Level 6 & 7 | 1,814 | **B1 (Intermediate Threshold)** | Conversational independence, narrative recounting, personal perspectives, and practical communication. |
| [`masterDeck_level_08_09.tsv`](./masterDeck_level_08_09.tsv) | Level 8 & 9 | 1,661 | **B1 - B2 (Independent User)** | Expanding contextual vocabulary, descriptive versatility, expressing opinions, and idiomatic basics. |
| [`masterDeck_level_10_11.tsv`](./masterDeck_level_10_11.tsv) | Level 10 & 11 | 250 | **B2 (Upper Intermediate)** | Technical clarity, structured debate, abstract concepts, and nuanced conversational flow. |
| [`masterDeck_level_12_13.tsv`](./masterDeck_level_12_13.tsv) | Level 12 & 13 | 636 | **B2 - C1 (Advanced Vantage)** | Specialized terminology, formal registers, social commentary, and varied syntactic structures. |
| [`masterDeck_level_14_15.tsv`](./masterDeck_level_14_15.tsv) | Level 14 & 15 | 453 | **C1 (Effective Operational)** | Complex professional and academic vocabulary, subtle distinction of registers, and figurative speech. |
| [`masterDeck_level_16_17.tsv`](./masterDeck_level_16_17.tsv) | Level 16 & 17 | 916 | **C1 - C2 (Proficiency)** | Deep thematic fluency, cultural idioms, advanced discourse markers, and fine-grained synonyms. |
| [`masterDeck_level_18_19.tsv`](./masterDeck_level_18_19.tsv) | Level 18 & 19 | 222 | **C2 (Mastery)** | Near-native idiomatic mastery, rare expressions, literary nuances, and academic precision. |
| [`masterDeck_level_20.tsv`](./masterDeck_level_20.tsv) | Level 20 | 63 | **C2+ (Native Precision)** | Highly specialized lexis, refined communicative mastery, and subtle stylistic nuances. |
| [`masterDeck_full.tsv`](./masterDeck_full.tsv) | **Levels 0 to 20 (Full)** | **9,025** | **Complete Dataset** | Full consolidated dataset for bulk data processing, machine learning, and database seeding. |

---

## 3. Schema & Column Specifications

Each `.tsv` file follows a canonical 21-column tabular structure:

- **`ID`**: Unique 5-digit zero-padded identifier (e.g. `00001`, `00002`).
- **`Category`**: Thematic domain or communicative topic (e.g. `Basics`, `Politeness`, `Everyday Phrases`, `Shopping`, `Numbers`, `Home & Furniture`).
- **Base Lemmas / Lexemes**:
  - `EN`: English
  - `DE`: German
  - `ES`: Spanish
  - `FR`: French
  - `IT`: Italian
  - `PT`: Portuguese
  - `CA`: Catalan
  - `EO`: Esperanto
  - `IA`: Interlingua
- **Contextual Example Sentences**:
  - `txt_en`, `txt_de`, `txt_es`, `txt_fr`, `txt_it`, `txt_pt`, `txt_ca`, `txt_eo`, `txt_ia`: Natural example sentences illustrating practical usage in context.
- **`Level`**: Relative proficiency ranking integer from `0` to `20`.

---

## 4. Open License (MIT)

This project is licensed under the **MIT License**. You are completely free to:
- Use this dataset in commercial and non-commercial applications.
- Modify, expand, subset, and transform the data into any format (JSON, SQL, CSV, Anki, etc.).
- Integrate it into SRS algorithms, flashcard apps, AI training pipelines, or dictionaries.

---

*Curated and shared freely with the global community by*  
**LearnMaster5**

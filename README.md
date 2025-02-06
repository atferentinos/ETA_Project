# ETA_Project

# Analysis of Classical Greek and Roman Works
*A Text Analytics Study by Alexandra Ferentinos*

## Project Overview
This study applies exploratory text analytics methods to analyze patterns across nine classical Greco-Roman works, examining how different literary genres employ distinct narrative strategies and emotional patterns.

## Dataset
- **Source**: Project Gutenberg digital library
- **Corpus Size**: 9 classical works
- **Categories**:
  - Epic Poetry (The Iliad, The Odyssey, The Aeneid, Metamorphoses, Argonautica)
  - Drama (Sophocles' plays, Euripides' Medea, Aristophanes' Lysistrata)
  - Historical texts (Hesiod's works)

## Methods Used
- TFIDF Analysis
- Topic Modeling (LDA)
- Principal Component Analysis (PCA)
- Hierarchical Clustering
- Word Embeddings
- VADER Sentiment Analysis

## Key Findings
1. **Genre-Specific Vocabulary**:
   - Epic Poetry: frequent use of terms like "gods", "fate", "heroes"
   - Drama: high frequency of "chorus", "revenge", "women"
   - Historical: more generic term usage

2. **Sentiment Patterns**:
   - Epic works: Initial positive progression followed by decline
   - Dramatic works: Sporadic changes with multiple sentiment crossovers
   - Historical texts: Consistent emotional tone throughout

3. **Thematic Clusters**:
   - Domestic life
   - God-mortal interactions
   - Warfare/strategy

## Project Structure

```bash
final_project/
├── Project_Deliverables/
│   ├── Source_Files/
│   ├── Data_Files/
│   ├── PCA_Outputs/
│   └── Final_Project.ipynb
```

## Technical Implementation
- Text preprocessing including tokenization and stop word removal
- Implementation of various text analysis techniques
- Visualization of results through heatmaps, dendrograms, and sentiment graphs

## Conclusions
The analysis demonstrates that classical works implement distinct narrative storytelling strategies and emotional patterns based on their genre, with clear differentiation between epic, dramatic, and historical works.

## Future Work
The study suggests that further research with a larger corpus could reveal additional nuances in the patterns exhibited in classical works.

*Note: This project was completed as part of course DS5001.*

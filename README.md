# Cultural Bias in CLIP: A Probing Analysis

This repository contains code, data preprocessing scripts, and visualizations for the paper titled:  
**“Cultural Bias in CLIP: A Probing Analysis Using Cross-Modal Embeddings”**

We investigate how CLIP encodes cultural bias within its latent space using two complementary probing tasks:  
1. **Image–Image Similarity**  
2. **Text–Image Alignment** (Caption–Association Score, C–ASC)

## 📊 Visualizations

- **UMAP projections** of image and caption embeddings per concept:  
  Located in: `visualizations/umap_projections/`

- **Image–Image cosine similarity heatmaps**:  
  Located in: `CSSameConceptImg/`

- **C–ASC + Image Similarity joint analysis barplot**:  
  Located in: `figures/casc_similarity_barplot.png`

- **Global Text–Image alignment map**:  
  Located in: `figures/global_alignment_map.png`

---

All core analyses are performed in the Jupyter notebook: `EECE570.ipynb`
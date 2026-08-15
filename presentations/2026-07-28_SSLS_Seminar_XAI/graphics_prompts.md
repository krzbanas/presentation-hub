# Prompts for Generating Presentation Graphics

> **Purpose:** This file contains ready-to-use prompts for AI image generators
> (e.g., DALL·E, Midjourney, Stable Diffusion) to create all non-code graphics
> needed for the presentation *"AI & Explainable AI for Spectroscopic and
> Chemical Mapping Data."*
>
> For data-driven plots (PCA, UMAP, confusion matrices, etc.), the R/ggplot2
> code is embedded directly in the `.qmd` file. The prompts below cover
> conceptual diagrams, background images, and illustrations.

---

## 1. Title Slide Background

```
Prompt:
Create a wide-format (16:9) abstract scientific illustration blending spectroscopy
and artificial intelligence. Show stylised infrared absorption spectra as flowing
colourful wave lines merging into a neural network graph with glowing nodes and
edges. Use a dark navy-blue (#2c3e50) background with vibrant accent colours:
teal, orange, and violet. The mood should be modern, clean, and professional.
No text. High resolution, 1920×1080 px.
```

---

## 2. Section Divider — "Foundations"

```
Prompt:
A minimalist wide banner image (16:9) for a presentation section titled
"Foundations." Show an abstract representation of a data matrix being decomposed:
a large grid of coloured cells on the left, an equals sign, and two smaller
factor matrices on the right. Use muted blues and greys on a dark charcoal
background. No text. Clean geometric style. 1920×1080 px.
```

---

## 3. Section Divider — "Dimension Reduction"

```
Prompt:
Abstract scientific illustration (16:9) representing dimension reduction. Show a
dense cloud of data points in a 3-D coordinate system on the left, with an arrow
pointing to a clean 2-D scatter plot on the right where clusters are clearly
visible. Use a purple (#8e44ad) gradient background. Geometric, vector-art style.
No text. 1920×1080 px.
```

---

## 4. Section Divider — "Clustering & Grouping"

```
Prompt:
Wide-format illustration (16:9) of data clustering. Show scattered dots in
various colours forming distinct groups connected by thin edges or Voronoi
boundaries. Use a green (#27ae60) gradient background. Include subtle dendrogram
branches in the background. Flat design, modern data-science aesthetic. No text.
1920×1080 px.
```

---

## 5. Section Divider — "Building Models"

```
Prompt:
Abstract banner (16:9) representing supervised machine learning. Show a stylised
decision boundary separating two classes of data points (circles and triangles),
with a neural network architecture faintly visible in the background. Use a warm
orange (#d35400) gradient background. Modern, geometric, professional. No text.
1920×1080 px.
```

---

## 6. Section Divider — "Explainable AI"

```
Prompt:
Illustration (16:9) representing Explainable AI / opening the black box. Show a
dark opaque cube (the "black box") being opened or becoming transparent to reveal
colourful gears, graphs, and feature-importance bars inside. Use a purple
(#8e44ad) gradient background. Clean vector style. No text. 1920×1080 px.
```

---

## 7. Conceptual Diagram — SHAP Waterfall (Illustrative)

```
Prompt:
Create a clean, publication-quality waterfall chart illustration showing SHAP
value contributions. Start from a base value on the left, then show horizontal
bars pushing the prediction higher (in red/coral) or lower (in blue/teal).
Label the bars with generic feature names like "Feature A", "Feature B", etc.
White background, large readable font (18pt+), axis labels in bold. Style:
scientific figure, no decorations. 1200×600 px.
```

---

## 8. Conceptual Diagram — LIME Local Explanation (Illustrative)

```
Prompt:
Illustration of the LIME explanation concept. Show a complex, wavy non-linear
decision boundary in grey, with a single data point highlighted in red. Around
that point, show a dashed circle (the local neighbourhood) and within it a
straight dashed line representing the local linear approximation. Scattered data
points in two colours (blue and orange). White background, clean vector style,
large labels. 1200×600 px.
```

---

## 9. Honey Case Study — Conceptual Header

```
Prompt:
Wide photograph-style image (16:9) of honey jars from different countries
arranged on a laboratory bench next to an FTIR spectrometer. The jars have
labels showing different country flags (Argentina, New Zealand, Ukraine, China,
Greece, Canada). Warm lighting, shallow depth of field. Professional lab
setting. No text overlay. 1920×1080 px.
```

---

## 10. Tooth Cross-Section — Conceptual Header

```
Prompt:
Microscopy-style image (16:9) of a human tooth cross-section showing distinct
layers: enamel (translucent outer layer), dentin (yellowish inner layer), and
the dentin-enamel junction between them. Add subtle false-colour overlay
suggesting spectroscopic mapping. Scientific illustration style with labels
pointing to each layer. Dark background. 1920×1080 px.
```

---

## 11. Halobates — Conceptual Header

```
Prompt:
Scientific illustration (16:9) of a Halobates (ocean strider / sea skater)
insect viewed from above, with a false-colour elemental map overlay showing
different anatomical regions in different colours (head in blue, body in green,
legs in red, internal organs in yellow). Dark ocean-blue background. Style:
scientific figure / electron microscopy aesthetic. No text. 1920×1080 px.
```

---

## 12. Analytical Pipeline Flowchart (Alternative to Mermaid)

```
Prompt:
Create a horizontal flowchart with 6 connected rounded-rectangle boxes in a
clean infographic style. The boxes are labelled: "Raw Data" → "Pre-processing"
→ "Dim. Reduction" → "Clustering / Classification" → "Evaluation" → "XAI".
Each box has a distinct colour: blue, green, purple, orange, red, teal.
Arrows connect them left to right. White background, bold sans-serif font,
large text. Flat design. 1600×400 px.
```

---

## 13. Timeline of AI in Spectroscopy (Alternative to ggplot2)

```
Prompt:
Create a horizontal timeline infographic spanning from 1966 to 2023. Place
milestone markers at: 1966 (Nearest Neighbour), 1980 (PLS), 1986
(Backpropagation), 1995 (SVM), 1998 (Random Forest), 2001 (Isomap/LLE),
2006 (Deep Belief Networks), 2008 (t-SNE), 2014 (GANs/VAEs), 2016 (SHAP),
2018 (UMAP), 2020 (Transformers), 2023 (Foundation Models). Colour-code by
category: Classification (red), Regression (blue), Deep Learning (green),
Ensemble (orange), Dimensionality Reduction (purple), Explainability (brown).
Clean infographic style, white background, large bold labels. Alternate labels
above and below the timeline to avoid overlap. 1920×600 px.
```

---

## 14. PCA Decomposition Equation Illustration

```
Prompt:
Mathematical illustration showing matrix decomposition X = T × P^T + E.
Show matrix X as a large coloured grid (samples × variables), equals sign,
then T (tall narrow matrix, blue), times P-transpose (wide short matrix,
green), plus E (same size as X, faded grey). Label dimensions: n (samples)
and p (variables) on X, n × k on T, k × p on P^T. White background, clean
geometric style, bold labels. 1200×500 px.
```

---

## 15. Cross-Validation Diagram

```
Prompt:
Illustration of 5-fold cross-validation. Show 5 horizontal bars, each divided
into 5 equal segments. In each bar, one segment is coloured red (test fold)
and the remaining four are blue (training folds). The red segment shifts one
position to the right in each successive bar. Label "Fold 1" through "Fold 5"
on the left. Add arrows showing "Train" and "Test" labels. Clean infographic
style, white background, large bold labels. 1200×500 px.
```

---

## 16. Confusion Matrix Template (Illustrative)

```
Prompt:
Create a 4×4 confusion matrix heatmap illustration. Rows labelled "True Class
A/B/C/D", columns labelled "Predicted Class A/B/C/D". Diagonal cells are
bright green with high numbers (e.g., 45, 38, 42, 40). Off-diagonal cells
are pale with low numbers (0-3). Include a colour bar on the right going
from white (0) to green (45). Bold labels, white background, publication
quality. 800×700 px.
```

---

## 17. SHAP Beeswarm Plot (Illustrative)

```
Prompt:
Create an illustrative SHAP beeswarm/summary plot. Vertical axis lists 10
features ("Wavenumber 1050", "Wavenumber 1650", etc.). Horizontal axis shows
SHAP value from negative to positive. Each feature has a row of scattered
dots coloured on a blue-to-red gradient (blue = low feature value, red = high
feature value). Features are ordered by importance (most important at top).
White background, large bold labels, clean scientific style. 1000×700 px.
```

---

## 18. Autoencoder Architecture Diagram

```
Prompt:
Diagram of an autoencoder neural network for spectral data. Show an input
layer (wide, labelled "Spectrum — 1800 variables"), progressively narrower
hidden layers forming a bottleneck (labelled "Latent Space — 10 variables"),
then progressively wider layers leading to an output layer (same width as
input, labelled "Reconstructed Spectrum"). Symmetric hourglass shape. Nodes
connected by lines. Colour gradient from blue (input) through purple
(bottleneck) to green (output). Dark background, clean vector style. No
text other than labels. 1400×600 px.
```

---

## 19. Grad-CAM Spectral Saliency Map (Illustrative)

```
Prompt:
Illustration of Grad-CAM applied to a 1-D spectrum. Top panel: a black line
showing an infrared spectrum (x-axis: wavenumber 4000–400, y-axis: absorbance).
Bottom panel: a heatmap bar below the spectrum showing saliency (importance)
as a colour gradient from blue (low importance) to red (high importance),
with red hotspots at specific peak positions. White background, bold axis
labels, publication quality. 1200×500 px.
```

---

## 20. NMF Unmixing Diagram

```
Prompt:
Illustration of Non-negative Matrix Factorisation for spectral unmixing.
Left: a mixed spectrum (black line with multiple overlapping peaks). Arrow
pointing right to three separate "pure component" spectra (red, green, blue
lines, each with distinct peaks) and their corresponding concentration maps
(small coloured spatial maps). Label: "X ≈ W × H". White background, clean
scientific illustration, large labels. 1400×600 px.
```

---

# Notes on Usage

1. **Aspect ratio:** All section dividers should be 16:9 (1920×1080) to match
   the Revealjs slide dimensions.

2. **Colour consistency:** Use the presentation's colour palette:
   - Dark navy: `#2c3e50`
   - Red: `#e74c3c`
   - Green: `#27ae60` / `#2ecc71`
   - Blue: `#3498db`
   - Purple: `#8e44ad` / `#9b59b6`
   - Orange: `#e67e22` / `#d35400`
   - Teal: `#1abc9c` / `#16a085`

3. **Font:** If the generator supports font specification, request bold
   sans-serif fonts (e.g., Inter, Helvetica, or Arial) at 18pt+ for all labels.

4. **No text on backgrounds:** Section divider images should have no text —
   the Revealjs slide will overlay the title text.

5. **File naming convention:**
   - `bg_title.png`
   - `bg_foundations.png`
   - `bg_dimreduction.png`
   - `bg_clustering.png`
   - `bg_models.png`
   - `bg_xai.png`
   - `diag_shap_waterfall.png`
   - `diag_lime_concept.png`
   - `diag_pipeline.png`
   - `diag_cv.png`
   - `diag_confusion.png`
   - `diag_autoencoder.png`
   - `diag_gradcam.png`
   - `diag_nmf.png`
   - `photo_honey.png`
   - `photo_tooth.png`
   - `photo_halobates.png`
   - `diag_pca_decomp.png`
   - `diag_shap_beeswarm.png`
   - `diag_timeline.png`

6. **To add generated images to the presentation:** Place the image files in
   the same directory as `ai_xai_spectroscopy.qmd` and reference them with:
   ```
   ## Slide Title {background-image="bg_title.png" background-size="cover"}
   ```
   or inline:
   ```
   ![Caption](diag_shap_waterfall.png){width="80%"}
   ```

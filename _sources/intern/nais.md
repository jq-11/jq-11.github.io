# Agriculture and Agri-Food Canada (AAFC)

From May to August 2025, I worked at **Agriculture and Agri-Food Canada (AAFC)** as a **Data Science Student & Geospatial Data Analyst**. 

I specifically worked under the National Agroclimate Information Service (NAIS) to work on drought prediction across Canada using various maching learning techniques.

I worked on various projects, shown below!

## PCA

I used Principal Component Analysis (PCA) on sample drought to test its efficacy. The implementation is on my [GitHub](https://github.com/jq-11/PCA_nais).

I then presented about PCA to a scientific research audience, and the presentation is provided below.

```{warning}
This presentation does not have proper citations; only links are provided.
```

<iframe src="../_images/Principal_Component_Analysis_(PCA).pdf" width="100%" height="600px">
  Your browser does not support PDFs. <!-- This will appear as alt text (or at least it should) -->
  <!-- Note: have to explicitly add the pdf to _build/_images -->
</iframe>

As seen in the presentation, I also began investigating  using UMAP, SVM, and an Autoencoder neural network in
TensorFlow.

```{note}
I recently presented this at BrainHacks Toronto 2026!
```

## XGBoost Drought Prediction Workflow

I fixed a broken pre-existing Python machine learning workflow (Snakemake) to predict drought using Random Forest and XGBoost.

The predictions were with respect to the [Canadian Drought Monitor](https://agriculture.canada.ca/en/agricultural-production/weather/canadian-drought-monitor).
Go through the data (images and meta-data) that you have available to understand what's available to you. For example:

    What types of diagnoses are there, and how do they relate to each other? You can use Google Scholar or other sources, to learn more background about these diagnoses.
    Is there some missing data? Are there images of low quality? Etc.

Write a summary about your findings in a single groupXX_summary.md file:

    This can just be plain text document of 1-2 pages with text and some headings. Do not forget to add your sources/references.
    Do not worry about the format too much, since later in the report course we will use LaTeX
    It is a requirement that each group member makes non-trivial updates to this file


As a data science student working with the PAD-UFES-20 dataset for skin cancer labeling and future prediction, understanding the context and characteristics of this dataset is crucial. Here’s an analysis based on the provided summary:
Diagnoses Types and Their Relations

The dataset includes six types of skin lesions, categorized into three skin cancers (Basal Cell Carcinoma - BCC, Melanoma - MEL, Squamous Cell Carcinoma - SCC including Bowen’s Disease - BOD) and three skin diseases (Actinic Keratosis - ACK, Nevus - NEV, Seborrheic Keratosis - SEK).

    BCC is the most common form of skin cancer, characterized by slow growth and seldom metastasizes but can cause significant local damage if not treated.
    MEL is the most aggressive skin cancer, known for its high potential for metastasis and mortality if not detected early.
    SCC, including BOD as an early form or SCC in situ, is a skin cancer that can metastasize if left untreated, especially in its more advanced forms.
    ACK is a precancerous condition that can evolve into SCC, representing a critical stage for intervention to prevent progression to invasive cancer.
    NEV and SEK are benign conditions, with nevi (moles) sometimes being precursors to melanoma under specific conditions.

These diagnoses are related through a continuum of skin changes, from benign conditions that may serve as indicators of skin health, to precancerous lesions that signify a higher risk of developing into invasive cancers. This spectrum is crucial for training predictive models, as it allows for the identification of features that differentiate between lesion types, especially in early-stage versus late-stage cancers.
Data Completeness and Quality Concerns

    Missing Data: The summary does not explicitly mention missing data, but in large datasets, particularly those involving clinical features and imaging, some degree of missingness is expected. This could be in the form of incomplete patient information, missing values for certain clinical features, or absent metadata. Handling missing data through imputation or exclusion methods will be necessary to prepare the dataset for analysis.

    Image Quality Variability: The dataset comprises images collected using various smartphone devices, leading to variability in image sizes and potentially in quality. This variability can pose challenges in model training, particularly for deep learning approaches that require consistent input sizes and quality. Techniques such as image preprocessing, normalization, and augmentation might be needed to mitigate these issues.

    Biopsy-Proven Diagnoses: Approximately 58% of the samples are biopsy-proven, providing a high confidence level for these diagnoses. However, the remaining portion based on clinical diagnosis by consensus might introduce variability in diagnosis accuracy. This aspect is crucial when considering the ground truth for model training, as the reliability of labels directly impacts model performance. Stratifying the dataset into biopsy-proven and clinically diagnosed cases for separate analysis or using it as a feature in prediction models could be beneficial.

Ethical Considerations

Working with human subject data mandates strict adherence to ethical guidelines, which the dataset complies with through approvals and patient consent. Maintaining patient privacy and data security is paramount, especially when dealing with sensitive health information. Any further use of this data for research or application development should continue to prioritize these ethical considerations.
Tetiana:

We have been trying to detect skin cancer in the provided photos.

Mariia:

Katya:


As a team of students , we have been conducting project on the PAD-UFES-20 dataset, which involves analyzing and labeling lesions in order to predict skin cancer.

The dataset includes six types of skin lesions, categorized into three skin cancers (Basal Cell Carcinoma - BCC, Melanoma - MEL, Squamous Cell Carcinoma - SCC including Bowen’s Disease - BOD) and three skin diseases (Actinic Keratosis - ACK, Nevus - NEV, Seborrheic Keratosis - SEK).

BCC is the most common form of skin cancer, characterized by slow growth and seldom metastasizes but can cause significant local damage if not treated.
MEL is the most aggressive skin cancer, known for its high potential for metastasis and mortality if not detected early.
SCC, including BOD as an early form or SCC in situ, is a skin cancer that can metastasize if left untreated, especially in its more advanced forms.
ACK is a precancerous condition that can evolve into SCC, representing a critical stage for intervention to prevent progression to invasive cancer.
NEV and SEK are benign conditions, with nevi (moles) sometimes being precursors to melanoma under specific conditions.

These diagnoses are related through a continuum of skin changes, from benign conditions that may serve as indicators of skin health, to precancerous lesions that signify a higher risk of developing into invasive cancers. This spectrum is crucial for training predictive models, as it allows for the identification of features that differentiate between lesion types, especially in early-stage versus late-stage cancers.
Data Completeness and Quality Concerns

Image Quality Variability: The dataset comprises images collected using various smartphone devices, leading to variability in image sizes and potentially in quality. This variability can pose challenges in model training, particularly for deep learning approaches that require consistent input sizes and quality. But during processing our photos we managed to label even low-quality photos.

Biopsy-Proven Diagnoses: Approximately 58% of the samples are biopsy-proven, providing a high confidence level for these diagnoses. However, the remaining portion based on clinical diagnosis by consensus might introduce variability in diagnosis accuracy. This aspect is crucial when considering the ground truth for model training, as the reliability of labels directly impacts model performance. Stratifying the dataset into biopsy-proven and clinically diagnosed cases for separate analysis or using it as a feature in prediction models could be beneficial.


Tetiana:

We have been trying to detect skin cancer in the provided photos.

The given dataset contains images with various types of lesions, including Basal Cell Carcinoma (BCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Melanoma (MEL), and Nevus (NEV) on different body regions, such as hand, face, arm, forearm, thigh, back, chest, lip, foot, and nose. 
The dataset patients age ranges from 27 to 90 years old, originating from diverse regions including Pomerania, Germany, Italy, and Brazil. The wide age range and varied lesion locations emphasize the need for personalized treatment approaches considering both patient demographics and lesion characteristics. Additionally, the presence of both benign and malignant lesions underscores the importance of accurate diagnosis for optimal treatment.
From csv data we can also note that:
-	Some patients have reported smoking and alcohol consumption. 
-	Some lesions have undergone biopsy for definitive diagnosis. 
-	A variety of lesion types indicates the need for precise diagnostic methods for effective treatment. 
-	Several patients have a history of skin cancer. 
-	Some lesions, such as SCC and MEL, are considered high-risk and may require more intensive monitoring and treatment.
However, it is important to note that some records lack complete patient background information. Additionally, duplicate entries exist, which may represent follow-up visits or multiple lesions from the same person.


Mariia:
First of all, the images investigated by me included patients from various regions, including Germany, Pomerania, Italy, Brazil, and other unspecified regions.
Lesions were placed in diverse body regions, including the face, neck, nose, ear, forearm, back, scalp, chest, abdomen, and hand. Their types vary, with Basal Cell Carcinoma (BCC), Actinic Keratosis (ACK), Nevus (NEV) being the most common through my part of given images. 
Characteristics like itching, bleeding, growth, and changes in lesions were present in different cases.
From the given dataset it is also notable that:
-	Living conditions, such as access to piped water and sewage systems, may vary and can be relevant to health considerations.
-	Not all lesions have undergone biopsy, limiting the dataset's diagnostic information.
-	A significant number of patients have a history of skin cancer.
-	Patients from different regions exhibit distinct patterns of skin lesions, potentially influenced by environmental factors and sun exposure.
-	Smoking and alcohol consumption are reported as risk factors for skin cancer in some cases.
-	Pesticide exposure is noted in one instance.
It is also important to note that some records have incomplete information, particularly regarding patient background and lesion characteristics. 

Katya:

Based on the provided data, we have been analyzing a dataset aimed at detecting skin cancer in photos. The dataset includes various types of skin lesions, such as Basal Cell Carcinoma (BCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Melanoma (MEL), and Nevus (NEV). Lesions are located on different body regions, including the hand, face, arm, forearm, thigh, back, chest, lip, foot, and nose. We can get the following information from this dataset:
-	Patients in the dataset vary in age, ranging from 20 to 94 years old.
-	The dataset includes patients from different regions, mainly Pomerania, Germany, Italy, and Brazil.
-	Some patients have reported smoking and alcohol consumption, factors that may influence skin health.
-	The presence of both benign and malignant lesions suggests the need for precise diagnostic methods to determine optimal treatment plans.
-	Several patients in the dataset have a history of skin cancer, indicating the importance of ongoing monitoring and follow-up.
-	Incomplete patient background information in certain records hinders a comprehensive analysis of those cases.
-	Duplicate entries may indicate follow-up visits or the presence of multiple lesions in the same individual.

Andreea:

The dataset presented a wide range of images featuring skin lesions on individuals from various backgrounds, different ages, genders, and lifestyle choices, such as smoking and alcohol use. Some of the patients had a prior history of cancer, and some were subjected for biopsy. The lesions documented in these images were diverse, differing in size, shape, colors, having smooth or textured borders and situated on different body parts such as face, forearms, hands, thighs. The primary challenge in annotating these images was the accurate identification of the lesions. While some images appeared entirely normal, others had plenty of abnormalities that proved a hard time to identify.

Based on the analysis of the dataset, here are the conclusions drawn from the available information:
- The dataset contains more males than females.
- The most common locations for lesions are as follows:
  - Face: 18.30% of the analysed dataset.
  - Forearm: 14.36% of the analysed dataset.
  - Chest: 11.02% of the analysed dataset.
  - Approximately 58% of the subjects did not have a history of previous skin cancer.
  - More than half of the subjects reported neither drinking and smoking.
  - Approximately 59% of the subjects were prescribed for biopsy.



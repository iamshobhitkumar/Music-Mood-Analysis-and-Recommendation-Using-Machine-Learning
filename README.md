# Music Mood Analysis and Recommendation Using Machine Learning

## Overview

This project explores music mood analysis using machine learning techniques to identify the mood of music tracks based on their audio features. The project aims to enhance music listening experiences through personalized, mood-centric recommendations and to contribute to the growing field of music analysis.

## Authors

- Dev Thakkar - [dev20052@iiitd.ac.in](mailto:dev20052@iiitd.ac.in)
- Hiren Arvind K. - [hiren20066@iiitd.ac.in](mailto:hiren20066@iiitd.ac.in)
- Sahil Deshpande - [sahil20114@iiitd.ac.in](mailto:sahil20114@iiitd.ac.in)
- Shobhit Kumar - [shobhit20334@iiitd.ac.in](mailto:shobhit20334@iiitd.ac.in)

## Project Statement

Music has a profound influence on human emotion. With the advent of machine learning technologies, it's now possible to analyze music beyond traditional genres, delving into mood and emotion recognition. This project focuses on identifying the mood of music tracks using traditional machine learning techniques, enriching the user experience through mood-centric recommendations.

## Features

- **Music Mood Analysis:** Identifies the mood of a song using audio features.
- **Machine Learning Models:** Utilizes Random Forest and Gradient Boosting algorithms.
- **Feature Extraction:** Extracts key audio features using the Spotify API.
- **Semi-Supervised Learning:** Utilizes pseudo-labeling for enhanced accuracy.
- **Music Recommendation:** Recommends songs based on mood similarity.

## Datasets

- **Labeled Dataset:** Publicly available on Kaggle, this dataset includes songs annotated with mood labels.
- **Unlabeled Dataset:** Extracted using the Spotify API, this dataset includes audio features without mood labels.

## Methodology

1. **Feature Extraction:** Extracted nine musical features from the datasets.
2. **Model Training:** Trained and evaluated various machine learning models, including RidgeClassifier, SVM, and XGBoost.
3. **Semi-Supervised Learning:** Generated pseudo-labels for the unlabeled dataset using an ensemble of classifiers.
4. **Model Evaluation:** Evaluated the models using five-fold cross-validation.

## Usage

1. **Music Recommendation:** The user inputs a Spotify song link that represents their current mood. The system classifies the mood and recommends similar songs.

## Results

- **Accuracy:** The Random Forest and Gradient Boost models achieved an accuracy of over 92%.
- **Feature Importance:** Valence, energy, and danceability were the most influential features in predicting mood.

## Conclusion

This project successfully implemented a music mood analysis and recommendation system using machine learning. The Random Forest Classifier showcased a high accuracy, underscoring its capability to analyze complex moods. The system holds potential for enhancing user experience through mood-centric music recommendations.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## References

1. Agarwal et al. (2021)
2. Assuncao et al. (2018)
3. Pyrovolakis et al. (2022)
4. Siriket et al. (2021)

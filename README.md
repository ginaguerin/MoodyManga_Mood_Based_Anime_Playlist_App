# MoodyManga #

![Alt text](https://raw.githubusercontent.com/ginaguerin/MoodyManga_Mood_Based_Anime_Playlist_App/b94b9036672915feec5eec5d26c1c3e385634070//images/custom_anime_header2.png)


MoodyManga is an innovative app that harnesses the power of Natural Language Processing (NLP) and machine learning techniques to analyze and classify emotions in manga synopses. The app combines advanced algorithms with a hybrid model incorporating content-based and collaborative filtering, enhanced by tuning with genre, popularity, age, and gender features.


## Data Overview ##

Combined datasets from “MyAnimeList"
- 800,000 +
- Animes
- Profiles
- Reviews
- View our Data_Notebook.ipynb for breakdown

#### Limitations ####

- Anime is often catergorized as "animation"

#### Outside Data ####

- Sources from notifyvisitors.com

## Features ##

- Emotion Classification: Utilizes NLP techniques and a pre-trained model to classify emotions in the 'synopsis' column data.

- Tuning with Genre and Popularity: Refines the classification model by considering the "genre" and "popularity" columns.

- Random Forest Classifier: Employs a tuned random forest classifier for enhanced accuracy.

- Hybrid Model: Integrates content-based and collaborative filtering features in a neural network, providing a comprehensive recommendation system.

- Personalization with Age and Gender: Adjusts the tuned model based on user demographics, enhancing the user experience.


## Model Creation ##

In shaping MoodyManga's intelligence, we meticulously designed a sophisticated model creation process. Beginning with advanced Natural Language Processing (NLP) techniques, we utilized a pre-trained model to extract and classify emotion keywords from manga synopses. The model then underwent meticulous tuning, refining emotional classification through an intricate interplay with genre and popularity data for contextual and user-driven analysis. Integration of a tuned random forest classifier heightened emotion analysis precision. The pinnacle achievement was the development of a hybrid model, uniting content-based and collaborative filtering within a neural network. This innovation not only boosts recommendation accuracy but also tailors suggestions based on individual reader demographics like age and gender. MoodyManga stands as a harmonized fusion of cutting-edge technology and user-centric personalization.

- to view our flowchart please refer to our Presentation_Slides!

## App Deployment ##

Checkout our finalized app:
- [MoodyManga](https://moody-manga-app-ginakari.streamlit.app)!

See Moody_Manga_App --> 'moody_manga_app.py' for completed app details


## Future Developments ##

- More Emotions: Train model on a larger selection of moods

- Mood Mapping: Expand genre-to-mood labeling

- User Feedback: Real-time user feedback to improve predictions and app functions

- Image Classification: Use img_url to process image data with Convolution Neural Networks to use for more advanced mood predictions

## Contact Us! ##

#####  Kari Primiano #####
- Email: Kkprim@gmail.com
- Linkedin: linkedin.com/in/kari-primiano
- GitHub: github.com/kkprim

##### Gina Guerin #####
- Email: Gina.b.guerin@gmail.com
- Linkedin: linkedin.com/in/ginaguerin
- GitHub: github.com/ginaguerin


#### Kari and Gina Collaboration Logo! ####

![Logo](https://raw.githubusercontent.com/ginaguerin/MoodyManga_Mood_Based_Anime_Playlist_App/b94b9036672915feec5eec5d26c1c3e385634070//images/K_G_Logo.png)


``` bash


├── Zipped_data                      <- Data file used in this project
├── Images                           <- Images and Logo
├── saved_models                     <- Our saved models for easier access
├── .gitattributes                   <- Attributes for pathnames
├── .gitignore                       <- Contains list of files to be ignored from GitHub
├── Presentation_Slides.pdf          <- Slide Presentation of the project
├── README.md                        <- Contains README file to be reviewed
├── Data_Notebook.ipynb              <- Creation of combined Datasets
└── Recc_System_Notebook.ipynb       <- Jupyter notebook of the project containing codes and analysis

```


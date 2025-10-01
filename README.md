## Beats and Bytes: A Statistical Symphony of Spotify’s best tracks 

This project delves into the top-ranking songs on Spotify, exploring the intricate dynamics behind 
global and regional music trends. Using data on track features like danceability, energy, tempo, and 
popularity, we uncover what makes a song a chart-topper. By examining patterns in explicit 
content, album releases, and listener preferences across countries, this exploratory analysis offers 
valuable insights into the evolving world of music streaming.  

## Research Area

<img width="1690" height="780" alt="image" src="https://github.com/user-attachments/assets/8805f9f9-1502-438d-94f1-eebfe07a9e8d" />

## BEST MODELS AFTER EXPERMINENTATION

#### RANDOM FOREST 

<img width="986" height="476" alt="image" src="https://github.com/user-attachments/assets/524bc1c9-08a6-4d75-ac63-3d1389a24849" />

<img width="1019" height="424" alt="image" src="https://github.com/user-attachments/assets/57b80bc4-470c-44b6-8cb9-9144a36d6476" />

<img width="986" height="481" alt="image" src="https://github.com/user-attachments/assets/300bc69a-025d-4e4a-9ae3-cbe04f7b93a6" />

<img width="927" height="434" alt="image" src="https://github.com/user-attachments/assets/b7782b63-34f8-4476-aace-9be939ec94f8" />


#### KNN 

<img width="973" height="425" alt="image" src="https://github.com/user-attachments/assets/3a6fd043-8fe4-4b99-a4c6-7eb95b3160d1" />

<img width="967" height="469" alt="image" src="https://github.com/user-attachments/assets/7ced772a-2bdc-48ab-bf68-ea6f1b021d5d" />

#### K-MEANS CLUSTERING

<img width="600" height="420" alt="image" src="https://github.com/user-attachments/assets/358b0ac5-d190-43c7-be56-2bce48c1ad43" />

<img width="872" height="478" alt="image" src="https://github.com/user-attachments/assets/c59c71ce-21e5-4d70-a782-54d480e00051" />

<img width="663" height="380" alt="image" src="https://github.com/user-attachments/assets/ca7298ae-9f8b-48b0-b19d-a77452fbd15f" />

<img width="830" height="412" alt="image" src="https://github.com/user-attachments/assets/94ee4da8-a39c-4326-859b-57c3b8513fb9" />

#### TIME-SERIES DECOMPOSITION

<img width="741" height="530" alt="image" src="https://github.com/user-attachments/assets/d075d5c8-f995-4ab6-bdb5-91b0ec1a3ac5" />

<img width="488" height="297" alt="image" src="https://github.com/user-attachments/assets/308fa5eb-ded4-4cd0-8a94-aa5c07a79238" />

<img width="490" height="283" alt="image" src="https://github.com/user-attachments/assets/469d7f0e-8f44-4629-9054-dcf02302f9c3" />

<img width="485" height="305" alt="image" src="https://github.com/user-attachments/assets/45370a7d-9572-427a-8295-3bc56dc1634b" />


#### FINDINGS

1. The analysis revealed that a song's popularity is influenced by a combination of song attributes rather than any single feature. Loudness, Danceability and energy drives popularity of songs. 
2. Model Comparison: Random Forest Classification is a good choice while linear and logistic regression, perform poor on the data due to high skewness and non-linear associations between musical features and popularity of songs.
3. People prefer music that is energetic and danceable, while niche or raw qualities (e.g.live recordings, high speech content) have less universal appeal.
4. Musical features alone are strong predictors, but adding non-musical factors (e.g., explicit content, duration, age) and performance metrics (e.g., weekly and daily movement) improves prediction.
5. Model Comparison: k-NN outperforms logistic regression, likely due to non-linear associations between musical features and rank groups revealed in the EDA.
6. Cultural Influence: Regional and cultural contexts strongly influence musical preferences, shaping the popularity of certain attributes and artists. For example, clusters with more acoustic music might represent regions where traditional genres dominate.
7.  Global vs. Local Preferences: Clusters with globally popular music trends (e.g., Clusters 1 and 3) show more consistent popularity and high artist overlap. Other clusters (e.g., Cluster 4) highlight unique regional tastes, which can differ from global trends.
8. Daily fluctuations driven by external events.
9. Lifespans of most songs in the Top 50 are short.
10. Popularity declines over time but varies based on song type and target audience.
11. The analysis of temporal patterns highlights that song popularity is dynamic and influenced by both internal factors (e.g., song quality and marketing) and external factors (e.g., seasonal events and competition). 










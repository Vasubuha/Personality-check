Personality-check model
📌 Dataset Overview¶
This dataset simulates three human personality types:

Introvert
Extrovert
Ambivert
It contains 20,000 records and 30 features:

29 numerical personality traits (e.g., talkativeness, empathy, creativity, etc.)
1 categorical target column: personality_type
This dataset is ideal for:

Personality classification
Behavioral pattern analysis
Feature importance studies
Educational ML experimentation
📊 Exploratory Data Analysis (EDA)
✅ Univariate Analysis
Most features are scaled between 0–10.
Traits like talkativeness, empathy, and group_comfort vary clearly across personality types.
✅ Bivariate & Multivariate Analysis
Introverts score higher in deep_reflection, routine_preference, and emotional_stability.
Extroverts are high in social_energy, party_liking, and public_speaking_comfort.
Ambiverts show balanced traits.
Heatmap showed strong correlations (e.g., organization & planning, talkativeness & social_energy).
Pairplot, scatterplots, and violin plots helped visualize class separation.
✅ Conclusion
This project demonstrated:

How psychological traits can be analyzed using data science
How to build effective multiclass classification models
That high prediction accuracy (90%+) is achievable on synthetic behavioral data

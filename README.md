# Master´s Proyect 1 ICESI

Citizen Perception of Corruption in Colombia

This project looks at how people in Colombia react to corruption using sentiment analysis. Traditional indicators, like CPI or World Bank data, are based on expert opinions, but they do not fully show what citizens actually feel. This study tries to fill that gap by analyzing real comments from social media.

🔍 Objective

The goal is to understand how citizens express their opinions and emotions about corruption, and to identify which sentiment analysis model works best in this type of context.

🧠 Approach

First, different sentiment analysis methods were reviewed, including lexicon-based models, machine learning, deep learning, and Transformers. Based on this, several criteria were defined to choose the best model:

1. Ability to understand Spanish (especially informal language).
2. Performance in noisy data (slang, emojis, errors).
3. Capacity to capture context (sarcasm, irony).
4. Stability in political and emotional discussions.
   
After this process, the model BETO (a Spanish version of BERT) was selected.

⚙️ Data

The analysis is based on around 2,900 comments from YouTube related to the MinTIC–Centros Poblados corruption case. YouTube was used because access to Twitter data was limited. The comments were cleaned, but informal language was kept to reflect how people actually speak online.

📈 Results
1. Most of the comments show a negative sentiment, mainly linked to anger and distrust in institutions.
2. Neutral comments include short or unclear messages, sometimes with sarcasm.
3. Positive comments are rare and are usually directed at journalists or people exposing the case, not at the situation itself.
   
The model was able to detect not only clear opinions, but also more complex expressions, including sarcasm and local slang.

🧩 Main Insights
1. Simple methods are not enough for this type of data.
2. Context matters a lot when analyzing political discussions.
3. Transformer models perform better because they understand language in a deeper way.
   
⚠️ Limitations
1. These models require more computational resources.
2. Some comments are still difficult to classify, especially very short or ambiguous ones.
3. Results may include bias from the training data.
4. 
💡 Contribution

This project shows that social media can be a useful source to understand how people feel about corruption. It also shows that sentiment analysis can complement traditional indicators by adding a citizen perspective.

✅ Conclusion

This project shows that analyzing social media can help us better understand how people feel about corruption. The results confirm that there is a strong negative perception, driven by distrust and frustration toward institutions.
It also shows that choosing the right model is important. Simpler methods are not enough for this type of data, while models like BETO are better at understanding context, informal language, and complex expressions.
Even with some limitations, this approach adds value by including the citizen perspective, which is often missing in traditional indicators.

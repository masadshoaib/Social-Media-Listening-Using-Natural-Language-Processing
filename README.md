# Social Media Listening Using Natural Language Processing

In this project, we analyze social media data collected from different forums, blogs, and websites including twitter, instagram and facebook with a total of 37844 posts and 63 columns. The data has been collected on user experiences of Continuous Glucose Monitoring devices such as FreeStyle Libre and Dexcom.

Using natural language processing (NLP) techniques, we aim to analyze these texts and extract insights that can inform recommendations for CGM companies. Our objective is to understand better the sentiments, expectations, needs, customer segments, perceived benefits, and complaints associated with using these products. Based on our analysis, we will provide suggestions for feature enhancements and prioritize improvements to address customer concerns and improve the overall user experience.

We have followed a four-step approach to extract insights:
1. Pre-processing: We pre-processed the data and filtered it to the relevant terms for answering the question based on word cloud, bi-grams, and tri-grams. For example, to understand general CGM expectations, we filtered the data to 'expect,' 'wish,' 'hope,' 'need,' 'want,' and 'cgm,' 'continuous glucose monitoring,' and 'continuous glucose monitor.' After that, we removed the frequently occurring terms such as Dexcom, cgm, etc.
2. Modeling: Next, we ran the data through the Latent Dirichlet model to cluster and segment it into topics.
3. Dominant Topic Identification: LDA assigned all the documents (phrases) several topics with varying probabilities. Therefore, we decided to identify the dominant topic based on the highest probability and assign it to each.
4. Lastly, we generated word clouds to understand what each topic represented. Ultimately, we manually reviewed the documents under each to develop specific examples to answer the questions.

## Authors
Asad Shoaib

Diksha Chand

Abishaik Mohan


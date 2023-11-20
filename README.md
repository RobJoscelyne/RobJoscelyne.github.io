# Data science portfolio

## Projects

### Performance analysis of text retrieval models  

Information retrieval is crucial as it can provide rapid access to vast amounts of data, facilitating the discovery of new knowledge. This study investigates the performance of three information retrieval models: 1. Vector Space Model, 2. Best Matching 25 (BM25), and 3. ELECTRA on the Cranfield collection, a renowned benchmark dataset. The objectives were: 1) Implement an indexing component, 2) Develop a ranking system using the three models, 3) Compare models employing the TREC evaluation format, and 4) Integrate the top-performing model into a user interface. Preprocessing involved tokenisation, text normalisation, stopword removal, and index building. The BM25 algorithm emerged as the most effective. The work correlated with previous research and found that hyperparameter tuning of BM25 yielded improved results. The BM25 retrieval model was successfully integrated into a [Streamlit user interface](https://alpaca-search-cranfield-collection.streamlit.app/) to demonstrate the undertaken work.

[Report](https://github.com/RobJoscelyne/robjoscelyne.github.io/blob/a00001bc3f9d72f8b6aa94ab3eec2f39647522e7/assets/Information%20retrieval.pdf)

<img src="/assets/embedding_projector.jpg" width="1000">


### Using data visualisations for airline route planning 

A start-up airline wishes to operate a new short-haul route serving the San Francisco Bay Area. The management team have shortlisted three potential departure airports. Passengers rate airlines' punctuality. Delays and cancellations can cause travellers to avoid the airline or seek cheaper future tickets. For these reasons, the management team must know which airport shall provide the best on-time performance. A visualisation was developed using attention and distraction principles to help effectively communicate the airport with the lowest cancellations and delays. The dataset was sourced from the United States Bureau of Transportation Statistics and contained four years of data on flight schedules. This dataset qualifies as big data due to its significant volume. To enhance efficiency during the preprocessing stages, the data was converted into the Parquet format a choice well-suited for handling big data. Dataset queries were developed in Python to match the business objectives: short-haul flights departing in the morning from 1. San Francisco International (SFO), 2. Mineta San Jose International Airport (SJC), and 3. Metropolitan Oakland International (OAK). An interactive visualisation using D3.js was developed and showed that the airport with the best on-time performance was Metropolitan Oakland International. The charts were deployed on GitHub pages and can be accessed here [Visualisation](https://robjoscelyne.github.io/data_visualisations/)

<img src="/assets/embedding_projector.jpg" width="1000">


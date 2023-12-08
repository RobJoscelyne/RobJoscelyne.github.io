# Data science portfolio

## Projects

### Performance analysis of text retrieval models  

Information retrieval is crucial as it can provide rapid access to vast amounts of data, facilitating the discovery of new knowledge. This study investigates the performance of three information retrieval models: 1. Vector Space Model, 2. Best Matching 25 (BM25), and 3. ELECTRA on the Cranfield collection, a renowned benchmark dataset. The objectives were: 1) Implement an indexing component, 2) Develop a ranking system using the three models, 3) Compare models employing the TREC evaluation format, and 4) Integrate the top-performing model into a user interface. Preprocessing involved tokenisation, text normalisation, stopword removal, and index building. The BM25 algorithm emerged as the most effective. The work correlated with previous research and found that hyperparameter tuning of BM25 yielded improved results. The BM25 retrieval model was successfully integrated into a [Streamlit user interface](https://alpaca-search-cranfield-collection.streamlit.app/) to demonstrate the undertaken work.

[Report](https://github.com/RobJoscelyne/robjoscelyne.github.io/blob/a00001bc3f9d72f8b6aa94ab3eec2f39647522e7/assets/Information%20retrieval.pdf)

<img src="/assets/embedding_projector.jpg" width="1000">


### Using data visualisations for airline route planning 


A start-up airline is considering a new short-haul route in the San Francisco Bay Area, focusing on punctuality as a key factor for passenger satisfaction. They examined on-time performance data from three potential departure airports: San Francisco International (SFO), Mineta San Jose International Airport (SJC), and Metropolitan Oakland International (OAK). The data, sourced from the United States Bureau of Transportation Statistics, covers four years of flight schedules, qualifying as big data due to its volume. For efficient preprocessing, the data was converted to the Parquet format, suitable for big data handling. Python queries were used to analyze morning short-haul flights from these airports. An interactive visualisation, created with D3.js, was used to determine that Metropolitan Oakland International offers the best on-time performance. This visualisation is accessible on GitHub pages, highlighting the importance of effective data management and visual communication in business decision-making. [Visualisation](https://robjoscelyne.github.io/data_visualisations/)

[Report](https://github.com/RobJoscelyne/robjoscelyne.github.io/blob/6c024b99a2f7641a7ddfbd885193bc947aea00f6/assets/data_visualisations_for_route_planning.pdf)

<img src="/assets/llama_base.jpg" width="1000">

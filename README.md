    # infoRetrieval

    ## Project Overview
        This project focuses on information retrieval and ranking for social media data, specifically related to tweets from the farmers' protests. It includes preprocessing steps, query formulation, and retrieval evaluation using metrics like Precision, Recall, F1, MAP, and MRR. The notebook provides tools to process text data, generate TF-IDF scores, and evaluate query results for relevance.


    ## Installation and Environment Setup

    This project is intended to be run in Google Colab due to compatibility requirements with certain libraries (e.g., `stopwords_hindi`). Ensure that Colab is set up before proceeding with the steps below.

    ## Dependencies and Libraries
    Make sure the following libraries are installed:
    - `indic-nlp-library`
    - `punjabi_stopwords`
    - `LiHiSTO`
    - `emoji`
    - `wordcloud`

    You can install these directly in Colab with the following command:
    ```bash
    !pip install indic-nlp-library punjabi_stopwords LiHiSTO emoji wordcloud

    ## Data Requirements

    Documents needed to include in the root directory in colab:
        The following documents must be uploaded to the root directory in Google Colab:
        - `farmers-protest-tweets.json`: The main dataset containing tweet data.
        - `gargi.ttf`: Font file used for text rendering in visualizations.
        - `tweet_document_ids_map.csv`: Mapping of tweet IDs to document IDs for retrieval.
        - `evaluation_gt.csv`: Ground truth data for evaluating query retrieval.
        - `our_evaluation.csv`: Additional evaluation dataset.

    ## Running the Notebook
        1. Clone the repository and upload the code to Google Colab.
        2. Install the necessary libraries as mentioned above, the pip instructions are already present in the code.
        3. Add the necessary documents.
        4. Run the main notebook deliverable.ipynb.
        5. Follow the instructions inside the notebook.



Find additional information in the report.
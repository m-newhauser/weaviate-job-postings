# weaviate-job-postings

### Clustering AI-related job postings with Sentence Transformers, Weaviate, and BERTopic

#### Overview
This Jupyter Notebook provides a comprehensive approach to analyzing LinkedIn job postings related to AI and Machine Learning using topic modeling.

#### Objectives
- **Data Preparation:** Load and preprocess job postings data.
- **Topic Modeling:** Apply BERTopic for extracting meaningful topics.
- **Visualization:** Use Plotly for interactive visualizations.
- **Evaluation:** Assess the model's performance and identify limitations.

#### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Libraries: `pandas`, `numpy`, `plotly`, `bertopic`, `colorcet`, `requests`, `transformers`

#### Files
```
weaviate-job-postings/
├── README.md
├── weaviate_job_postings.ipynb
└── output.zip
```

- weaviate_job_postings.ipynb: Entire workflow with documentation.
- output.zip: All output files generated by the notebook.
- - topic_info.csv: Labeled topics with representative keywords.
  - document_topics.csv: Topic assignment for each row in the dataset.
  - topic_map.html: Plotly HTML visualization of topics.
  - topic_model: BERTopic model.

#### Author
Mary Newhauser

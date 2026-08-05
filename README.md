# Semantic Book Recommender

This is a semantic book recommender built following the tutorial available at [https://www.youtube.com/watch?v=Q7mS1VHm3Yw](https://www.youtube.com/watch?v=Q7mS1VHm3Yw). Instead of the OpenAI model used in the tutorial, the [https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2](sentence-transformers/all-MiniLM-L6-v2) model was used in order to create the embeddings for the vector search.

## How to run the application

1. Download the repository to your machine in .zip format or through cloning

```
git clone git@github.com:juliaduboisas/semanticBookRecommender.git
```

2. Open the gradio-dashboard.py file and run it, either through your IDE or through

```
python gradio-dashboard.py
```

3. Open the local URL signaled, usually [http://127.0.0.1:7860](http://127.0.0.1:7860)

# Automatic Text Summarization through global semantics

DL Final Project

We examine a way to improve the performance of current state-of-the-art abstractive summarization models. We implement and evaluate the effectiveness of document-related modulation (DRM), a key component of the topic assistant module architecture introduced in ”Friendly topic assistant for transformer based abstractive summarization” (Wang et al., 2020). This architecture improves upon the global semantics of current state-of-the-art abstractive summarization models by first identifying topics in each document using a topic model. The topic proportion vector generated from a topic model is then fed into the DRM layer present in the base, state-of-theart model’s decoder. This is done to improve the global semantics of the generated summary through feature biasing. Due to the importance of the topic model to this approach, we experiment with two alternative topic models, the Latent Dirichlet Allocation (Blei et al., 2003) and the Weibull Hybrid Autoencoding Inference (Zhang et al., 2020) to see how each affects the performance of the summarization task.

Analysis: [Click Here](https://github.com/anhducvu-bot/Automatic-Text-Summarization/blob/main/DL_Final_Project__Copy_.pdf)

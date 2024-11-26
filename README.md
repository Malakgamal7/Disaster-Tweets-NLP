# Disaster-Tweets-NLP
Model predicts which Tweets are about real disasters and which one’s aren’t

BERT : Bidirectional Encoder Representations from Transformers
BERT uses the Transformer encoder architecture to process each token of input text in the full context of all tokens before and after, hence the name: Bidirectional Encoder Representations from Transformers. BERT models are usually pre-trained on a large corpus of text, then fine-tuned for specific tasks.

Uses DistilBERT: Bidirectional Encoder Representations from Transformers. Size of a BERT model was reduced by 40% via knowledge distillation during the pre-training phase while retaining 97% of its language understanding abilities and being 60% faster
DistilBERT model learns a distilled (approximate) version of BERT, retaining 97% performance but using only half the number of parameters
Specifically, it doesn't have token-type embeddings, pooler and retains only half of the layers from Google's BERT

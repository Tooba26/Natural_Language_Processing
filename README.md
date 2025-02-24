# Natural_Language_Processing
### Preprocessing
| Tokenizer  | Approach                          | Pros                                          | Cons                           | Used In |
|------------|----------------------------------|----------------------------------------------|-------------------------------|---------|
| **Normal** | Space & punctuation-based       | Simple, Fast                               | OOV problem, rigid            | Basic NLP models |
| **BPE**    | Merges frequent character pairs | Handles OOV well, reduces vocab size       | No probability modeling       | GPT-2, GPT-3 |
| **WordPiece** | Merges based on likelihood   | Efficient, balances segmentation           | More complex than BPE         | BERT, DistilBERT |
| **Unigram** | Probabilistic subword selection | More flexible, probabilistic choices      | Computationally expensive     | SentencePiece, T5, XLNet |

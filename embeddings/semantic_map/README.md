# Semantic Map Embeddings

Here you find pre-trained semantic map embeddings that you can use with the `SemanticMapFeaturizer` in the [rasa-nlu-examples repo](https://github.com/RasaHQ/rasa-nlu-examples).

| Name (rasa-sme-*)              | Languages | Size    | Corpus                       | Snippets              | Vocabulary          | Topology        | Density  |
|--------------------------------|-----------|---------|------------------------------|-----------------------|---------------------|-----------------|----------|
| wikipedia-en-64x64-v20201120   | en        | 64x64   | Wikipedia dump of 2019-12-20 | 57,962,486 paragraphs | 79,649 (lower case) | torus/hexagonal | up to 2% |
| wikipedia-en-128x128-v20201120 | en        | 128x128 | Wikipedia dump of 2019-12-20 | 57,962,486 paragraphs | 79,649 (lower case) | torus/hexagonal | up to 2% |

All embeddings are json files that are packed as zip-archives. You have to unpack them before use.

---
type: "MPhil"
student: "Muhammad Ahsan Aziz"
title: "Enhanced Document Classification using Graph Transformers"
date: 2024-09-01
permalink: /supervision/2024-muhammad-ahsan-aziz-enhanced-document-classification-using-graph-transformers
collection: supervision
---
Enhanced Document Classification using Graph Transformers by Muhammad Ahsan Aziz (2024)

In an era where data is generated rapidly, organizations need extraordinary systems to gather and organize huge amounts of data. Document classification provides help in this regard by classifying the documents into their specific classes. This task is supportive for applications like digital libraries, where it is necessary to organize massive information efficiently. Traditional methods including bag-of-words models and basic neural networks, often fail to capture the complex and significant relationships between words and documents. To overcome existing traditional methods, Graph-based approaches such as Graph Convolutional Networks (GCN) and Graph Attention Networks (GAT) offer some improvement by representing documents as graphs. These Graph-based approaches have limited capacity to capture global contextual relationships. GCN lacks attention mechanisms, that is why it cannot focus on the most relevant parts of the text. GAT utilizes local attention, missing the broader context needed for accurate classification. Transformers-based attention mechanism are effective for document classification because they can capture complex word relationships and understand the context of words within a document. This research addresses these limitations by proposing an enhanced document classification model that efficiently combines graph-based techniques with transformer architectures. We construct a heterogeneous graph where nodes represent both words and documents. The heterogeneity of the graph combined with Transformer-based embedding allows the model to capture the contextual relationships between words and documents more effectively, ensuring a deeper and more accurate understanding of the documented content. Integration of the transformer model for the initial document representation is a significant component of our approach. The Transformer model (BERT) with its deep understanding of context improves how documents are represented. When the BERT Transformer model is combined with the global attention of a Graph Transformer, it results in more accurate and effective classification by capturing global and local text relationships. This approach not only outperforms existing methods like GCN, GAT, and traditional Graph Neural Networks (GNNs) but also shows significant improvements in classification accuracy and reliability. The main focus of this research is to find the necessity of developing a more efficient and advanced document classification model. That can measure how the integration of the Transformer model with the Graph Transformer can lead to significant advancements in document classification.
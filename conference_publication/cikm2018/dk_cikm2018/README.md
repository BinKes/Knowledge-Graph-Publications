#GYANI: An Indexing Infrastructure for Knowledge-Centric Tasks
- **author**:Dhruv Gupta, Klaus Berberich  
- **abstract**:In this work, we describe GYANI (gyan stands for knowledge in Hindi), an indexing infrastructure for search and analysis of large semantically annotated document collections. To facilitate the search for sentences or text regions for many knowledge-centric tasks such as information extraction, question answering, and relationship extraction, it is required that one can query large annotated document collections interactively. However, currently such an indexing infrastructure that scales to millions of documents and provides fast query execution times does not exist. To alleviate this problem, we describe how we can effectively index layers of annotations (e.g., part-of-speech, named entities, temporal expressions, and numerical values) that can be attached to sequences of words. Furthermore, we describe a query language that provides the ability to express regular expressions between word sequences and semantic annotations to ease search for sentences and text regions for enabling knowledge acquisition at scale. We build our infrastructure on a state-of-the-art distributed extensible record store. We extensively evaluate GYANI over two large news archives and the entire Wikipedia amounting to more than fifteen million documents. We observe that using GYANI we can achieve significant speed ups of more than 95x in information extraction, 53x on extracting answer candidates for questions, and 12x on relationship extraction task.
- **keywords**: Knowledge-Centric，gyani，information extraction，relationship extraction
- **interpretation**:
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271745)
- **code**: 
- **dataset**: 
- **ppt/video**:
- **curator**: Wu Bo
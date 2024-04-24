# ANNS

### Graph Index

- [Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs](https://arxiv.org/abs/1603.09320), [hnswlib](https://github.com/nmslib/hnswlib.git)
- [Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph](https://arxiv.org/abs/1707.00143), [NSG](https://github.com/ZJULearning/nsg.git)
- [Graph Reordering for Cache-Efficient Near Neighbor Search (NIPS 2022)](https://papers.nips.cc/paper_files/paper/2022/hash/fb44a668c2d4bc984e9d6ca261262cbb-Abstract-Conference.html)
- [ParANN: Scalable and Deterministic Parallel Graph-Based Approximate Nearest Neighbor Search Algorithms](https://dl.acm.org/doi/pdf/10.1145/3627535.3638475), [code](https://github.com/cmuparlay/ParlayANN.git)

### Billion-scale similarity search

- Billion-scale similarity search with GPUs, [Faiss](https://github.com/facebookresearch/faiss.git)
- DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node (NeurIPS 2019), [DiskANN](https://github.com/microsoft/DiskANN.git)
- [FreshDiskANN: A Fast and Accurate Graph-Based ANN Index for Streaming Similarity Search](https://arxiv.org/pdf/2105.09613.pdf)
- [Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment](https://dl.acm.org/doi/pdf/10.1145/3639269), [code](https://github.com/zilliztech/starling.git)

### Graph Index on GPU

- SONG: Approximate Nearest Neighbor Search on GPU (ICDE 2020), [code](https://github.com/sunbelbd/song.git)
- GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction (ICDE 2022), [code](https://github.com/yuyuanhang/GANNS.git)
- CAGRA: Highly Parallel Graph Construction and Approximate Nearest Neighbor Search for GPUs (ICDE 2024), [code](https://github.com/rapidsai/raft.git)
- GGNN: Graph-based GPU Nearest Neighbor Search, [code](https://github.com/cgtuebingen/ggnn.git)

### Filtered Search

- [Constrained Approximate Similarity Search on Proximity Graph](https://arxiv.org/abs/2210.14958)
- [Navigable Proximity Graph-Driven Native Hybrid Queries with Structured and Unstructured Constraints](https://arxiv.org/abs/2203.13601)
- [CAPS: A Practical Partition Index for Filtered Similarity Search](https://arxiv.org/abs/2308.15014)
- [Filtered−DiskANN: Graph Algorithms for Approximate Nearest Neighbor Search with Filters (WWW 2023)](https://harsha-simhadri.org/pubs/Filtered-DiskANN23.pdf)
- [An Efficient and Robust Framework for Approximate Nearest Neighbor Search with Attribute Constraint (NIPS 2023)](https://papers.nips.cc/paper_files/paper/2023/hash/32e41d6b0a51a63a9a90697da19d235d-Abstract-Conference.html)
- [SeRF: Segment Graph for Range-Filtering Approximate Nearest Neighbor Search (SIGMOD 2024)](https://dl.acm.org/doi/pdf/10.1145/3639324), [code](https://github.com/rutgers-db/SeRF.git)
- [Approximate Nearest Neighbor Search with Window Filters](https://arxiv.org/abs/2402.00943)

## Others

### Billion-Scale Approximate Nearest Neighbor Search Challenge

- [NeurIPS'21 competition track](https://big-ann-benchmarks.com/neurips21.html)
- [NeurIPS'23 Competition Track: Big-ANN](https://big-ann-benchmarks.com/neurips23.html)

### ANN Benchmarks

- [ANN-Benchmarks](https://ann-benchmarks.com/)

## Dataset

### Billion-scale

|                           Dataset                            | Dimensions | Base Size | Query Size |  k   |
| :----------------------------------------------------------: | :--------: | :-------: | :--------: | :--: |
|           [SIFT1B](http://corpus-texmex.irisa.fr/)           |    128     |    1B     |    10K     | 100  |
| [DEEP1B](https://research.yandex.com/blog/benchmarks-for-billion-scale-similarity-search) |     96     |    1B     |    10K     | 100  |
| [Text-to-Image-1B](https://research.yandex.com/blog/benchmarks-for-billion-scale-similarity-search) |    200     |    1B     |    100K    |      |
| [Facebook SimSearchNet++](https://big-ann-benchmarks.com/neurips21.html) |    256     |    1B     |    100K    |      |
| [Microsoft SPACEV-1B](https://github.com/microsoft/SPTAG/tree/main/datasets/SPACEV1B) |    100     |    1B     |    29K     | 100  |

### Million-scale

|  Dataset  | Dimensions | Base Size | Query Size |  k   |
| :-------: | :--------: | :-------: | :--------: | :--: |
|   MNIST   |    784     |  60,000   |   10,000   | 100  |
| GloVe-100 |    100     | 1,183,514 |   10,000   | 100  |
| GloVe-200 |    200     | 1,183,514 |   10,000   | 100  |
|  GIST1M   |    960     | 1,000,000 |   1,000    | 100  |
|  SIFT1M   |    128     | 1,000,000 |   10,000   | 100  |
|  NYTimes  |    256     |  290,000  |   10,000   | 100  |


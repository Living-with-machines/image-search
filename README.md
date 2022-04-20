#  Image search with 🤗 datasets 

Materials for a workshop on image search with a focus on heritage data. The workshop is based on a blog post [Image search with 🤗 datasets](https://huggingface.co/blog/image-search-datasets) but goes into a *little* bit more detail. 

## Contents
- The [Slides](image_search.pdf) are used to introduce [🤗 `datasets`](https://huggingface.co/docs/datasets/index), [`sentence-transformers`](https://www.sbert.net/index.html), and [CLIP](https://openai.com/blog/clip/) as well as giving a broader conceptual overview of image search, embeddings and concluding with some discussion of ethical considerations about deployment. 
- [Notebook 1](01_sentence-transformers-intro.ipynb) gives a rapid overview of how `sentence-transformers` can be used to 'encode' text and images for tasks like image search. 
- [Notebook 2](02_image_search_demo.ipynb) allows for the exploration of the outputs of a CLIP model. This is intended to allow people to *begin* interrogating the strengths, weaknesses and issues with using CLIP with heritage material. 
- [Notebook 3](03_hf_blog_image_search.ipynb) is the original notebook which accompanied the blog post. This notebook gives an overview of the steps involved from start to finish. 



This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


### Acknowledgment

> This work was support by Living with Machines. This project, funded by the UK Research and Innovation (UKRI) Strategic Priority Fund, is a multidisciplinary collaboration delivered by the Arts and Humanities Research Council (AHRC), with The Alan Turing Institute, the British Library and the Universities of Cambridge, East Anglia, Exeter, and Queen Mary University of London.

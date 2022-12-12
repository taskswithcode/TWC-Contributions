# TWC Contributions to Open Research

 - APIs 📡 -  _a single end-point API for a task that is powered behind the scenes by the current SOTA solution for that task_
    - **Free evaluation APIs** are exposed for SOTA models with permissive licenses
    - [Contact](mailto:twc@taskswithcode.com) if you need a privately hosted API end-point for your use case. 
 - Apps 📱 
 - Notebooks 🗒️ ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)
 - Explorations  👨‍💻

<p>
<div style=\"font-size:16px; color: #dfdfdf; text-align: center\"><i>All test images and videos used in the illusrations unless explicitly specified below are from <a href="https://www.pexels.com"><b>Pexels</b></a> - a royalty free site for images and videos where creators upload high quality images for sharing</i></div>
</p>
<img src="divider.png"   width="1000px"/>


### Tasks solved using SOTA models
1. [Image background removal -  📡  API available now 🔥 ](#image-background-removal)
2. [Video background removal - 🗒️](#video-background-removal)
3. [Classifying the dominant object in the foreground of an image 📱 ](#foreground-object-classification)
4. [Detecting one or more objects within an image 📱 ](#detecting-objects-within-images)

5. [Sentence embeddings for Semantic search, similarity, and clustering 📱](#sentence-embeddings)
6. [Exploratory tasks  👨‍💻 ](#exploratory-tasks)


<img src="divider.png"   width="1000px"/>

### Image Background Removal

<p align="center">
  <a href="assets/SOD.png">
    <img src="assets/SOD.png" alt="Image Background Removal" width="800">
  </a>
  <br/>
</p>

### Current endpoint
- 📡 **API** for Image background removal. Usage illustrated in [Hugging Face app 🤗](https://huggingface.co/spaces/taskswithcode/salient-object-detection) & [TWC hosted app 📱](https://www.taskswithcode.com/salient_object_detection/)
#### SOTA model
- [InSPyReNet fork](https://github.com/taskswithcode/InSPyReNet)
   - [📱 TWC hosted app](https://www.taskswithcode.com/salient_object_detection/) & [Hugging Face app 🤗](https://huggingface.co/spaces/taskswithcode/salient-object-detection)
   - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb)

<img src="divider.png"   width="1000px"/>

### Video Background Removal

<p align="center">
  <a href="assets/SODV.png">
    <img src="assets/SODV.png" alt="Video Background Removal" width="800">
  </a>
  <br/>
</p>

### Current endpoint

- [🗒️ Notebook](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb)

#### SOTA model
- [InSPyReNet fork](https://github.com/taskswithcode/InSPyReNet)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb)

<img src="divider.png"   width="1000px"/>

### Foreground object classification

<p align="center">
  <a href="assets/SingleObjectClassification.png">
    <img src="assets/SingleObjectClassification.png" alt="Single Object Classification" width="800">
  </a>
  <br/>
</p>

### Current endpoint

- [Compare two model outputs (SimMIM & VIT base) in Colab](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)
- Classifies input image into one of [1000 classes](https://github.com/taskswithcode/SimMIM/blob/main/imagenet_code_to_label_map.txt)

#### SOTA model
- [SimMIM fork](https://github.com/taskswithcode/SimMIM)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)

<img src="divider.png"   width="1000px"/>

### Detecting objects within images
<p align="center">
  <a href="assets/SingleObjectClassification.png">
    <img src="assets/SingleObjectClassification.png" alt="Single Object Classification" width="800">
  </a>
  <br/>
</p>

### Current endpoint
- Compare models through separate apps
 - [🤗 App implemented with OWL-ViT](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo)
 - [🤗 App implemented with OWL-ViT](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo)

#### SOTA models
- [GRiT fork](https://github.com/taskswithcode/GriT)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)

<img src="divider.png"   width="1000px"/>


### Captioning objects
- [🤗 App implemented with OWL-ViT](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo)

#### SOTA models
- [GriT fork - 🗒️ notebook added](https://github.com/taskswithcode/GriT)

<img src="divider.png"   width="1000px"/>

### Video quality assessment

- [DOVER fork - 🗒️ notebook added](https://github.com/taskswithcode/DOVER)


<img src="divider.png"   width="1000px"/>


### Sentence embeddings

#### Tasks
- [👨‍💻 App code for Sentence Similarity Comparison on TWC](https://github.com/taskswithcode/sentence_similarity_app)
- [👨‍💻 App code for Semantic Search Comparison on TWC](https://github.com/taskswithcode/semantic_search_app)
- [👨‍💻 App code for Semantic Clustering Comparison on TWC](https://github.com/taskswithcode/semantic_clustering_app)
- [🤗 Sentence Similarity Comparison app on Hugging Face](https://huggingface.co/spaces/taskswithcode/semantic_similarity)
- [🤗 Semantic Search Comparison app on Hugging Face](https://huggingface.co/spaces/taskswithcode/semantic_search)
- [🤗 Semantic Clustering Comparison app on Hugging Face](https://huggingface.co/spaces/taskswithcode/semantic_clustering)


#### SOTA models
- [simCSE fork - with added code 👨‍💻 for use in comparison app ](https://github.com/taskswithcode/SimCSE)
- [SGPT fork - with added code 👨‍💻 for use in comparison app ](https://github.com/taskswithcode/sgpt)
- [DCPCSE fork - with added code 👨‍💻 for use in comparison app ](https://github.com/taskswithcode/DCPCSE)
- [OpenAI embeddings wrapper 👨‍💻](https://github.com/taskswithcode/openai_api)
- [🤗 Hugging Face models wrapper 👨‍💻  for comparison app](https://github.com/taskswithcode/sentence_similarity_hf_model)


<img src="divider.png"   width="1000px"/>

### Learning self-supervised representations for images

- [MAE  fork - 🗒️ notebook added](https://github.com/taskswithcode/mae)


<img src="divider.png"   width="1000px"/>

### Exploratory tasks

- [Latent Diffusion fork - 🗒️ notebook added](https://github.com/taskswithcode/latent-diffusion)
- [Taming Transformers fork - 🗒️ notebook added](https://github.com/taskswithcode/taming-transformers)



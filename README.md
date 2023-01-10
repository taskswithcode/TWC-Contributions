# TWC Contributions to Open Research

- [![SOTA Researchers](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/SOTAResearchers.svg)](https://github.com/taskswithcode/sota_researchers_with_published_code) - _Highlighting the work of SOTA reseachers who publish code, models, app & notebooks (in some cases) with their paper_
- [![Discover and Compare SOTA models](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCCompare.svg)](https://taskswithcode.com/find_sota_repos/) - _Discover and compare SOTA solutions for tasks with a few keystrokes/clicks_


 - [![APIs](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCAPI.svg)](https://huggingface.co/spaces/taskswithcode/salient-object-detection) -   _**Free APIs** for tasks using SOTA models (with permissive licenses). Please use for evaluation only to avoid overwhelming servers_
 
 - ![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg) - _demo apps hosted on TWC servers or on HuggingFace_
 - ![Notebooks](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCNotebook.svg) - _notebooks in Google colab_
 - ![Explorations](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCExplorations.svg) - _Github repos with experiments that are work in progress_


 The development for each task below is at different stages of development -  ![exploring solutions](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCExplorations.svg) , model evaluation using ![notebooks](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCNotebook.svg), ![apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg) to compare SOTA models, and an  endpoint ![API](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCAPI.svg) for a task. The goal is to have an endpoint API for each task with one or more SOTA models to choose from for that task.
<br/>
<div><i>All test images and videos used in the illustrations below unless explicitly specified  are from <a href="https://www.pexels.com"><b>Pexels</b></a> - a royalty free site for images and videos where creators upload high quality images for sharing</i></div>


<img src="divider.png"   width="1000px"/>


### Tasks solved using SOTA models
1. [Image background removal -  📡  API available now 🔥 ](#image-background-removal)
2. [Video background removal - 🗒️](#video-background-removal)
3. [Classifying the dominant object in the foreground of an image 📱 ](#foreground-object-classification)
4. [Detecting multiple objects within an image 📱 ](#detecting-multiple-objects-within-images)
5. [Image Captioning](#image-captioning)
6. [Video quality assessment](#video-quality-assessment)
7. [Learning image embeddings](#self-supervised-image-representations)
8. [Sentence embeddings for Semantic search, similarity, and clustering 📱](#sentence-embeddings)
9. [Exploratory tasks  👨‍💻 ](#exploratory-tasks)


<img src="divider.png"   width="1000px"/>

### Image Background Removal

<p align="center">
  <a href="assets/SOD.png">
    <img src="assets/SOD.png" alt="Image Background Removal" width="800">
  </a>
  <br/>
</p>

### Current endpoint
- 📡 **API** for Image background removal. API usage illustrated in [Hugging Face app 🤗](https://huggingface.co/spaces/taskswithcode/salient-object-detection) & [TWC hosted app 📱](https://www.taskswithcode.com/salient_object_detection/)
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

- [🗒️ Compare two model outputs (SimMIM & VIT base) in Colab](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)
  - Classifies input image into one of [1000 classes](https://github.com/taskswithcode/SimMIM/blob/main/imagenet_code_to_label_map.txt)

#### SOTA model
- [SimMIM fork](https://github.com/taskswithcode/SimMIM)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)

<img src="divider.png"   width="1000px"/>

### Detecting multiple objects within images
<p align="center">
  <a href="assets/MultipleObjectDetection.png">
    <img src="assets/MultipleObjectDetection.png" alt="Multiple Objects Classification" width="800">
  </a>
  <br/>
</p>

### Current endpoint
- Compare models through separate apps
  - [📱  App implemented with Detic 🤗](https://huggingface.co/spaces/taskswithcode/DeticChatGPT)
  - [📱  App implemented with OWL-ViT 🤗](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo)

#### SOTA models
- [GRiT fork](https://github.com/taskswithcode/GriT)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)

<img src="divider.png"   width="1000px"/>


### Image Captioning
- [🤗 App implemented with OWL-ViT](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo)

#### SOTA models
- [GriT fork - 🗒️ notebook added](https://github.com/taskswithcode/GriT)

<img src="divider.png"   width="1000px"/>

### Video quality assessment

- [DOVER fork - 🗒️ notebook added](https://github.com/taskswithcode/DOVER)


<img src="divider.png"   width="1000px"/>

### Self-supervised image representations

- [MAE  fork - 🗒️ notebook added](https://github.com/taskswithcode/mae)



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



### Exploratory tasks

- [Latent Diffusion fork - 🗒️ notebook added](https://github.com/taskswithcode/latent-diffusion)
- [Taming Transformers fork - 🗒️ notebook added](https://github.com/taskswithcode/taming-transformers)



# Contributions to Open Research

- [![SOTA Researchers](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCShorts.svg)](https://github.com/taskswithcode/MLIntro) - _ML Concepts explained in under a minute with accompanying notebook and notebook code walkthrough_

- [![SOTA Researchers](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/SOTAResearchers.svg)](https://github.com/taskswithcode/sota_researchers_with_published_code) - _Highlighting the work of SOTA reseachers & practitioners who publish code, models, app & notebooks (in some cases) for a paper_
- [![Discover and Compare SOTA models](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCCompare.svg)](https://taskswithcode.com/find_sota_repos/) - _Discover and compare SOTA solutions for tasks with a few keystrokes/clicks_


 - [![APIs](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCAPI.svg)](https://www.taskswithcode.com/salient_object_detection/) -   _**Free APIs** for tasks using SOTA models (with permissive licenses). Please use for evaluation only to avoid overwhelming servers_
 
 - [![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://taskswithcode.com/sentence_similarity/) - _demo apps hosted on [TWC servers](https://taskswithcode.com/sentence_similarity) and/or on [Hugging Face](https://huggingface.co/taskswithcode)_
 - [![Notebooks](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCNotebook.svg)](https://github.com/taskswithcode/latent-diffusion/blob/main/TWCLatentDiffusion.ipynb) - _notebooks in Google colab_
 - [![Explorations](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCExplorations.svg)](https://github.com/taskswithcode/latent-diffusion/blob/main/TWCLatentDiffusion.ipynb) - _Github repos with experiments that are work in progress_
 - [![Newsletters](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCNewsletter.svg)](https://taskswithcode.ghost.io/) - _Aperiodic newsletters on [Ghost](https://taskswithcode.ghost.io/) and [Medium](https://medium.com/taskswithcode)_




<img src="divider.png"   width="1000px"/>


### Tasks solved using SOTA models
1. [Image background removal -  API available now ](#image-background-removal)
2. [Video background removal ](#video-background-removal)
3. [Classifying the dominant object in the foreground of an image](#foreground-object-classification)
4. [Detecting multiple objects within an image](#detecting-multiple-objects-within-images)
5. [Image Captioning](#image-captioning)
6. [Video quality assessment](#video-quality-assessment)
7. [Learning image embeddings](#self-supervised-image-representations)
8. [Sentence embeddings for Semantic search, similarity, and clustering](#sentence-embeddings)
9. [Exploratory tasks](#exploratory-tasks)


<img src="divider.png"   width="1000px"/>

### Image Background Removal

<p align="center">
  <a href="assets/SOD.png">
    <img src="assets/SOD.png" alt="Image Background Removal" width="800">
  </a>
  <br/>
</p>

### Current endpoint
- [![APIs](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCAPI.svg)](https://www.taskswithcode.com/salient_object_detection/) for Image background removal. API usage illustrated in  [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/salient-object-detection)  & [![TWC hosted app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://www.taskswithcode.com/salient_object_detection/)
#### SOTA model for this task
- [InSPyReNet fork](https://github.com/taskswithcode/InSPyReNet)
   - [![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://taskswithcode.com/salient_object_detection/)  & [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/salient-object-detection)
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

- [Notebook](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/InSPyReNet/blob/master/TWCSOD.ipynb)

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

- [ Compare two model outputs (SimMIM & VIT base) in Colab](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/SimMIM/blob/master/TWCSimMim.ipynb)
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
- Compare models through separate apps (Detic & OWL-ViT)
  - [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/DeticChatGPT).  Detic Model
  - [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo) OWL-ViT model

#### SOTA models
- [GRiT fork](https://github.com/taskswithcode/GriT)
  - [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)

<img src="divider.png"   width="1000px"/>


### Image Captioning
- [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/Where-is-Waldo-an-OWL-VIT-Demo) OWL-ViT model

#### SOTA models
-  GRIT fork [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/GRiT/blob/master/TWCGRiT.ipynb)

<img src="divider.png"   width="1000px"/>

### Video quality assessment

- DOVER fork  [Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/DOVER/blob/master/TWCDOVER.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/DOVER/blob/master/TWCDOVER.ipynb)


<img src="divider.png"   width="1000px"/>

### Self-supervised image representations

-  [MAE fork Evaluate in Colab](https://colab.research.google.com/github/taskswithcode/mae/blob/master/TWCMAE.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/mae/blob/master/TWCMAE.ipynb)



<img src="divider.png"   width="1000px"/>

### Sentence embeddings

#### Tasks
- Sentence Similarity Comparison app  [![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://taskswithcode.com/sentence_similarity/)  & [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/semantic_similarity)
-  Semantic Search Comparison app  [![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://taskswithcode.com/semantic_search/)  & [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/semantic_search)
-   Semantic Clustering Comparison app  [![Apps](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/TWCDemo.svg)](https://taskswithcode.com/semantic_clustering/)  & [![Hugging Face app](https://raw.githubusercontent.com/taskswithcode/image_assets/main/.github/images/huggingface.svg)](https://huggingface.co/spaces/taskswithcode/semantic_clustering)


#### SOTA models
- [SimCSE fork -  👨‍💻 for use in comparison app ](https://github.com/taskswithcode/SimCSE)
- [SGPT fork -  👨‍💻 for use in comparison app ](https://github.com/taskswithcode/sgpt)
- [DCPCSE fork -  👨‍💻 for use in comparison app ](https://github.com/taskswithcode/DCPCSE)
- [OpenAI embeddings wrapper 👨‍💻](https://github.com/taskswithcode/openai_api)
- [🤗 Hugging Face models wrapper 👨‍💻  for comparison app](https://github.com/taskswithcode/sentence_similarity_hf_model)


<img src="divider.png"   width="1000px"/>



### Exploratory tasks

-  [Latent Diffusion fork with Colab notebook](https://colab.research.google.com/github/taskswithcode/latent-diffusion/blob/master/TWCLatentDiffusion.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/latent-diffusion/blob/master/TWCLatentDiffusion.ipynb)   
- [Taming Transformers fork with Colab notebook](https://colab.research.google.com/github/taskswithcode/taming-transformers/blob/master/TWCTamingTransformer.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taskswithcode/taming-transformers/blob/master/TWCTamingTransformer.ipynb)



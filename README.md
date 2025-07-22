# Enhancing Text To Image_Generation
   This project, centered on Natural Language Processing (NLP), was undertaken as part of my M.Tech Major Technical Project (MTP) at IIT Bhubaneswar, under the guidance of Dr. Manoranjan Satpathy and Dr. Abhik Jana.

# Dataset Source: Text–Image Pairs for Prompt Expansion (Below are downloadable open-source-data links for image data)

This dataset is used for the research project titled: **"Enhancing Text-to-Image Generation via Prompt Expansion with Multimodal Language Models"**

curated **1,500 high-quality image–text pairs** across diverse visual domains for training a prompt-aware Stable Diffusion model using LoRA.

## 🗂️ Data Sources & Download Links

### 🐘 1. COCO 2014 Captions Dataset (General Scenes – 400 Pairs)

Download **only the annotations ZIP**:

- 📥 **COCO Captions Annotations (241MB)**  
  [http://images.cocodataset.org/annotations/annotations_trainval2014.zip](http://images.cocodataset.org/annotations/annotations_trainval2014.zip)


### 🌄 2. Unsplash (General Scenes – 400 Pairs)

- 📥 Use [Unsplash API](https://unsplash.com/documentation)  
  → Query with tags: `Nature`,  `Urban Architecture`,
`Sci-Fi`,  `Fantasy`, `Historical`, `Abstract`, `Artistic`, `Wildlife`, `Everyday Life`, `Emotions` 
  → Extract title/description + image

> 🔑 You’ll need to sign up for a developer API key at: [https://unsplash.com/developers](https://unsplash.com/developers)


### 🖼️ 3. WikiArt / ArtStation / DeviantArt (Abstract/Cultural – 700 Pairs)

- 📥 Option 1: **WikiArt Dataset (Kaggle, 25k+ images)**  
  [https://www.kaggle.com/datasets/csafrit2/wikiart](https://www.kaggle.com/datasets/csafrit2/wikiart)

- 📥 Option 2: Scrape from [https://www.wikiart.org/](https://www.wikiart.org/) using tags: `Nature`,  `Urban Architecture`,
`Sci-Fi`,  `Fantasy`, `Historical`, `Abstract`, `Artistic`, `Wildlife`, `Everyday Life`, `Emotions`

### 4. Data Split 
    90% Training = 1,255 pairs
    10% Validation = 140 pairs

Code and other source files uploading soon ......


<div align="center">

  <h1> TinyStories Regional <img src="https://png.pngtree.com/png-vector/20220812/ourmid/pngtree-indian-flag-design-png-png-image_6108311.png" width="20"> </h1>
  <img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F3a1a36ff-6d9a-4ee7-9494-3ae38adfe134_1920x600.png" alt="Vizuara Logo" style="width:80%;">

  [![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg?style=flat)](https://arxiv.org/abs/1234.56789)
  [![Huggingfaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/TinyStories-Regional)

  [![nirvan](https://img.shields.io/badge/nirvan-black?logo=github&logoColor=white&labelColor=black&color=black&style=flat)](https://github.com/nirvan840)
  [![malhar](https://img.shields.io/badge/malhar-black?logo=github&logoColor=white&labelColor=black&color=black&style=flat)](https://github.com/malharinamdar)
  [![agnivo](https://img.shields.io/badge/agnivo-black?logo=github&logoColor=white&labelColor=black&color=black&style=flat)](https://github.com/agme2019)
  [![raj](https://img.shields.io/badge/🌐-rajdandekar-black?logo=globe&logoColor=white&labelColor=black&color=black&style=flat)](https://www.linkedin.com/in/raj-abhijit-dandekar-67a33118a/?originalSubdomain=in)
  
</div>
<br>

> [!IMPORTANT]
> * <i> Currently, models only support story completion based on starting prompts :) </i>
> * <i> Guides to replicating and using the repository and the models are below! </i>
> * <i> Quality of Life updates to various scripts soon to come! </i>

> [!NOTE]
> * <i> <a href="https://tensordock.com/">TensorDock</a> for providing GPU access! Please check them out for easy-to-deploy and cheap GPU options 💚 </i>
> * <i> Special thanks to Microsoft for inspiring us with their original <a href="https://arxiv.org/abs/2305.07759">TinyStories</a> paper 💙 </i>
> * <i> <a href="https://huggingface.co/sarvamai">Sarvam</a>, <a href="https://huggingface.co/TWO">SUTRA</a>, and <a href="https://karpathy.ai/">Andrej Karpathy</a> for their open-source efforts ❤️ </i>

> [!WARNING]
> * Our TinyStories Regional paper will soon be on arXiv!
> * Any references to the paper below are currently not accessible 

```sh
git clone https://github.com/nirvan840/Vizuara-TinyStories-Regional.git
```
```sh
pip install -U g4f[all] transformers datasets huggingface_hub tiktoken wandb tqdm aiolimter numpy
```

---

<br> 

## 📚 Table of Contents

- 🗂️ Dataset Generation
  - [✍️ Preparing Prompts](#preparing-prompts)
  - [💬 Prompting a Model](#prompting-a-model)
- ⚙️ Training SLMs
  - [🔤 Tokenizing Data](#tokenizing-data)
  - [🏋️ Training the Model](#training-the-model)
- 🔍 Inference and Evaluation
  - [🤖 Inference Models (Local or HF)](#inference-models-local-or-hf)
  - [📊 Evaluate Inference/Stories](#evaluate-inference-stories)
- 📈 Results
  - [💡 Inference Examples](#inference-examples)
  - [✅ A Fitting Use Case](#a-fitting-use-case)
- 💰 Costs
  - [⏱️ Training Time and Costs](#training-time-and-costs)
  - [🔄 Replicating the Project](#replicating-the-project)

---

<br> 

## 🗂️ Dataset Generation 

> [!WARNING] 
> <i> This repository provides code to generate data by making API calls to SOTA models (4o, 4o-mini, Gemini-flash-1.5, etc.) using the [GPT-4-free (G4F)](https://github.com/xtekky/gpt4free) repository. We do not condone using this repository for large-scale dataset generation; we include it as a free alternative to paid API services. Please read and follow official OpenAI/Gemini guidelines. </i>

> [!NOTE]
> - **Our** datasets for Hindi, Marathi and Bengali generated using **GPT-4o-mini**, are **open-sourced** on our HF
> - **Translated** versions (Hindi and Bengali) of **Microsoft's TinyStories** dataset can also be found on our HF
> - Translated versions (our Hindi ➡️ Bengali ; Hindi ➡️ Marathi ; Bengali ➡️ Hindi) will be soon on our HF

<h2 id="preparing-prompts">✍️ Preparing Prompts</h2>



## 💬 Prompting a Model
- d
  
---

<br>

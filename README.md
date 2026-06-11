# Journal-Club-26-Applying-Multimodal-LLM-for-Medical-Research
2026 NIH Journal Discussion Club

**Section 1**: GPT and Attention Mechanism <p>
**June 11 (Thu): 2PM – 3PM**<p>
This session introduces the foundations of Generative Pre-trained Transformers (GPT), the attention mechanism, and the current technology. 
Papers will be discussed: 
* Vaswani A, et al. Attention is all you need. In: Advances in Neural Information Processing Systems (NIPS 2017); 2017. URL: https://arxiv.org/abs/1706.03762
* Brown TB, et al. Language models are few-shot learners. In: Advances in Neural Information Processing Systems (NeurIPS 2020); 2020. URL: https://arxiv.org/abs/2005.14165
* Singhal K, et al. Large language models encode clinical knowledge. Nature. 2023. URL: https://pmc.ncbi.nlm.nih.gov/articles/PMC10396962/

* Presentation slices: section1.pdf

* Python notebooks:
* Build a basic neural network: intro_neural_network_exerise.ipynb
* Build GPT basic architecture:
* -- numpy version: numpy_gpt2_gpt3_basic_architecture.ipynb
* -- Pytorch version: numpy_gpt2_gpt3_basic_architecture.ipynb
* -- Tensorflow version: tensorflow_gpt2_gpt3_basic_architecture.ipynb


**Section 2**: CLIP and Biomedical Multimodal Foundation Models <p>
**June 25 (Thu): 2PM – 3PM** <p>
This session introduces the idea of Contrastive Language-Image Pre-training (CLIP), biomedical language model pre-training with PubMedBERT, and the extension of CLIP-style multimodal learning to biomedical image-text pairs using BiomedCLIP.
Papers will be discussed:
* Radford A, et al. Learning transferable visual models from natural language supervision. In: International Conference on Machine Learning (ICML 2021); 2021. URL: https://arxiv.org/abs/2103.00020
* Gu Y, et al. Domain-specific language model pretraining for biomedical natural language processing. ACM Transactions on Computing for Healthcare. 2021. URL: https://arxiv.org/abs/2007.15779
* Zhang S, et al. BiomedCLIP: a multimodal biomedical foundation model pretrained from fifteen million scientific image-text pairs. 2023. URL: https://arxiv.org/abs/2303.00915

* Python notebooks:
* Train a CLIP model using chest X-ray image and text pairs: clip_chest_xray.ipynb
* Use the BiomedCLIP backbone for downstream chest X-ray classification: biomedclip_chest_xray_mlp.ipynb
* Zhang S, et al. BiomedCLIP: a multimodal biomedical foundation model pretrained from fifteen million scientific image-text pairs. 2023. URL: https://arxiv.org/abs/2303.00915

* Python notebooks:
* Train a CLIP model using chest X-ray image and text pairs: clip_chest_xray.ipynb
* Use the BiomedCLIP backbone for downstream chest X-ray classification: biomedclip_chest_xray_mlp.ipynb

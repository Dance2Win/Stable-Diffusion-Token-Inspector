# Stable-Diffusion-Token-Inspector
Stable Diffusion - want to know all of the trained tokens in a model?

# Inspiration and related projects
Currently, there are a few repositories in this category of exploration:
1) AUTOMATIC1111's webUI plugin "Embedding Inspector" (robust, requires SD and Auto's): https://github.com/tkalayci71/embedding-inspector
2) CLIP Tokenizer (not related to the post-trained weights but instead the results of CLIP tokenization into a first-order tensor): https://github.com/AUTOMATIC1111/stable-diffusion-webui-tokenizer
3) WebUI Finetuning Tokens extension: unique token generator (refers to the CLIP vocabulary list): https://github.com/CodeExplode/stable-diffusion-webui-finetuning-tokens
4) SD Token Checker (used to explode strings into CLIP identified tokens): https://github.com/yushan777/stable-diffusion-token-checker

# Goals
1) Create a Colab that can view individual post-trained tensors (like the Embedding Inspector) as well as dump the 50,000+ tokens for mass analysis.
2) If #1 is completed, integrate the CLIP Tokenizer tool in to be able to see results of a prompt turned into CLIP and then into post-trained weights.

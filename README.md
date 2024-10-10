# Composed-Image-Retrieval-using-CLIP
We focus on implementing Composed Image Retrieval (CIR). Unlike the Text-Image Retrieval task, which retrieves images according to texts, composed image retrieval aims to identify the target
image corresponding to the input query, composed of a reference image and a text modifier describing how the reference image should be modified. We employ a large pre-trained vision-language model CLIP as the
backbone to efficiently train a CIR model. 

In the CIR task, vision and text features are extracted by vision and text encoders, respectively. Then, vision and text features are fused to get fused features that are expected to be similar to the target features,
so we can calculate their similarity and retrieve images according to the sort of similarity.

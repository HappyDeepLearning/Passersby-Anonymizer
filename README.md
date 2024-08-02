# Passersby-Anonymizer

## Passersby-Anonymizer: Safeguard the Privacy of Passersby in Social Videos

This respository contains the code for theIEEE-IJCB-2024 Special Session on Generative AI for Futuristic Biometrics paper Passersby-Anonymizer: Safeguard the Privacy of Passersby in Social Videos.
<div align="center">
    <a><img src="fig1_overview.pdf"  width="100%" ></a>
</div>

## Abstract
In the current era of pervasive short video content, the exposure of passersby's data frequently raises privacy concerns. Traditional anonymization techniques for passersby, like blurring and mosaicing, are often used before uploading such videos. However, these methods tend to degrade the informational richness of the visual content, markedly reducing the quality of the anonymized videos. Recent advancements of diffusion models have paved the way for text-guided image and video synthesis, yet applying these models to the anonymization of passersby poses three main challenges: (i) bridging the domain gap between specific passersby data and high-quality image/video datasets that are used for pre-training diffusion models, (ii) ensuring temporal consistency in the anonymized videos, and (iii) preserving the integrity of video subjects’ content while exclusively anonymizing passersby-related information. To address these challenges, we propose the Passersby-Anonymizer, a novel diffusion-based framework for anonymizing identity-specific attributes in video content. At its core, our model introduces a spatial content adapter (SCA) to adapt to the visual patterns of passersby image datasets. We introduce a Temporal Content Stabilizer (TCS) to maintain the temporal consistency of the anonymized videos. Furthermore, we design a mask-aware training strategy that specifically targets the anonymization of the mask region while preserving the integrity of other contents. Our experimental evaluations demonstrate that our model effectively addresses the challenge of anonymizing passersby without compromising the informational integrity of the social videos. The source code for our method will be made available.

# Full-Page-handwriting-recognition-on-cuda-enabled-docker
Handwritten text recognition is a critical aspect of document digitization, often relying on convolutional and recurrent neural networks alongside language models. This paper introduces TrOCR, an end-to-end framework that harnesses pre-trained Transformer models from HuggingFace to enhance text recognition. TrOCR demonstrates superior performance across both printed and handwritten text domains, leveraging synthetic data for pre-training and human labeled datasets for fine-tuning. Microsoft TrOCR stands out as the most accurate model available to date for text recognition. Nonetheless, TrOCR encounters challenges in multiline text recognition. To overcome this limitation, we integrate PaddleOCR alongside TrOCR. PaddleOCR specializes in text detection and, when combined with TrOCR, facilitates the recognition of multiline text within images. This integration results in a robust solution for fullpage handwriting recognition. 

Through experimentation with various OCR libraries and integration of different text detection models, we addressed challenges such as multi-line text
extraction and accuracy enhancement.

Leveraging GPU utilization and multi-threading optimizations, we significantly improved
execution time and system performance. The transition to a user-friendly Flask API with a
Gradio demo and deployment using Docker encapsulates the project's evolution into a fully
functional and deployable system for handwritten text extraction.
![image](https://github.com/gaurvi-vishnoi/Full-Page-handwriting-recognition-on-cuda-enabled-docker/assets/83802095/fa5945fa-6ff9-4940-adfb-2e07cd0c24e4)



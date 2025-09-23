# FitChef – AI Recipe & Image Generator

FitChef is an intelligent multimodal system that generates personalized food recipes and realistic dish images.  
It combines a fine-tuned T5 model for recipe text generation with a Diffusion model for image creation.

## Tech Stack
- Python
- Hugging Face Transformers (Flan-T5)
- Diffusers (Stable Diffusion)
- Scikit-learn, Pandas
- Gradio for interface
- CLIP for text–image alignment

## Features
- Generates personalized recipes based on user ingredients, goals, and dietary restrictions
- Produces realistic food images from generated recipes
- Interactive Gradio web app for user-friendly access

## Results
- Fine-tuned T5 achieved high-quality recipe generation
- Evaluated with ROUGE and BERTScore
- CLIP used to validate recipe–image alignment

---
👩‍💻 Built with Google Colab and deployed via Gradio.

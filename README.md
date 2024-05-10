# Procedure Used

This README outlines the procedure used to create, upload, train, and fine-tune the Llama 8B Instruct model.

## 1. Create Building Data

   - Generated relevant building data using the building handbook to fine-tune the model. This data includes information about building physics, standards, codes, etc. 

## 2. Upload to Hugging Face Repo

   - Uploaded the building data to the Hugging Face model repository.

## 3. Create Token for Authentication

   - Generated an authentication token for accessing the Hugging Face model repository. This token was used for authentication during model training and fine-tuning.

## 4. Train the Llama 8B Instruct Model

   - Trained the Llama 8B Instruct model using the uploaded building data. This step involved initializing the model with the pre-trained weights and fine-tuning it on the building data.

## 5. Fine-Tune the Model Using LoRA Through Unslot

   - Fine-tuned the Llama 8B Instruct model using LoRA.

## 6. Major Problems Encountered

   - When Colab was used, GPU was exhausted; see attached image
   - Tried running on my CPU, but my storage space was full
   - The office server had a CUDA compatibility issue

## 7. Final Goal

   - The model ran successfully on a friend's paid GPU version on Colab.

Thank you for the opportunity; I have indeed extended my knowledge on this subject matter. This interview was worth the attempt. Now, I enjoy the idea of building custom LLM.

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




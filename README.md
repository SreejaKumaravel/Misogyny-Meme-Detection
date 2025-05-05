This project contains code for a multimodal classification model that detects misogyny in memes through image input and text input data. It uses ResNet-50 for image features and BERT for text embeddings and puts them together in a joint classifier to accurately predict whether a meme has misogynist content.
Project structure
├── train.csv / dev.csv        # Metadata files with image_name, transcriptions, labels
├── train/ / dev/              # Folders containing corresponding meme images
├── Misogyny_Meme_Detection.ipynb


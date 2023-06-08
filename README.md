# baby-cry-analysis
baby cry analysis to identify the reason behind baby's cry
1. CNNmc is a Multi input CNN with the 2 features mel spectrogram and cqt spectrogram
2. CNNfm is a Multi input CNN with the 2 features mel spectrogram and mfcc
3. SVM is a sipported victor machine with VGG16 feature extraction 
4. spectoT Extract cqt and mel spectrograms from audios and save them in another directory
5. augmentation is obviously to apply augmentation for audios 
7. ViT Training a ViT from scratch on smaller datasets with shifted patch tokenization and locality self-attention

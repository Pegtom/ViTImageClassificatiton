# Vision Transformers FineTunning

# Modeling
I used the Hugging Face library to train my dataset; I borrowed ViTFeatureExtractor class from it. Here's the link: https://huggingface.co/docs/transformers/model_doc/vit#:~:text=configuration%20%3D%20model.config-,ViTFeatureExtractor,-class%20transformers.

# Dataset
I had to upload my dataset; I used the Kaggle dataset. If you need help uploading your dataset from Kaggle, check out this link:
  https://www.kaggle.com/general/74235.
  
 You can use the datasets which are already available in Huggin Face via this link: https://huggingface.co/datasets?task_categories=task_categories:image-classification
  
 # Results
 After I trained my dataset, I got 0.995 evaluation accuracy. I wanted to know which images decreased our accuracy, so I predicted the labels and found out which was the problem. 


 ![alt text](https://user-images.githubusercontent.com/24693328/197225051-235ce034-3e92-4ed3-8501-cb88e32188e8.png)


As you can see, the model classified this specific image into the fire category because of the reddish background resembling fire flames.

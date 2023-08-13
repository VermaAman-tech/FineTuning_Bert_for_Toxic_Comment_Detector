The original file can be found in 
https://colab.research.google.com/drive/1eojz3Prv7xsLtGGCuOCccMQlaA7hVvQ9?usp=sharing

The Model I used was BERT from where the Trainer Tokenizer and lot of other functions are used and the main
aim was to FineTune it to get a particular task done that was
To detect Toxic Comments and the user can end the comments in the box and next to it its toxicity can be known

I think this can be used in many online platforms to avoid Toxic comments being posted and is already used by some 
companies to detect and remove bad comments.

The dataset used is 
https://drive.google.com/file/d/19GdyBPhmsWPVXb_ua2SMrN1_R4w75Nb5/view?usp=sharing

Which I downloaded from kaggle from this competition
https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data
Where I downloaded the dataset available and used the train.csv 


This is how it looks after running the gradio app.
<img width="960" alt="image" src="https://github.com/VermaAman-tech/FineTuning_Bert_for_Toxic_Comment_Detector/assets/122050072/5487d256-9094-436d-aa6c-5ae624057ee8">

There were some challenges faced like linking the GPU and merging the Gradio to the model and some Pytorch related functions showed errors which was resolved by restarting the runtime and fixing out stuff

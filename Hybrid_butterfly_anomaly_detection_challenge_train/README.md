How to train the model
1. download `both` directory at https://drive.google.com/drive/folders/1IqKJkVNm7QnQ81fPxPkm63J8TlTOPBo6?usp=sharing
* structure your directories like this:
```
Hackathon-Butterfly-Hybrid (cloned repository)
│
├── input_data (create this folder and place the downloaded `both` directory inside)
│   ├── both (download and place here)
├── DINO_notebook (run the notebook inside this folder)
├── DINO_train (no need to modify this)
├── submission (contains two example submissions)
│   ├── submission_detr_svm/
│   ├── submission_DINO_svm/
│   ├── model.py 
```


2. Open DINO_notebook.ipynb and start running it.
There should be no bugs as long as you set up the directories correctly.
After running the notebook, rename the generated .pkl file to clf.pkl
(since the generated file will have a name like DINO_svm.pkl, etc.)

3. Uploading to Codabench - Quick Guide
When submitting, package the following files into a .zip file:
model.py (provided)
clf.pkl (your generated file)
requirements.txt
Upload the .zip file to Codabench for submission.

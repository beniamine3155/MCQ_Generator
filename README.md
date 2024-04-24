pip install ipykernel

conda create -p env python=3.11 -y

source activate ./env

pip list

git status

ls -a

git add .

git commit -m "folder structure updated"

git config --global user.email "beniamine3155@gmail.com"

git config --global user.name "beniamine3155"

git commit -m "folder structure updated"

git remote add origin https://github.com/beniamine3155/MCQ_Generator.git

git push -f origin main

pip install -r requirements.txt

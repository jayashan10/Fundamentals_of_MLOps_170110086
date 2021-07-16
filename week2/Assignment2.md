https://github.com/jayashan10/mlops_Assignment


List of commands used:

 git -C ./Desktop/ clone https://github.com/jayashan10/mlops_Assignment
 dvc init
 dvc cache dir ../external_cache
 dvc add data/creditcard.csv
 git add data/creditcard.csv.dvc data/.gitignore
 git commit -m "added raw data"
 git branch -M main
 dvc remote add -d storage s3://mlopsweek2part1/datastore
 git add .dvc/config
 git commit -m "configure remote storage"
 dvc push
 git push origin main
 
 
 
 

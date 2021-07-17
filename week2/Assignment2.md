## Repo used for assignment: https://github.com/jayashan10/mlops_Assignment

## List of commands used:

 - git -C ./Desktop/ clone https://github.com/jayashan10/mlops_Assignment
 - dvc init
 - dvc cache dir ../external_cache
 - dvc add data/creditcard.csv
 - git add data/creditcard.csv.dvc data/.gitignore
 - git commit -m "added raw data"
 - git branch -M main
 - dvc remote add -d storage s3://mlopsweek2part1/datastore
 - git add .dvc/config
 - git commit -m "configure remote storage"
 - dvc push
 - git push origin main

### decision-tree scores:
- f1 score is: 0.7230046948356808
- the accuracy score is: 0.9989642217618764

### Random forest scores:
- f1 score is: 0.8969696969696971
- the accuracy score is: 0.9997015554229135
 
 
 ## Screenshot of the aws s3 bucket
 
 ![Screenshot (346)](https://user-images.githubusercontent.com/63214321/126049599-77524bfe-f0ad-4c78-85c4-00055bbbb7fa.png)

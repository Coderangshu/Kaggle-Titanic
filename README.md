<H3> Working with CI/CD for continuous machine learning </H3>
  
  - Working on Kaggle-Dataset
  - we also implement github actions for CI/CD using cml (similar to DevOps)
  - Originally the work is done in jupyter notebook but for the purpose of CI/CD the ipynb is converted to python script using the following command in yaml:
      jupyter nbconvert --to script classifier.ipynb

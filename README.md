# Command line parameter
m: choose model  
s: sequence by sequence  
c: class(16/4)
e: enable early stop

# Avalible model
| name | description                   | accuracy |
| --   | ---                           | --       |
| cnn  | cnn+maxpool+cnn+maxpool+dense |          |
| lstm | lstm+lstm+dense               |          |


# csv column
|name | description|
|-----|------------|
|type| 16 types|
|posts| long sentence, maxlength=2312|
|IE | I=1,E=0 |
|NS | N=1,S=0 |
|TF | T=1,F=0 |
|JP | J=1,P=0 |
___
# Models list
## yeqy_CNN

    [ 2019-01-17 07:05:59,126][end2end]
    Accuracy(Total) on test set(10%) = 0.5362232779097387
    Accuracy(One by one) on test set(10%) = 0.813687648456057
    [I] precision: 0.544, recall: 0.919, f1: 0.684
    [E] precision: 0.970, recall: 0.774, f1: 0.861
    [N] precision: 0.509, recall: 0.987, f1: 0.672
    [S] precision: 0.998, recall: 0.853, f1: 0.920
    [T] precision: 0.890, recall: 0.763, f1: 0.821
    [P] precision: 0.767, recall: 0.892, f1: 0.825
    [J] precision: 0.808, recall: 0.787, f1: 0.797
    [F] precision: 0.673, recall: 0.701, f1: 0.686
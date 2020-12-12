# KAIST 2020 Fall CS470 Project (Team 22)

This is code repository of team 22.

Topic: Adversarial Training with Complex Attacks

Member: 박종찬, 유승진, 정원빈

## Project Description

This project is about suggestion of complex adversarial training against multiple adversarial attacks.

Please refer our final report to know more about the project.

## Code Description

There is two .ipynb files in code directory and seven .pth files in pretrained directory.

PGD_FGSM.ipynb: This is code of training and testing average/complex attack of PGD and FGSM attack. 

DDN_FGSM.ipynb: This is code of training and testing average/complex attack of DDN and FGSM attack. 

You may change parameter in parser default setting cell.

FGSM.pth: This is pre-trained GoogLeNet model that trained by FGSM attack.

PGD.pth: This is pre-trained GoogLeNet model that trained by PGD attack.

DDN.pth: This is pre-trained GoogLeNet model that trained by DDN attack.

AVG_FGSM_PGD.pth: This is pre-trained GoogLeNet model that trained by average attack of FGSM and PGD.

CMPLX_FGSM_PGD.pth: This is pre-trained GoogLeNet model that trained by complex attack of FGSM and PGD.

AVG_FGSM_DDN.pth: This is pre-trained GoogLeNet model that trained by average attack of FGSM and DDN.

CMPLX_FGSM_DDN.pth: This is pre-trained GoogLeNet model that trained by complex attack of FGSM and DDN.

## References
https://blog.csdn.net/u012436149/article/details/77017832 

https://discuss.pytorch.org/t/how-do-i-check-the-number-of-parameters-of-a-model/4325/8

https://github.com/utkuozbulak/pytorch-cnn-adversarial-attacks

https://github.com/locuslab/fast_adversarial

https://github.com/louis2889184/pytorch-adversarial-training

https://github.com/badchild0912/DDN-attack

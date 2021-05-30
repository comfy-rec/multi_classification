# multi classification

a keras implementation of simple cnn model based 8 classes(airplane, car, cat, dog, flower, fruit, motorbike, person) classification on supervised learning.

## requirements

keras 2.2.4

matplotlib 3.4.2

numpy 1.20.1

opencv-python 4.5.2.52

python 3.7.10

scikit-learn 0.24.2

tensorflow 2.1.0

anaconda 3

pycharm

## datasets

airplane - 727 images

car - 968 images

cat - 885 images

dog - 702 images

flower - 843 images

fruit - 1000 images

motorbike - 788 images

person - 986 images

### train

train ratio - 0.7 each class

validation ratio - 0.2 each class

data augmentation - rescale, width shift, height shift, horizontal flip

### test

test ratio - 0.1 each class

data augmentation - rescale

## usage

### data preprocessing

8mul_preprocessing.py

### train

8mul.py

### test

8mul_test.py

## conclusion

### 8mul train accuracy

![8mul_train_acc](https://user-images.githubusercontent.com/62055003/120117123-a6241500-c1c6-11eb-98ef-e4127abf56ef.png)

### 8mul train loss

![8mul_train_loss](https://user-images.githubusercontent.com/62055003/120117142-ba681200-c1c6-11eb-91e7-b3e8e88573ec.png)

### 8mul test images

![test_airplane](https://user-images.githubusercontent.com/62055003/120117150-ca7ff180-c1c6-11eb-9862-6724c5a8f4a1.png)

![test_car](https://user-images.githubusercontent.com/62055003/120117153-ce137880-c1c6-11eb-9573-9d6f81d4fb6a.png)

![test_cat](https://user-images.githubusercontent.com/62055003/120117155-d10e6900-c1c6-11eb-8dae-a9c39af4d736.png)

![test_dog](https://user-images.githubusercontent.com/62055003/120117163-d4a1f000-c1c6-11eb-8eba-c26187a70020.png)

![test_flower](https://user-images.githubusercontent.com/62055003/120117172-d7044a00-c1c6-11eb-89ef-67913d415f0e.png)

![test_fruit](https://user-images.githubusercontent.com/62055003/120117174-d966a400-c1c6-11eb-8e96-9ff34b16c7df.png)

![test_motorbike](https://user-images.githubusercontent.com/62055003/120117176-db306780-c1c6-11eb-8ffd-b90f90b79163.png)

![test_person](https://user-images.githubusercontent.com/62055003/120117177-dcfa2b00-c1c6-11eb-9652-c0b7f66e9de3.png)

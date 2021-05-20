I used https://github.com/xahidbuffon/FUnIE-GAN method for restoration here is my marked dataset https://drive.google.com/drive/folders/14rRGVZgIeswJrvdYwJ7_lqfLM3Jjl0l3?usp=sharing

My diploma's theme has a bit specific application area - sunken technical objects. I have to restorate underwater images. And to prove useability of restoration method for autonomous underwater vechile (AUV) I decided to compare quality of CNN model train with preprocessing and without it. Due to the lack of data I use mirroring by way of augmentation. And to preprocess hundreds of images of images I used this method https://github.com/xahidbuffon/FUnIE-GAN .

Firstly, I use CNN model without fine-tuning and model trained on natural images was definitely better. However second step was with AlexNet and in that case preprocessing improved quality.

Need some help with conclusion of that experiment. As far as I aware it can be connect with squeezing of restoration method in first step, and with familiar color spectrum between fixed images and ImageNet images in the second.

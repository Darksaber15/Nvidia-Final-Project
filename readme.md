# Automated Threat Scout

 This project is a real time weapon detection sytem. When running it can identify when there is a weapon in frame and will produce bounding boxes around the weapon. This is useful because it can be used as a DIY, easy to set, up security system that is unmanned, meaning it does not have to be monitored by a person. I decided on this as my project because I thought it would be cool and I wanted to see how far I could push the technology but also create something that has practical applications.

![add image descrition here](direct image link here)

## The Algorithm

I obtained the dataset that I trained the system on from here: https://www.kaggle.com/datasets/snehilsanyal/weapon-detection-test/data 

This system uses YOLOv5 as the base model trained with a dataset from Kaggle which includes 9 different weapon classes that are: Automatic Rifle, Bazooka, Handgun, Knife, Grenade Launcher, Shotgun, SMG, Sniper, Sword. 

## Running this project

1. Install pyTorch on to your system.
2. Run "pip install -r requirements.txt" command
3. 

[View a video explanation here](video link)

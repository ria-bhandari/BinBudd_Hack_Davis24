## Problem Statement 🗑️
How can people figure out where to throw their trash away? Sometimes a Google Search isn't effective enough.

## Inspiration 💫
According to World Bank statistics, global waste output is projected to continue increasing. Despite various factors contributing to this rise, only 19% of waste is currently recovered through recycling. Most recycling efforts fail due to an excess of contaminants. By using our app, we aim to reduce the amount of contaminants, enhancing recycling efforts and increasing waste recovery. 

## What it does ♻️
BinBud is an app that enables users to take a photo of their trash. The app connects to a VGG16 Classification model trained by our team, providing users with guidance on where to properly dispose of their waste.

## How we built it 🛠️
Our VGG16 model is made in a python notebook using one of the Keras libraries. The model is trained on 4GBs 25 thousand images that range from various websites such as Kaggle and Datasource.ai. 

When it's time for the model to be ran, the training images and testing images are preprocessed before training or testing begins. It will then regularly run through the slightly tweaked VGG16 model. To the the details on the model please go to our GitHub Repository: [BinBud Repo](https://github.com/ria-bhandari/BinBudd_Hack_Davis24)

The app that we made for our model was made through android studio.

## Challenges we ran into 😰

One of the challenges that we ran into was waiting for our model to train. None of our PCs that any of our team owns are the powerful. As a result we decided to learn about Virtual Machines. We learned about Tailscale and ran our model through them. 

We also came across multiple problems in app development because all of us are pretty new to whole subject. 

## Accomplishments that we're proud of 😎

Our team learned about Virutal Machines and App Development. Two things are group either rarely comes across are has never come across before. 

The VGG 16 model outclasses most contemporary models and classifies trash across 14 categories with an average accuracy of 92%. With Bin Bud, we give you the power to save the world with every click!

## What's next for BinBud! 📱

It would be very cool to release the app to the public. Right now it only works locally when connected to a computer as a local server. 


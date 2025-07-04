---
title: About
layout: index.njk
---

## About Me

Hi, I'm Vincent Wang, a third year student studying mathematics at the University of Waterloo.


## Experience

I'm currently working as a DevOps Engineer at Sunlife, working with Java, Kubernetes, and all sorts of other tools and technologies. Here are my past experiences.


## Projects

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="display: flex; align-items: center;">
    <h3 style="margin: 0 8px 0 0;">Visual Metronome</h3>
    <p style="margin: 0; font-weight: normal;">| Java, Gradle</p>
  </div>
  <p>
    <a href="https://runelite.net/plugin-hub/show/visual-metronome" style="font-weight: normal; text-align: right;" >[runelite]</a>
    <a href="https://github.com/vincent0955/Visual-metronome" style="font-weight: normal; text-align: right;" >[github]</a>
  </p>
</div>

- Created one of the most popular external plugins “Visual Metronome” for an open-source video game client called RuneLite

- Used Java, RuneLite API, and Gradle to create a highly customizable 2D and 3D environment overlay UI to help with timing-based activities in the game

- 100,000+ active installs, 25+ updates, including multiple issues/feature requests submitted from the users and implemented

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="display: flex; align-items: center;">
    <h3 style="margin: 0 8px 0 0;">Machine Learning Triggerbot</h3>
    <p style="margin: 0; font-weight: normal;">| Python, TensorFlow, NumPy</p>
  </div>
  <a href="https://github.com/vincent0955/tensorflow-triggerbot" style="font-weight: normal; text-align: right;" >[github]</a>
</div>

- Developed a Python program that detects enemies and automatically shoots in first-person shooter games by recording the users’ screen and then using a convolutional neural network to classify 28x28px screen frames

- Built and trained the neural network using TensorFlow/Keras with a self-created dataset of 2800 images, preprocessed the images and adjusted the network layers to achieve over 93% validation accuracy during training

- Used ONNX runtime to reduce average prediction time from 30ms to 10ms to allow the program to practically work in-game

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="display: flex; align-items: center;">
    <h3 style="margin: 0 8px 0 0;">Calorie Counter React App</h3>
    <p style="margin: 0; font-weight: normal;">| React, JavaScript, Node.js, Express, MongoDB </p>
  </div>
  <a href="https://github.com/vincent0955/macro-tracker" style="font-weight: normal; text-align: right;" >[github]</a>
</div>

- Created a full stack web application that lets users count calorie and macronutrient intake and organizes the data in order to easily track their diet goals 

- Coded the backend using Node.js and Express, created REST API endpoints to call from the MongoDB database, allowing the user to set daily goals, view reports of their recent activity, search, and filter through the users’ entries

- Used React and Material UI to create a user-friendly frontend to display the organized data and allow the user to view summaries of specific weeks and days 

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="display: flex; align-items: center;">
    <h3 style="margin: 0 8px 0 0;">Japanese Text OCR</h3>
    <p style="margin: 0; font-weight: normal;">| Python, HuggingFace, PyTorch, Pandas, Numpy </p>
  </div>
  <a href="https://github.com/vincent0955/vit-japanese-ocr" style="font-weight: normal; text-align: right;" >[github]</a>
</div>

- Created a Japanese Text OCR (Optical Character Recognition) that extracts Japanese text from images using a Vision Encoder-Decoder Transformer model, utilizing tools from HuggingFace and PyTorch

- Composed of a DeiT encoder and BERT decoder to process the image and then generate the final text

- Used Pandas to preprocess a large dataset of 110,000 image-text pairs, optimizing it to a refined subset of 5,000 entries due to system limitations, and fine-tuned the model on the optimized dataset 


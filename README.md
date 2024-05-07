<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Distracted Driver Detection</title>
</head>
<body>
  <h1>Distracted Driver Detection</h1>
  <h2>Overview</h2>
  <p>This project tackles the critical issue of distracted driving, a major safety hazard. Deep learning models are utilized to analyze in-vehicle dashboard camera footage and distinguish between safe driving and various forms of distraction.</p>
  <h3>Key Features</h3>
  <ul>
    <li>Deep learning models (CNNs and pre-trained architectures) analyze dashboard camera images.</li>
    <li>Target distractions include texting, phone use, reaching for objects, and passenger conversation.</li>
    <li>Regularization techniques (Early Stopping, Dropout, Normalization) prevent overfitting.</li>
    <li>Project goal: Identify the most effective model for real-time driver distraction detection, ultimately enhancing road safety.</li>
  </ul>
  <h2>Data Description</h2>
  <p>The project leverages a subset of the State Farm Distracted Driver Detection Kaggle competition dataset. This dataset consists of:</p>
  <ul>
    <li><strong>Images:**</li>
      <ul>
        <li>22,424 dashboard camera images categorized into 10 classes (c0-c9) representing driver behavior.</li>
        <li>c0: Safe driving</li>
        <li>c1-c4: Texting/Talking on phone (left/right hand)</li>
        <li>c5: Operating radio</li>
        <li>c6: Drinking</li>
        <li>c7: Reaching behind</li>
        <li>c8: Hair and makeup</li>
        <li>c9: Talking to passenger</li>
      </ul>
    <li><strong>Image Preprocessing:**</li>
      <ul>
        <li>Original RGB images (480x640) resized to 120x160 for computational efficiency.</li>
      </ul>
    <li><strong>CSV File:**</li>
      <ul>
        <li>Provides image filename, subject ID, and corresponding class ID.</li>
      </ul>
  </ul>
  <h2>Project Objective</h2>
  <p>The primary goal is to develop a robust deep learning model that accurately classifies driver behavior in each image based on the 10 defined classes. This model has the potential to significantly improve road safety by preventing accidents and aiding insurance companies in addressing distracted driving.</p>
</body>
</html>

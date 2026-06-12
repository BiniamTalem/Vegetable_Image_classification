{
  "title": "Dataset Augmentation and Transfer Learning for Neural Networks",
  "purpose": [
    "Familiarize with dataset augmentation techniques using images.",
    "Learn and apply transfer learning methods for neural networks."
  ],
  "task_overview": {
    "dataset_description": {
      "classes": [
        "Beans",
        "Bitter Gourd",
        "Bottle Gourd",
        "Eggplant",
        "Broccoli",
        "Cabbage",
        "Capsicum",
        "Carrot",
        "Cauliflower",
        "Cucumber",
        "Papaya",
        "Potato",
        "Pumpkin",
        "Radish",
        "Tomato"
      ],
      "total_images": 21000,
      "images_per_class": 1400,
      "image_resolution": "224x224",
      "format": ".jpg",
      "dataset_split": {
        "training": "approximately 70%",
        "validation": "approximately 15%",
        "testing": "approximately 15%"
      },
      "dataset_link": "https://drive.google.com/drive/folders/1He5s1VTwm74jVUFvncyW2tkpX9zx9_82X?usp=sharing"
    },
    "tasks": [
      {
        "name": "Basic CNN Classification",
        "description": "Develop a CNN to classify vegetable images, train, and evaluate.",
        "actions": [
          "Build CNN model",
          "Train on training set",
          "Plot learning and validation curves",
          "Evaluate on test set"
        ]
      },
      {
        "name": "Augmented Dataset Classification",
        "description": "Apply dataset augmentation techniques, retrain the CNN, and compare performance.",
        "actions": [
          "Apply augmentation (see lectures 3-4)",
          "Retrain CNN on augmented data",
          "Compare with previous results",
          "Draw conclusions on augmentation impact"
        ]
      },
      {
        "name": "Transfer Learning with Pre-trained Models",
        "description": "Use pre-trained models (Keras or PyTorch), fine-tune on initial and augmented datasets, and compare results.",
        "actions": [
          "Select at least 3 pre-trained models",
          "Fine-tune models on initial dataset",
          "Fine-tune models on augmented dataset",
          "Compare model performances",
          "Optional: Test on external vegetable images from the internet"
        ],
        "links": {
          "keras_models": "https://keras.io/api/applications/",
          "pytorch_models": "https://pytorch.org/vision/0.8/models.html"
        }
      }
    ]
  },
  "notes": [
    "Emphasize understanding dataset augmentation and transfer learning benefits.",
    "Visualize results with plots and summarize conclusions.",
    "Focus on building, training, and evaluating neural networks."
  ],
  "good_luck_message": "Good luck and happy coding!"
}

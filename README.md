{
  "title": "Dataset Augmentation and Transfer Learning for Neural Networks",
  "purpose": [
    "Familiarize with dataset augmentation techniques using images",
    "Learn and apply transfer learning methods for neural networks"
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
      "image_resolution": "224x224 pixels",
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
        "title": "Basic CNN Classification",
        "description": "Build a CNN to classify vegetable images, train on training set, plot learning and validation curves, evaluate on test set."
      },
      {
        "title": "Augmented Dataset Classification",
        "description": "Apply dataset augmentation techniques, retrain the same CNN architecture, compare performance with previous results, and analyze the impact."
      },
      {
        "title": "Transfer Learning with Pre-trained Models",
        "description": "Use pre-trained models from Keras or PyTorch, fine-tune at least 3 models on initial and augmented datasets, compare results, and optionally test on internet images."
      }
    ],
    "notes": [
      "Involves building, training, and evaluating neural networks.",
      "Focus on understanding the benefits of dataset augmentation and transfer learning.",
      "Visualize results with plots and summarize conclusions."
    ],
    "good_luck_message": "Good luck and happy coding!"
  }
}

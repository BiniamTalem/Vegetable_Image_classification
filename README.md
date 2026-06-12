{
  "project_title": "Augmentation of datasets from images and transfer learning for neural networks",
  "purpose": [
    "To get acquainted with the augmentation of datasets from images",
    "Learn how to transfer learning for neural networks"
  ],
  "dataset_description": {
    "classes": [
      "beans", "bitter gourd", "bottle gourd", "eggplant", "broccoli",
      "cabbage", "capsicum", "carrot", "cauliflower", "cucumber",
      "papaya", "potato", "pumpkin", "radish", "tomato"
    ],
    "total_images": 21000,
    "images_per_class": 1400,
    "image_resolution": "224x224",
    "format": "jpg",
    "split_ratio": {
      "train": "70%",
      "validation": "15%",
      "test": "15%"
    },
    "data_source": "https://drive.google.com/drive/folders/1He5s1VTwm74jVUFvncyW2tkpX9zx982X?usp=sharing"
  },
  "tasks": [
    {
      "task_id": 1,
      "title": "Baseline CNN Classification",
      "description": "Solve classification using a convolutional neural network on the original dataset.",
      "actions": [
        "Build training and validation curves",
        "Test results on the test set"
      ]
    },
    {
      "task_id": 2,
      "title": "CNN with Augmented Dataset",
      "description": "Same CNN architecture as Task 1, but applied on a pre-augmented dataset.",
      "actions": [
        "Compare results with Task 1",
        "Draw conclusions"
      ]
    },
    {
      "task_id": 3,
      "title": "Transfer Learning",
      "description": "Solve classification for both original and augmented datasets using pre-trained models.",
      "requirements": [
        "Use at least 3 pre-trained models",
        "Available frameworks: Keras (https://keras.io/api/applications/) or PyTorch (https://pytorch.org/vision/0.8/models.html)"
      ],
      "actions": [
        "Compare classification results",
        "Draw conclusions",
        "Optional: Test on arbitrary internet images of vegetables"
      ]
    }
  ],
  "expected_deliverables": [
    "Training and validation curves for each task",
    "Test set accuracy results",
    "Comparison between baseline, augmented, and transfer learning models",
    "Conclusions based on performance differences",
    "(Optional) Predictions on custom internet images"
  ],
  "frameworks_suggested": {
    "keras_models": "https://keras.io/api/applications/",
    "pytorch_models": "https://pytorch.org/vision/0.8/models.html"
  },
  "status": "planned"
}

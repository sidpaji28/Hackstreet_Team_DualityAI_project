# Hackstreet_Team_DualityAI_project



# 🚀 Space Station Hackathon - YOLOv8 Training Setup

This repository contains the setup, training workflow, and scripts to train a YOLOv8 object detection model as part of the Space Station Hackathon. Follow the steps below to get your environment ready and start training.

---

## 📁 Project Structure

```
Hackthon_Dataset/
├── ENV_SETUP/
│   ├── setup_env.bat     # Environment setup script for Windows
│   └── setup_env.sh      # Equivalent environment setup script for Mac/Linux
├── train.py              # Script to train the YOLOv8 model
├── predict.py            # Script to run predictions
└── ...                   # Other necessary files
```

---

## ⚙️ Setup Instructions

### 1. Install Anaconda

Make sure you have **Anaconda** installed. You can download it from [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution).

---

### 2. Set Up the Training Environment

**Windows:**

- Open an **Anaconda Prompt** window.
- Navigate to the `ENV_SETUP` folder inside the `Hackthon_Dataset`:

  ```bash
  cd Hackthon_Dataset/ENV_SETUP
  ```

- Run the setup script:

  ```bash
  setup_env.bat
  ```

**Mac/Linux:**

- Open a terminal.
- Navigate to the `ENV_SETUP` folder:

  ```bash
  cd Hackthon_Dataset/ENV_SETUP
  ```

- Run the equivalent setup script:

  ```bash
  bash setup_env.sh
  ```

This will create a Conda environment named **`EDU`** with all the dependencies required to run the training and prediction scripts.

---

### 3. Understand the Training Workflow

The project includes a guided walkthrough (Exercise 3) using Falcon that explains:

✅ YOLOv8 training pipeline structure  
✅ The purpose of each training script  
✅ How to evaluate and visualize results  

---

## 🏋️‍♂️ Training the YOLOv8 Model

Once the environment is ready and the dataset is in place:

1. Open an **Anaconda Prompt** (Windows) or **Terminal** (Mac/Linux).
2. Navigate to the folder containing the training and prediction scripts:

   ```bash
   cd Hackthon_Dataset
   ```

3. Activate the environment:

   ```bash
   conda activate EDU
   ```

4. Run the training command:

   ```bash
   python train.py
   ```

Training will begin, and logs along with checkpoints will be saved to the `runs/` directory.

---

## 📊 Visualizing Results

After training, use the provided visualization tools or scripts to:

✅ Inspect training metrics  
✅ Visualize detection outputs  
✅ Evaluate model performance  

---

## 📦 Dependencies

All required dependencies will be installed through the `setup_env.bat` (Windows) or `setup_env.sh` (Mac/Linux) script.  

If you encounter issues, you can manually install dependencies from the `environment.yml` (if provided) or using:

```bash
conda install <package_name>
```

---

## 🛰️ Notes

- Make sure your dataset is properly placed in the expected directories before training.
- If you're using a GPU, ensure appropriate CUDA versions and drivers are installed.
- For any issues, raise an issue in this repository.

---

## 🤝 Contributing

Pull requests and suggestions are welcome! Feel free to fork this repo and contribute.

---

## 📄 License

This project is licensed for educational and hackathon use only.

---

**Good luck with your model training! 🚀**


# 🎯 Coins Deduction System

This project is a Coins Deduction System tailored to identify Sri Lankan currency coins using YOLOv8. The system can accurately detect and categorize the following denominations:

💲 Rs.1 💲 Rs.2 💲 Rs.5 💲 Rs.10 💲 Rs.20 💲 Rs.100 💲 Rs.200 💲 Rs.500 💲 Rs.1000 💲 Rs.1500 💲 Rs.2000 💲 Rs.5000

## 📌 Key Features
- ⏱ **Real-time Detection**: The system can identify and classify coins in real-time, making it suitable for various automated applications.
- 💪 **Robust Performance**: Trained on a diverse set of coin images to ensure reliable detection across different lighting conditions and angles.
- 🔄 **Scalability**: The system can be easily adapted to detect other denominations or currencies by retraining the model with a new dataset.

## 🛠️ Technologies Used
- Python 🐍
- Google Colab ☁️
- YOLOv8 🎯
- OpenCV 🎥
- PyTorch 🔥

## 📂 Project Structure
```
Coins_Deduction_System/
│── train.py                 # Model training script
│── detect.py                # Object detection script
│── requirements.txt         # Dependencies
│── dataset/                 # Training dataset
│── extracted/               # Extracted training files
│── runs/                    # Training results
│── README.md                # Project documentation
```

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Coins_Deduction_System.git
cd Coins_Deduction_System
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Training Script
```bash
python train.py
```

### 4️⃣ Detect Coins
```bash
python detect.py
```

## 🎯 Usage
1. Mount Google Drive in Colab.
2. Upload the dataset and extract the files.
3. Train YOLOv8 with the dataset.
4. Deploy the trained model for real-time coin detection.

## 🔥 Demo
🚀 **Coming soon!**

## 🤝 Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## 📜 License
This project is licensed under the MIT License.

---
🌟 **Star this repository if you found it useful!** 🌟


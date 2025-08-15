# 🧭 Pendulum Balance DQN

![Pendulum Balance DQN Banner](Pendulum.png)

**A Deep Q-Network (DQN) agent trained to stabilize an inverted pendulum using OpenAI Gym's Pendulum-v1 environment.**  
*Explores reward shaping, action discretization, and performance criteria balancing stability and speed.*

---

## 🧩 Features

- 🎯 **Deep Q-Network Agent**: Learns to balance the pendulum in a continuous action space.  
- ⚖️ **Reward Shaping**: Custom reward functions to guide the agent's learning process.  
- 🧮 **Action Discretization**: Converts continuous actions into discrete choices for the DQN.  
- 📊 **Performance Metrics**: Evaluates agent performance based on stability, speed, and learning efficiency.  

---

## 📚 Dataset

- **Environment**: [OpenAI Gym's Pendulum-v1](https://www.gymlibrary.ml/environments/classic_control/pendulum/)  
  - **State Space**: Continuous (angle, angular velocity)  
  - **Action Space**: Continuous (torque applied to the pendulum)  

---

## 🏗 Model Architecture

- **Model Type**: Deep Q-Network (DQN)  
- **Input**: State vector (angle, angular velocity)  
- **Output**: Q-values for discrete actions (torque levels)  
- **Network Structure**: Multi-layer perceptron with ReLU activations  

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/4ndrrw/Pendulum-Balance-DQN.git
cd Pendulum-Balance-DQN

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🎥 Demo

![Pendulum Balance DQN Demo](dqn_pendulum_trained.gif)

*Watch the agent balance the pendulum.*

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?logo=visualstudiocode&logoColor=white)

---

## 🤝 Contributing

1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Commit your changes (`git commit -am 'Add new feature'`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Open a Pull Request.


---

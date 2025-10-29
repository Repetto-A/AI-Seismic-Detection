# Introduction
The project we developed aims to improve the detection of seismic events on celestial bodies using data collected by seismometers on the Moon and Mars. To tackle this challenge, we implemented an LSTM (Long Short-Term Memory) neural network model that analyzes seismic time series data to identify real earthquake signals embedded in background noise. The focus is on optimizing data transmission from landers on these bodies, so that only fragments containing useful information are transmitted to Earth, saving energy and communication resources.

# What does it do?
The system filters seismic data in real-time to differentiate relevant signals, such as earthquakes or crustal movements, from other non-informative noise. This local processing reduces the amount of data sent to Earth by focusing solely on moments when significant seismic events are detected. This improves energy efficiency and maximizes the amount of useful information transmitted by space missions.

# How does it work?
The system uses an LSTM model, which is capable of learning patterns in long temporal sequences, ideal for seismic data that can be buried under large volumes of noise. I trained this model with a dataset provided by NASA, containing real data collected by seismometers on the Moon (Apollo missions) and Mars (InSight). The model was designed to identify patterns that precede and follow a seismic event, allowing it to distinguish between background noise and a possible earthquake signal. Once a relevant signal is detected, it is labeled and prepared for transmission.

# What benefits does it offer?
This project provides several crucial benefits for space missions focused on planetary seismology:

- Energy savings: By transmitting only relevant data, the energy consumption required for communications from distant celestial bodies is significantly reduced.
- Increased scientific efficiency: By filtering out noise, scientists on Earth can focus on analyzing only the most relevant seismic events, optimizing their time and resources.
- Better planetary understanding: Accurate detection of seismic events on other planets and moons can reveal valuable information about internal structure, tectonic processes, and geological evolution.
- Application for future missions: This technology could be applied to future planetary missions where seismic data collection and transmission are a challenge, such as on Europa or Titan.


There is also the possibility of extrapolating the techniques implemented in this work to prediction models and early warning systems for seismic activity on Earth, significantly reducing humanitarian, economic, and ecological losses.

# What do we hope to achieve?
The ultimate goal is to contribute to the advancement of planetary scientific exploration by implementing an efficient system for detecting and transmitting seismic data. With this, we hope that space missions can maximize the scientific value of the data collected without the constraints of transmitting large volumes of information. Additionally, we aspire for this system to be applicable in future missions to other planets and moons, allowing scientists to study seismic activity on a variety of bodies in the solar system with greater accuracy and efficiency.

# Tools, coding languages, hardware, or software used:
- Programming languages: Python
- Machine learning libraries: TensorFlow, Keras (for the implementation of the LSTM model)
- Data processing libraries: NumPy, Pandas (for manipulation and analysis of seismic data)
- Data preprocessing: Use of tools to clean, normalize, and segment the data, transforming them into time series suitable for the model.
- Dataset: Real seismic data provided by NASA from the Apollo (Moon) and InSight (Mars) missions.
- Hardware: Computer with GPU for model training, combined with Google Colab to optimize processing time.
- Development environment: Google Colab, Jupyter Notebooks (for code development and testing).


By implementing AI and machine learning technology, this project not only addresses the immediate challenges of current missions but also opens new possibilities for future planetary seismology research.

# Use of Artificial Intelligence
Indeed, we used artificial intelligence tools to develop our solution. Specifically, we employed TensorFlow and Keras, two widely used libraries in machine learning and deep learning. These tools enabled us to develop, train, and evaluate a Long Short-Term Memory (LSTM) neural network model, suitable for analyzing the seismic time series data used in our project. Keras facilitated the construction of the LSTM model due to its intuitive and high-level interface, while TensorFlow provided a robust platform for executing the mathematical operations required for training and fine-tuning the model. Additionally, with these tools, we were able to optimize the detection of useful seismic signals buried in large volumes of noise, which helped reduce the amount of data that needs to be sent to Earth from the lander.

# Automated Lip Reading Using Deep Learning Techniques

## Overview
This project implements a novel approach to automated lip reading using advanced deep learning techniques in Python. The primary objective is to enhance accessibility for individuals with hearing impairments and improve performance in noisy environments where traditional audio-based speech recognition systems struggle.

### Project Lead
**Dr. L Mohana Sundari**  
Assistant Professor Senior Grade 1  
Department Of Software Systems

### Batch Members
- **Piyush Kumar** (21BCE3077)
- **Madhav** (21BCE3239)
- **Anas Khan** (21BCE3244)

## Objectives
- Utilize Conv3D for extracting spatiotemporal features, MaxPooling for downsampling, and LSTM for modeling sequential data to ensure high precision in word detection.
- Improve accessibility for individuals with hearing impairments by providing an alternative communication tool that relies on visual cues from lip movements.
- Develop a web-based application using the Streamlit framework for real-time demonstration and interaction with the lip reading model.

## Introduction
Lip reading, or speechreading, enables understanding speech by observing a speaker's lip movements. This technology is crucial for individuals with hearing impairments and is becoming increasingly relevant in our technology-driven world.

### Growing Demand
The need for lip reading technologies is rising due to the increasing prevalence of hearing loss and the demand for accessible communication methods.

### Advances in AI
Recent developments in deep learning have significantly improved the accuracy and performance of automated lip reading systems.

### Applications
Lip reading systems can be applied in various domains, including assistive technologies for the hearing impaired, security systems, and human-computer interaction.

## Literature Survey
A comprehensive review of existing lip reading systems reveals several limitations and gaps in current research:

| Study/Model | Summary | Limitations |
|--------------|---------|-------------|
| LipNet (Assael et al., 2016) | End-to-end deep learning model combining CNN and RNN for sentence-level lip reading. | Struggles with unseen speakers and variations in lip movements. |
| Shillingford et al. (2018) | Proposed a large-scale dataset and used 3D CNNs to capture spatiotemporal features, improving lip reading in noisy conditions. | Requires large datasets and is computationally expensive. |
| Martinez et al. (2020) | Applied transformer models to lip reading, demonstrating improvements in modeling long-term dependencies. | Transformers require large datasets and high computational power. |

### Gap Identification
Existing lip reading systems often struggle with accuracy in real-world scenarios, particularly in noisy environments. Key challenges include:
- Limited models focusing on visual-based techniques.
- Need for real-time, efficient models in dynamic environments.

## Proposed Methodology
The project employs a novel deep learning approach combining CNNs and RNNs to effectively extract features and model temporal dependencies in lip movements.

### Method Steps
1. **Data Acquisition**: Collect video sequences of speakers' lip movements.
2. **Preprocessing**: Normalize lip movements and enhance data quality.
3. **Model Training**: Train a CNN-RNN model on the preprocessed data.
4. **Evaluation**: Assess the model's performance on unseen data.

## System Architecture
![Block Diagram](link_to_your_block_diagram_image)

### Requirements
#### Hardware
- High-performance CPU and GPU
- Sufficient RAM for training and inference processes

#### Software
- Python with libraries like TensorFlow or PyTorch for deep learning

#### Data
- A large and diverse dataset of lip movements is essential for training the model.

## Design and Implementation
The project structure includes:
- **Folder Structure**: Code and interface elements, model definitions, training scripts, and checkpoints.
- **Model Building**: Implement Conv3D for feature extraction and LSTM for word prediction.
- **Web Application**: Develop a user-friendly interface using Streamlit for real-time predictions.

## Conclusion
This project aims to provide an innovative approach to automated lip reading, addressing existing challenges and enhancing the accuracy of lip recognition. 

### Future Work
- Explore advanced models for better accuracy and efficiency.
- Expand the system for different languages and applications beyond assistive technology.

### Impact
- **Enhanced Accessibility**: Provides crucial tools for individuals with hearing impairments.
- **Advancement in AI**: Demonstrates the application of advanced deep learning techniques in visual speech recognition.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
We would like to acknowledge Dr. L Mohana Sundari for her guidance and support throughout this project.

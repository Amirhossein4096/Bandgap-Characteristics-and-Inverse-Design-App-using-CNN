## Bandgap Characteristics and Inverse Design App using CNN

This repository contains a MATLAB application designed for predicting bandgap characteristics and ratios, as well as performing inverse design of elastic metamaterials using a trained Convolutional Neural Network (CNN). This tool integrates advanced machine learning techniques to optimize the design of elastic metamaterials for desired bandgap properties. Key features include:

- **Bandgap Characteristics Prediction**: Utilizes a trained CNN to accurately predict the bandgap characteristics of elastic metamaterials based on user-defined parameters.
- **Bandgap Ratio Prediction**: Provides predictions for the bandgap ratio derived from the defined characteristics using the trained neural network model.
- **Inverse Design**: Facilitates the design of metamaterials with specified bandgap ratio goals through a particle swarm optimization approach.
- **User-Friendly Interface**: A MATLAB-based graphical interface for enhanced usability and accessibility.

---

### Features

1. **Prediction Tab**:
   - Set target bandgap ratio and boundary ranges for the control parameters.
   - perform inverse design, utilizing particle swarm optimization and the trained CNN for minimal optimization.
   - Automatically update the 2D view of the elastic metamaterial unit cell within the app.

2. **Inverse Design Tab**:
   - Set boundary ranges for **e/a**, **d/a**, and **h/a** using range sliders.
   - Input the desired bandgap ratio.
   - Click "Compute" to perform inverse design with minimal optimization using a trained neural network and particle swarm optimization.

### Getting Started

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Amirhossein4096/Bandgap-Characteristics-and-Inverse-Design-App-using-CNN.git
    ```

3. **Run the Application**:
    - Unzip the zip file.
    - Navigate to the cloned repository directory.
    - Run the executable file: `Bandgap_Characteristic_ and_Inverse_Design_App_using_CNN.exe`.

### Usage

- **Prediction Tab**:
  - Use the sliders to set the values of the control points to define the unit cell geometry.
  - View predicted bandgap characteristics and ratios by clicking 'Compute,' along with 3D visualizations.

- **Inverse Design Tab**:
  - Set boundary ranges for control points.
  - Input the desired bandgap ratio.
  - Click "Compute" to start the inverse design process.

### License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Amirhossein4096/Bandgap-Characteristics-and-Inverse-Design-App-using-CNN/blob/main/LICENSE) file for details.

### Contact

For any questions or suggestions, please contact amir.farajollahi@ut.ac.ir.

---

### Short Description

A MATLAB app for predicting bandgap characteristics and ratios, and performing inverse design of elastic metamaterials using a trained CNN.

### Title

**Bandgap Characteristics and Inverse Design App using CNN**

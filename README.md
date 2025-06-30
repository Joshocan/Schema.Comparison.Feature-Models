# Schema/Model Interoperability Feature Model

This repository contains the feature models for various operations (Matching, Mapping and Alignment)  and ML/AI approaches related to model/schema comparison. 
It is designed to be used with **FeatureIDE Eclipse** for managing and visualizing feature models.

## Table of Contents

- [Installation](#installation)
  - [Installing FeatureIDE Eclipse](#installing-featureide-eclipse)
- [Importing the Repository](#importing-the-repository)
- [Using the Feature Model](#using-the-feature-model)
- [Contributors](#contributors)

## Installation

### Installing FeatureIDE Eclipse

**FeatureIDE** is an Eclipse plugin for feature-oriented software development. To use the feature models in this repository, you will need to install FeatureIDE on your Eclipse IDE.

Follow these steps to install FeatureIDE Eclipse:

1. **Open Eclipse IDE**.
2. **Install FeatureIDE**:
   - Go to `Help` > `Eclipse Marketplace`.
   - In the `Eclipse Marketplace` dialog, search for **FeatureIDE**.
   - Click `Go` and then click `Install` next to the FeatureIDE entry.
   - Follow the installation instructions and restart Eclipse when prompted.
3. After installing **FeatureIDE**, make sure it is available under the `FeatureIDE` perspective. You can switch to this perspective via `Window` > `Perspective` > `Open Perspective` > `Other...` and select **FeatureIDE**.

For more detailed installation instructions, please refer to the official FeatureIDE documentation:
- [FeatureIDE Installation Guide](https://featureide.github.io/)

### Importing the Repository

Once **FeatureIDE** is installed and set up in your Eclipse environment, follow these steps to import this repository:

1. **Clone the Repository**:
   - You can clone this repository using your preferred Git client or from within Eclipse.
   - To clone directly from Eclipse, go to `File` > `Import` > `Git` > `Projects from Git`.
   - Enter the repository URL and follow the prompts to clone it into your workspace.

2. **Import the Project into Eclipse**:
   - After cloning, go to `File` > `Import` > `General` > `Existing Projects into Workspace`.
   - Select the repository folder and click `Finish`.

3. **Open the Feature Model**:
   - After importing the project, navigate to the `src` folder in the Eclipse project explorer.
   - You should be able to see the feature model files with `.xml` extensions. Right-click on the file you want to work with and open it in **FeatureIDE**.

## Using the Feature Model

Once you've successfully imported the repository, you can start using the feature model:

1. **Create a New Feature Model**:
   - Open **FeatureIDE** perspective (from the menu `Window` > `Perspective` > `Open Perspective` > `FeatureIDE`).
   - Create a new feature model using the `New` menu, and select **Feature Model**.
   - Import the desired `.xml` feature model file into your project.

2. **Manipulate the Feature Model**:
   - You can now manipulate the features in the model using the **FeatureIDE** tools, such as the **Feature Tree** view, **Feature Diagram**, and **Constraints**.
   - You can also validate, analyze, and work with the feature model for tasks like configuration, comparison, and integration.

For more detailed usage of **FeatureIDE**, refer to the official documentation:
- [FeatureIDE User Guide](https://featureide.github.io/)

## Contributors

- **Joshua Tetteh  Ocansey** (Lead Developer) - jtoc@hvl.no


Please feel free to open issues or submit pull requests with bug fixes, feature requests, or improvements.

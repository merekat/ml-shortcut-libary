![Header Image](images/header.png)

# ML Shortcut Libary
A Visual Studio Code shortcut libary designed to simplify and accelerate machine learning development in python.

#### Why Use ML Shortcuts?
ML Shortcuts helps streamline your machine learning workflow by providing quick access to commonly used code snippets and tools, making your development process more efficient and productive. 

#### Features
  * Snippets for common ML libraries (Pandas, Numpy, TensorFlow, scikit-learn etc.)
  * Quick data visualization tools
  * Code completion for ML tasks
  * Customizable shortcuts for frequent operations
  * Inline model performance metrics

## Installation

Copy and paste the content of python.json to the user snippet JSON file of Visual Code Studio. The file can be opened by File > Preferences > Configure User Snippets > python.json.

![Header Image](images/installation.gif)

To use the snippets of the libary just start typing the prefixes of the snippets and accept them via autocomplete. Sometimes placeholders need to be replaced after the code snippet appeared. You can jump from one placeholder to another via tab. All prefixes and codes can be customized in the user snippet JSON file. Placeholders are written as `${1:text}` with the number representing the order in which the user accesses the placeholder. 

![Header Image](images/implementation.gif)
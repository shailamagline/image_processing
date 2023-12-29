# Image Processing Project

## Overview

This GitHub repository contains a Python-based image processing project focused on retinal image enhancement. The project utilizes various techniques, including fuzzy filtering for noise removal, non-linear diffusion filtering for artifact removal, and speckle filtering for contrast enhancement using Euclidean distance measures.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Libraries Used](#libraries-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The project is centered around improving the quality of retinal images through a series of image processing steps. The primary techniques employed include:

1. **Fuzzy Filtering:** Applied for noise removal.
2. **Non-linear Diffusion Filtering:** Employed for artifact removal.
3. **Speckle Filtering:** Used for contrast enhancement based on Euclidean distance measures.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/image-processing-project.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the project directory:

    ```bash
    cd image-processing-project
    ```

2. Run the main script:

    ```bash
    python main.py
    ```

3. Follow the on-screen instructions to input the retinal image and observe the enhancements.

## Libraries Used

The project relies on the following Python libraries:

- **cv2 (OpenCV):** Used for image processing tasks.
- **matplotlib:** Employed for plotting and visualization.
- **skimage:** Utilized for various image processing functions.
- **numpy:** Used for numerical operations.

Make sure to install these libraries before running the project (refer to the [Installation](#installation) section).

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Description of changes"`.
4. Push the branch to your fork: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to the terms of the license.

# LUT Convertor  ♥️ Codespace Jupyter Notebooks

_____________________________
< LUT FILE CONVERTOR        >
-----------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
_____________________________
_____________________________

LUT Convertor is a Python tool for extracting and applying Look-Up Tables (LUTs) for color grading, contrast, and brightness adjustments on images. This tool leverages the power of numpy and PIL to process images and transform their appearance based on reference images.

## Features

- Extract color grading LUT from a reference image.
- Extract contrast and brightness LUTs.
- Apply LUTs to input images.
- Save transformed images.

## Installation

1. Clone this repository:
    ```sh
    cd lut-convertor
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Place your reference image and input image in the `data/images` directory.

2. Run the script:
    ```sh
    python lut_convertor.py
    ```

3. The transformed images will be saved in the 

output

 directory.

## Example


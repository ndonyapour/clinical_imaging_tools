# Medical Imaging Tools

A Python toolkit for general medical imaging tasks, focusing on NIFTI file processing and visualization.

## Features

- Load and visualize 3D medical images in NIFTI format.
- View anatomical slices in different orientations (Axial, Sagittal, Coronal).
- Work with medical image coordinate systems and orientations.
- Analyze affine transformations and voxel-to-world mappings.

## Installation

### Setup

1. **Clone the Repository**

   ```bash
   git clone git@github.com:ndonyapour/clinical-imaging-tools.git
   cd clinical-imaging-tools
   ```

2. **Install and Set Up Using UV**

   ```bash
   # Install uv
   pip install uv

   # Create virtual environment
   uv venv

   # Activate virtual environment
   source .venv/bin/activate  # On Unix/macOS
   # or
   .venv\Scripts\activate     # On Windows

   # Install dependencies
   uv sync
   ```

3. **Install `dcm2niix`**

   You need to install `dcm2niix` separately, as it can't be installed using `uv`. Follow the instructions [here](https://github.com/rordenlab/dcm2niix?tab=readme-ov-file).

## Usage

### Basic Usage

Open the notebooks in the examples folder and run the cells.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# FragMiner (CLI version)
    A Python utility tool for identification and visualization of SMILES fragments present in molecular structures using RDKit.

# Version:
    0.5.0 (CLI)

# Introduction to FragMiner
    FragMiner is a versatile Python utility designed for the identification and visualization of SMILES fragments present in molecular structures. By leveraging the RDKit library, it provides an efficient way to process molecular data, highlight specific substructures, and save the results in various image formats (e.g., PNG, SVG, PDF, EPS). Whether you're working with small molecule databases or performing fragment-based analyses, FragMiner streamlines the process of fragment identification and visualization.

# Features at a Glance
    - Flexible File Loading: Supports loading molecular data from .sdf files.
    - Fragment Identification: Automatically identifies fragments in molecules based on provided SMILES.
    - Customizable Highlighting: Allows customizable highlight colors for fragments.
    - Parallel Processing: Leverages multiple CPU cores for faster processing using the multiprocessing module.
    - Multiple Output Formats: Save visualizations in PNG, SVG, PDF, or EPS formats.
    - High-Quality Visualization: Generates high-quality 2D molecular images with highlighted fragments.
    - Prerequisites
    
FragMiner is available as a precompiled executable for both Linux and Windows. No manual dependency installation is required.

# Installation and usage
    - Windows
              1. Download FragMiner.exe from the release page.
              2. Place the executable in your desired directory.
              3. Open a command prompt (cmd) and navigate to the directory where FragMiner.exe is located.
              4. Run FragMiner.exe --help to view available options.

# Example Usage
    - Windows: FragMiner.exe --input molecules.sdf --fragments fragments.txt --outdir output_dir --format png --width 600 --height 600 --cpu 4 --color red

    - Linux: ./FragMiner --input molecules.sdf --fragments fragments.txt --outdir output_dir --format png --width 600 --height 600 --cpu 4 --color red

# Command-line Options
    --input <file>: Input .sdf file containing molecular structures.
    --fragments <file>: Text file containing SMILES of fragments (one per line).
    --outdir <dir>: Directory to save output images (default: ./output).
    --format <format>: Output image format (choices: png, svg, pdf, eps).
    --width <int>: Image width in pixels (default: 500).
    --height <int>: Image height in pixels (default: 500).
    --cpu <int>: Number of CPU cores to use (default: all available cores).
    --color <color>: Highlight color for the fragments (e.g., red or 1,0,0 for RGB).

  For detailed usage, use:

    - Windows: FragMiner.exe -h/--help
    - Linux: ./FragMiner -h/--help

# About the Author
    This project was created by SUVANKAR BANERJEE. You can explore the project further and contribute via GitHub: FragMiner on GitHub

# License
    FragMiner is released under the MIT License, fostering open and collaborative software development.

# Acknowledgments
    A heartfelt thanks to the RDKit community and all contributors for their invaluable resources and support. Your contributions continue to drive innovation in computational chemistry!

# Contributing
    Contributions are welcome! To contribute to the development of FragMiner, please follow these steps:
      1. Fork the repository.
      2. Create a new branch (git checkout -b feature-name).
      3. Commit your changes (git commit -am 'Add feature').
      4. Push to your fork (git push origin feature-name).
      5. Open a Pull Request.


<a id="readme-top"></a>


<br />
<div align="center">
  
  <a href="https://github.com/Siamak-salimy/HMNexus">
    <img src="https://img.shields.io/badge/GitHub_Repo-Siamak--salimy/HMNexus-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository"/>
  </a>
  <br/><br/>

  <a href="https://github.com/Siamak-salimy/HMNexus">
    <img src="src/images/icon.ico" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">HMNexus</h3>

  <p align="center">
    A high-speed, code-free GUI for downloading TCGA data.
    <br />
    <a href="https://siamak-salimy.github.io/HMNexus/"><strong>Explore the Website »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Siamak-salimy/HMNexus/releases">View Repositoty</a>
    ·
    <a href="https://github.com/Siamak-salimy/HMNexus/issues/new?assignees=&labels=bug&template=bug_report.md&title=">Report Bug</a>
    ·
    <a href="https://github.com/Siamak-salimy/HMNexus/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=">Request Feature</a>
  </p>
</div>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#data-source">Data Source</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#development-team">Development Team</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## About The Project

[![HMNexus Screenshot][product-screenshot]](https://siamak-salimy.github.io/HMNexus/)

**HMNexus** is a cross-platform desktop application designed to eliminate the technical barriers in accessing The Cancer Genome Atlas (TCGA) data. Traditional methods require command-line expertise and scripting, making them inaccessible for many biologists, clinicians, and medical researchers. HMNexus solves this problem by providing a fully graphical, intuitive, and powerful tool that requires zero coding.

Here's why HMNexus is a game-changer:
* **Accessibility:** Empowers researchers without a programming background to independently download and manage massive genomic datasets.
* **Efficiency:** Accelerates the data acquisition phase of research with high-speed, parallel downloads, saving valuable time.
* **Simplicity:** Transforms a complex workflow into a simple, three-step process: select, import, and download.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project was built using Python and the native Tkinter library, ensuring it is lightweight and cross-platform.

* [![Python][Python.org]][Python-url]
* [![Tkinter][Tkinter-shield]][Tkinter-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Data Source

All data is sourced from the official NCI portals. You can download your data manifest from the **Genomic Data Commons (GDC) Portal**, and then use our app to download the files.

*   [![The Cancer Genome Atlas (TCGA) Program][TCGA-shield]][TCGA-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Getting Started

Follow these instructions to get a copy of HMNexus up and running on your local machine.

### Prerequisites

To run the application from the source code, you will need Python 3.9+ and pip.

* **Python & pip**
  You can download Python from the [official website](https://www.python.org/downloads/). Pip comes bundled with Python 3.9+.

### Installation

You can either download the standalone executable (recommended for most users) or run from the source code.

1. **Standalone Executable (Recommended)**
   - Go to the **[Releases Page](https://github.com/Siamak-salimy/HMNexus/releases)**.
   - Download the executable file for your operating system (`.exe` for Windows, `.dmg` for macOS, or the Linux binary).
   - Run the application. No further installation is needed!

2. **From Source Code**
   - Clone the repo
     ```sh
     git clone https://github.com/Siamak-salimy/HMNexus.git
     ```
   - Navigate to the project directory
     ```sh
     cd HMNexus
     ```
   - Install required packages
     ```sh
     pip install -r requirements.txt
     ```
   - Run the application
     ```sh
     python main.py
     ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Usage

HMNexus is designed to be as intuitive as possible. The main workflow consists of:
1.  **Filtering Data**: Use the dropdown menus to select the cancer type and data category you are interested in.
2.  **Importing a Manifest**: Click "Import Manifest" to load a manifest file downloaded from the GDC Data Portal.
3.  **Downloading**: Click "Start Download" to begin the high-speed download process. Your files will be automatically organized into structured directories.

For more detailed examples and tutorials, please refer to the **[Project Website](https://siamak-salimy.github.io/HMNexus/)**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Roadmap

- [x] Core GUI for data filtering and download
- [x] Concurrent, high-speed download engine
- [x] MD5 checksum validation
- [x] Windows Standalone Executable
- [ ] Support for macOS and Linux executables
- [ ] Integration with GDC API for direct data cart management

See the [open issues](https://github.com/Siamak-salimy/HMNexus/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please [fork the repo](https://github.com/Siamak-salimy/HMNexus/fork) and create a pull request. You can also simply [open an issue](https://github.com/Siamak-salimy/HMNexus/issues/new/choose) with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👨‍💻 Development Team

- Siamak Salimy (Team Lead)
- Amirmohammad Asgari
- Mohammadreza Shahbazi
- Abolfazl Ghasemi
- Mahan Mirzade

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📜 Citation

If you use HMNexus in your academic research, please cite our paper:

> Salimy S., Asgari A., Shahbazi M., Ghasemi A., & Mirzade M. (2025). HMNexus: A Tkinter GUI Platform for High-Speed, Code-Free TCGA Data Download. *BMC Bioinformatics*.

---

## 📄 License

© 2025 HMNexus Project

## Contact

Siamak Salimy - [siamak.salimy@gmail.com](mailto:siamak.salimy@gmail.com)

Project Link: [https://github.com/Siamak-salimy/HMNexus](https://github.com/Siamak-salimy/HMNexus)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[product-screenshot]: src/images/project%20snapshot.png
[Python.org]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://python.org
[Tkinter-shield]: https://img.shields.io/badge/Tkinter-FFD43B?style=for-the-badge&logo=python&logoColor=blue
[Tkinter-url]: https://docs.python.org/3/library/tkinter.html
[TCGA-shield]: https://img.shields.io/badge/The_Cancer_Genome_Atlas_(TCGA)-0A539C?style=flat&logo=unrealengine&logoColor=white
[TCGA-url]: https://www.cancer.gov/tcga




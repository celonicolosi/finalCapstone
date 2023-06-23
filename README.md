# Watch Next

Watch Next is a convenient tool that enhances the user experience in video recommendation. It provides users with personalized recommendations for their next content to watch based on their preferences.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)

## Project Overview

Watch Next is a personalized recommendation tool designed to enhance the user experience in video streaming platforms. By utilizing advanced algorithms and machine learning techniques, it analyzes user preferences to generate tailored recommendations for their next content to watch.

## Installation

### Requirements

- Python 3. (If you don't have Python 3 installed, you can download it from the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/))
- Additional dependencies:
    - spaCy
    - en_core_web_md language model

### Steps

1. Clone this repository to your local machine.

2. Install the required dependencies. Open your terminal and run the following commands:

**pip**

```bash
pip install -U pip setuptools wheel
python -m spacy download en_core_web_md
```

**conda**

Alternatively, you can install spaCy using conda-forge:
```bash
conda install -c conda-forge spacy
python -m spacy download en_core_web_md
```

Please note that if your machine does not recognize the python command, you may need to use python3 instead, especially on macOS.

3. Once the dependencies are installed, navigate to the project directory.


## Usage

1. Open the watch_next.py file.

2. Inside the script, you will find a variable named `my_movie` set to the description of a sample movie (Planet Hulk). You can modify this variable and replace it with the description of the last movie you enjoyed watching.

3. In the `movies.txt` file, you will find a list of movies to compare and analyze for the best recommendation. You can modify this list by replacing the movie descriptions with your own collection of movies or desired movies to watch next. Each movie should be formatted as follows, with one movie per line:

    Movie A: The world at an end, a dying mother sends her young son on a quest to find the place that grants wishes.
    
    Movie B: After the death of Superman, several new people present themselves as possible successors.

4. Save the changes and run the `watch_next.py` script using Python:

```bash
python watch_next.py
```

5. The script will analyze the movie descriptions and provide a recommendation for the next content to watch based on your preferences.


## Troubleshooting

If you encounter any issues during the installation or usage of the Watch Next tool, consider the following solutions:

- Ensure that you have installed all the required dependencies correctly and that they are up to date.
- Double-check the formatting of the movie descriptions in the `movies.txt` file to ensure they follow the specified format.
- If you encounter any errors related to language models, verify that the `en_core_web_md` model has been successfully downloaded.
- If problems persist, feel free to open an issue in the project's GitHub repository for further assistance.

We hope you enjoy using Watch Next for personalized video recommendations!
# RelaxingGO - Personalized Travel Assistant

## Overview
RelaxingGO is a personalized travel assistant powered by a large language model (LLM) on Streamlit. It helps users evaluate whether a tour package meets their needs based on their preferences such as destination, travel dates, budget, activities, and dietary restrictions. This tool allows users to easily assess tour packages and provides tailored recommendations based on their input.

## Features
- **Upload Tour Package (PDF)**: Extracts text from the uploaded PDF to analyze the tour details.
- **Personal Preferences**: Input your preferred destination, travel dates, budget, activities, and any dietary restrictions.
- **Generate Recommendations**: Based on the input, the app provides an evaluation of the tour package.
- **Rating System**: Ratings are provided across five key sections: Attraction, Food, Season, Budget, and Logistics.
- **Final Report**: Downloadable final report in DOC format for record-keeping.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Installation
```bash
# 1. Clone the repository to your local machine:
git clone https://github.com/PEY0413/RelaxingGO.git

# 2. Navigate to the project directory:
cd RelaxingGO

# 3. Install the required dependencies:
pip install -r requirements.txt

# 4. Run the Streamlit application:
streamlit run app.py

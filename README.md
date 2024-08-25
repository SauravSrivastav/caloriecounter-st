# Calorie Counter 🍽️🔢

**Calorie Counter** is an innovative AI-powered application that analyzes food images to provide detailed nutritional insights. Using advanced image recognition and Google's Generative AI, it offers users a quick and easy way to understand the caloric content and health impacts of their meals.

## Overview

Calorie Counter is designed for health-conscious individuals, dietitians, and anyone interested in understanding their food better. By simply uploading a photo of their meal, users receive comprehensive information about calories, ingredients, and potential health effects, making informed dietary choices easier than ever.

## Features

- 📸 **Image Upload**: Easily upload food photos for instant analysis.
- 🤖 **AI-Powered Recognition**: Utilizes Google's Generative AI for accurate food identification.
- 📊 **Detailed Calorie Breakdown**: Get specific calorie information for each food item.
- 🥗 **Health Insights**: Learn about healthy and potentially harmful ingredients in your meal.
- 💡 **Dietary Context**: Understand how your meal fits into your daily calorie needs.
- 📱 **User-Friendly Interface**: Built with Streamlit for a smooth, interactive experience.

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)
- Google Generative AI API key

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/SauravSrivastav/caloriecounter-st.git
    cd caloriecounter-st
    ```

2. **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Create a `.env` file in the root directory and add your Google Generative AI API key:**
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

5. **Ensure you have a `requirements.txt` file in your project directory with the following contents:**
    ```
    streamlit
    pillow
    google-generativeai
    python-dotenv
    ```

6. **Run the application:**
    ```bash
    streamlit run app.py
    ```

7. **Access the app:**
    - Open your web browser and go to `http://localhost:8501`

## Usage

1. Upload an image of your food using the file uploader.
2. Click the "Tell me about this food" button.
3. View the detailed analysis, including:
   - Dish identification
   - Calorie breakdown per food item
   - Healthy and potentially harmful ingredients
   - Total calorie estimate and daily intake percentage

## Screenshots

[Add a screenshot of your application here]

## Contributing

Contributions are welcome! If you'd like to improve Calorie Counter, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please feel free to reach out:

- Email: [Sauravsrivastav2205@gmail.com](mailto:Sauravsrivastav2205@gmail.com)
- LinkedIn: [in/sauravsrivastav2205](https://www.linkedin.com/in/sauravsrivastav2205)
- GitHub: [https://github.com/SauravSrivastav](https://github.com/SauravSrivastav)

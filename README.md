# AzureOpenAI
Here’s a step-by-step README file for your project, including instructions on cloning, installing dependencies, and running the script:

---

# Azure OpenAI DALL-E 3 Image Generator

This project uses Azure OpenAI's DALL-E 3 model to generate images based on a given prompt. The generated images are saved locally and displayed using Python.

## Prerequisites
- Python 3.12 or later installed on your system.
- Azure OpenAI API Key and Endpoint.

---

## Getting Started

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/Muhammad-Muzammil-Shah/AzureOpenAI.git
```

### 2. Set Up a Virtual Environment (Optional but Recommended)
Create and activate a virtual environment:
```bash
python -m venv venv
```
- On Windows:
  ```bash
  .\venv\Scripts\activate
  ```

### 3. Install Dependencies
Install the required Python packages:
```bash
pip install -r requirements.txt
```

---

## Configuration

### 4. Add Azure OpenAI Credentials
Update the script with your Azure OpenAI API Key and Endpoint:
- Replace `<API Key>` with your Azure OpenAI API key.
- Replace `<API Endpoint>` with your Azure OpenAI endpoint URL.

---

## Running the Script

### 5. Execute the Script
Run the Python script to generate an image:
```bash
python DALL-E-3.py
```

The script will:
1. Generate an image based on the provided prompt.
2. Save the image in the `images` directory (created automatically if it doesn’t exist).
3. Open the image in your default image viewer.

---

## Notes

- Ensure your Azure subscription allows access to DALL-E 3.
- If you encounter errors, check for missing dependencies or verify the API credentials.

---

## Troubleshooting

### Common Errors
1. **ModuleNotFoundError**: Ensure all dependencies are installed using `pip install -r requirements.txt`.
2. **API Access Issues**: Verify your API Key and Endpoint.

Feel free to modify the code and experiment with different prompts. Happy coding!




# Welcome to Local LLM API for Text Summaries

This documentation guides you in setting up your environment and testing the LLM model with web scraping summaries.

## 1. Conda Environment Setup

Create a Conda environment using the provided `conda_env.yaml` file:

```bash
conda env create -f conda_env.yaml
conda activate your_environment_name  # Replace with the name specified in the YAML file
```

## 2. Install LMStudio and Download LLM Model

### Step 1: Install LMStudio

1. **Download LMStudio**: Visit the [LMStudio website](https://lmstudio.ai/) and download the appropriate version for your OS.
  
2. **Installation Instructions**:
   - **Windows**: Run the `.exe` installer.
   - **macOS**: Open the `.dmg` file and drag LMStudio to Applications.
   - **Linux**: Extract the `.tar.gz` file and follow the instructions.

### Step 2: Download an LLM Model

1. **Launch LMStudio**.

2. **Navigate to Discovery**: Browse available models in the **Discovery** section.

3. **Download a Model**: Select and download your desired LLM model.

### Step 3: Load the Model and Start the Server

1. **Go to Developer**: After downloading, navigate to the **Developer** section.

2. **Load the Model**: Follow instructions to load your model. exmaple : llama 

3. **Start the Server**: 

## 3. Testing the Model with Web Scraping Summaries

Use the model to summarize content from various sources:

### 3.1 Storybook Summaries

Scrape and summarize details from storybooks.

### 3.2 Research Paper Summaries

Gather and summarize key findings from research papers.

### 3.3 News Site Summaries

Collect and summarize headlines from news sites.

## 4. System and User Prompts

To optimize the model's performance for summarizing shopping offers, use the following prompts:

- **System Prompt**:  
  `system_prompt = "You are an assistant that analyzes website content for summarization. Focus on positive offers and present the information in Markdown format."`

- **User Prompt**:  
  `user_prompt = "Please provide a summary of today’s shopping offers categorized by topics like Electronics, Clothing, Home Goods, and Seasonal Discounts."`

---

## Conclusion

This guide helps you get started with LLM models and web scraping for summarization. Enjoy exploring and testing your model!

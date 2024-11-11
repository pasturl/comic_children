# Children Comic Generator

An interactive Streamlit application that generates educational comic books. The app uses Claude AI for story generation and Stable Diffusion for creating comic panels.

## Features

- Generate educational story options based on user-provided themes
- Create comic panels with AI-generated illustrations
- Incorporate personal photos into the story
- Built on Montessori educational principles

## Setup

1. Clone the repository:
```bash
git clone https://github.com/pasturl/comic_children.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.streamlit/secrets.toml` file with your API keys:
```toml
ANTHROPIC_API_KEY = "your-anthropic-api-key"
REPLICATE_API_KEY = "your-replicate-api-key"
```

4. Run the application:
```bash
streamlit run app.py
```

## Usage

1. Enter an educational theme
2. Upload a photo of the child
3. Generate story options
4. Select your preferred story
5. Generate comic panels

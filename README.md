<a href="https://cookbook.openai.com" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/images/openai-cookbook-white.png" style="max-width: 100%; width: 400px; margin-bottom: 20px">
    <img alt="OpenAI Cookbook Logo" src="/images/openai-cookbook.png" width="400px">
  </picture>
</a>

<h3></h3>
 
> ✨ Navigate at [cookbook.openai.com](https://cookbook.openai.com)

Example code and guides for accomplishing common tasks with the [OpenAI API](https://platform.openai.com/docs/introduction). To run these examples, you'll need an OpenAI account and associated API key ([create a free account here](https://platform.openai.com/signup)). Set an environment variable called `OPENAI_API_KEY` with your API key. Alternatively, in most IDEs such as Visual Studio Code, you can create an `.env` file at the root of your repo containing `OPENAI_API_KEY=<your API key>`, which will be picked up by the notebooks.

Most code examples are written in Python, though the concepts can be applied in any language.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Git
- An OpenAI API key ([create a free account here](https://platform.openai.com/signup))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/openai/openai-cookbook.git
   cd openai-cookbook
   ```

2. **Set up a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   
   Most examples require the OpenAI Python package. Install it with:
   ```bash
   pip install openai jupyter
   ```
   
   Some examples have additional dependencies listed in a `requirements.txt` file. When present, install them with:
   ```bash
   cd examples/<example-directory>
   pip install -r requirements.txt
   ```
   
   If an example doesn't have a `requirements.txt`, check the imports at the top of the notebook and install packages as needed (e.g., `pip install pandas matplotlib`).

4. **Configure your OpenAI API key**
   
   Set your API key as an environment variable:
   ```bash
   export OPENAI_API_KEY='your-api-key-here'  # On Windows: set OPENAI_API_KEY=your-api-key-here
   ```
   
   Or create a `.env` file in the root directory:
   ```
   OPENAI_API_KEY=your-api-key-here
   ```

5. **Run Jupyter notebooks**
   
   If working with notebook examples, install Jupyter:
   ```bash
   pip install jupyter
   jupyter notebook  # or: jupyter lab
   ```

For other useful tools, guides and courses, check out these [related resources from around the web](https://cookbook.openai.com/related_resources).

## License

MIT License

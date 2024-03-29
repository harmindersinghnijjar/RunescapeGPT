# RunescapeGPT: The Premier Open-Source Python Bot for GPT-Driven Code Generation in Runescape

<img src="https://i.imgur.com/dza1fyo.png">

RunescapeGPT constitutes a sophisticated artificial intelligence system, purpose-built to facilitate the authoring of streamlined and precise Java code pertinent to DreamBot scripts for Old School RuneScape (OSRS). By systematically assimilating contemporary discourse and exemplary code from the DreamBot forums, RunescapeGPT maintains an up-to-date repository of best practices and optimal strategies for OSRS bot script engineering.

## Capabilities

- **Interactive AI Dialogue System**: Interface with RunescapeGPT through intuitive natural language for comprehensive discussions pertaining to DreamBot scripting requisites.
- **Automated Code Synthesis**: Produce optimally structured Java code segments for DreamBot, characterized by their clarity and readiness for deployment.
- **Dynamic Learning Framework**: Regularly augmented with the most recent contributions from the DreamBot forums to refine the AI's code suggestion proficiency.
- **Targeted OSRS Adaptation**: Architectured to align with the intricate mechanics and attributes of OSRS, ensuring the generation of scripts that are exceptionally pertinent to the game's environment.


## How It Works

RunescapeGPT employs a bespoke model, refined on the basis of OpenAI's GPT-3.5-turbo, to comprehend and formulate Java code. This process involves parsing through DreamBot forum discussions to construct a robust internal knowledge base, which in turn informs the AI's generation of pertinent responses and Java code excerpts.

### Code Generation

Engage with the RunescapeGPT via its dialogic interface to initiate code generation. Articulate the specific functionality you require, and RunescapeGPT will deliver a Java code fragment, crafted for straightforward integration with your DreamBot script.

### Training

The training regimen of RunescapeGPT encompasses regular updates from new DreamBot forum content, thereby ensuring the AI's repository of information remains abreast of the prevailing OSRS bot scripting trends and methodologies.

### Installation CLI

```bash
# Navigate to the directory containing your Dockerfile and other app files
cd "C:\Users\Harminder Nijjar\Desktop\blog\kb-blog-portfolio-mkdocs-master\scripts\RAG\RunescapeGPT_v1.0.0"

# Build your Docker image
docker build -t runescape-gpt-app .

# If a container with the same name is already running or exists, remove it
docker rm -f runescape-gpt-container

# Run your new Docker container
docker run -it -p 8000:5000 --name runescape-gpt-container -e OPENAI_API_KEY=your_openai_api_key runescape-gpt-app

```

### Installation Flet UI
```bash
# Navigate to the directory containing your Dockerfile and other app files
cd "C:\Users\Harminder Nijjar\Desktop\blog\kb-blog-portfolio-mkdocs-master\scripts\RAG\RunescapeGPT_v1.0.0"

# Build your Docker image
docker build -t runescape-gpt-app .

# If a container with the same name is already running or exists, remove it
docker rm -f runescape-gpt-container

# Run your new Docker container and execute ui.py
docker run -it -p 8000:5000 --name runescape-gpt-container -e OPENAI_API_KEY=your_openai_api_key runescape-gpt-app python ui.py
```


This command initiates an interactive terminal session inside the container, where RunescapeGPT operates.


## License
This project is licensed under the MIT License.

## Acknowledgments
- DreamBot Community for their invaluable discussions and code snippets.<br>
- OpenAI for providing the GPT-3.5-turbo API.<br>

## Disclaimer
RunescapeGPT is intended for educational purposes and to facilitate the learning process of Java coding for DreamBot scripts. Botting in Old School RuneScape (OSRS) is against the Terms of Service of the game and can lead to account bans. The creators of RunescapeGPT do not condone the use of bots in violation of game rules.

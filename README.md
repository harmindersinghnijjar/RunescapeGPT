# RunescapeGPT: The Premier Open-Source Python Bot for GPT-Driven Code Generation in Runescape

![cmd_sRtfZKZ68Y](https://github.com/harmindersinghnijjar/RunescapeGPT/assets/110620707/89713e9a-274c-4413-8896-ec52ca0216a5)

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

### Installation

### Building the Docker Image

To containerize RunescapeGPT, construct the Docker image using the provided Dockerfile:

```bash
docker build -t runescapegpt .
```

### Running the Application as a Docker Container

Launch RunescapeGPT within a Docker container by executing:

```bash
docker run -it -p 8000:5000 --name runescape-gpt-container -e OPENAI_API_KEY=YOURAPIKEYHERE runescape-gpt-app
```

This command initiates an interactive terminal session inside the container, where RunescapeGPT operates.


## License
This project is licensed under the MIT License.

## Acknowledgments
- DreamBot Community for their invaluable discussions and code snippets.<br>
- OpenAI for providing the GPT-3.5-turbo API.<br>

## Disclaimer
RunescapeGPT is intended for educational purposes and to facilitate the learning process of Java coding for DreamBot scripts. Botting in Old School RuneScape (OSRS) is against the Terms of Service of the game and can lead to account bans. The creators of RunescapeGPT do not condone the use of bots in violation of game rules.

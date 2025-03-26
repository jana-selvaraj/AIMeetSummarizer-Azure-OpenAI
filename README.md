# AIMeetSummarizer: AI-Powered Meeting Transcript Summarizer with Azure OpenAI

AIMeetSummarizer is an AI-driven tool designed to streamline the summarization of office meeting transcripts. Whether your transcripts are from Microsoft Teams, Skype, or other platforms, AIMeetSummarizer efficiently processes .docx and .txt files, segments them into manageable chunks, and delivers clear, comprehensive summaries using Azure OpenAI.

## Key Features:

**Versatile Format Support:** Compatible with .docx, .doc, .md and .txt files.<br>

**AI-Driven Summarization:** Utilizes Azure OpenAI for precise and context-aware summaries. <br>

**Smart Chunking:** Divides lengthy transcripts into smaller, manageable sections for improved processing. <br>

**Flexible Prompts:** Supports JSON-based prompts to customize the summarization process. <br>

# Installation

1. Clone the repository:
```
 git clone https://github.com/jana-selvaraj/AIMeetSummarizer-Azure-OpenAI.git
```

2. Install dependencies:
```   
pip install -r requirements.txt
```
3. Set up your .env file with the following variables
```
AZURE_OPENAI_API_KEY=your_api_key
AZURE_OPENAI_ENDPOINT=your_endpoint
AZURE_OPENAI_DEPLOYMENT_NAME=your_deployment_name
FILE_PATH=path_to_your_transcript_file
```
# Usage
1. Place your transcript file in the project directory.
2. Update the DOC_PATH in the .env file.
3. Run the script
```
python MeetSummarizer.py
```
4. Check the <tanscript_filename>_Summary.txt file for the generated summary.
# Sample Input and Output Files

See the <b> Samples </b> directory for example input files and their corresponding outputs.

# License

This project is licensed undet the MIT License. See the <a href="https://github.com/jana-selvaraj/AIMeetSummarizer-Azure-OpenAI/blob/main/LICENSE">LICENSE.md</a> file for details.














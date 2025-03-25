# AIMeetSummarizer-Azure-OpenAI

AIMeetSummarizer is an AI-driven tool designed to streamline the summarization of office meeting transcripts. Whether your transcripts are from Microsoft Teams, Skype, or other platforms, AIMeetSummarizer efficiently processes .docx and .txt files, segments them into manageable chunks, and delivers clear, comprehensive summaries using Azure OpenAI.

## Key Features:

**Versatile Format Support:** Compatible with .docx and .txt files.<br>

**AI-Driven Summarization:** Utilizes Azure OpenAI for precise and context-aware summaries. <br>

**Smart Chunking:** Divides lengthy transcripts into smaller, manageable sections for improved processing. <br>

**Flexible Prompts:** Supports JSON-based prompts to customize the summarization process. <br>

# Installation

# Clone the repository:

git clone (https://github.com/jana-selvaraj/AIMeetSummarizer-Azure-OpenAI/)
Install dependencies:
pip install -r requirements.txt
Set up your .env file with the following variables:
AZ_OPENAI_API_KEY=your_api_key
AZ_OPENAI_ENDPOINT=your_endpoint
AZ_OPENAI_DEPLOYMENT_NAME=your_deployment_name
FILE_PATH=path_to_your_transcript_file
Usage
Place your transcript file in the project directory.
Update the DOC_PATH in the .env file.
Run the script:
python MeetSummAIzer.py
Check the <tanscript_filename>_Summary.txt file for the generated summary.
Sample Input and Output
See the Samples directory for example input files and their corresponding outputs.

License
This project is licensed undet the MIT License. See the LICENSE.md file for details.














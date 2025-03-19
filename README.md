# AIMeetSummarizer-Azure-OpenAI

MeetSummAIzer - AI-Powered Meeting Transcript Summarizer
MeetSummAIzer is an AI-powered tool designed to simplify the process of summarizing office meeting transcripts. Whether your transcripts are from Microsoft Teams, Skype, or any other platform, MeetSummAIzer can process .docx and .txt files, chunk them into manageable pieces, and generate concise, comprehensive summaries using Azure OpenAI.

Key Features:
Multi-Format Support: Works with .docx and .txt files.
AI-Powered Summarization: Leverages Azure OpenAI for accurate and context-aware summaries.
Efficient Chunking: Breaks down large transcripts into smaller chunks for better processing.
Customizable Prompts: Use JSON-based prompts to tailor the summarization process.
Installation
Clone the repository:
git clone https://github.com/navindevan/MeetSummAIzer-AzureOpenAI.git
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


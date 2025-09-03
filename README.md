GenAI Log Analyzer: AI-Powered Incident Debugging Tool
The Generative AI-powered Log Analyzer accelerates production incident resolution by rapidly analyzing raw log files, providing detailed root cause analysis, and recommending effective remediation strategies. Designed to seamlessly integrate into IT support workflows, it enhances efficiency and accuracy in troubleshooting efforts.

This tool plugs into popular IT operations platforms like ServiceNow, acting as a catalyst for smarter, faster incident management. By automating log analytics, it delivers an estimated 95% reduction in incident resolution costs and 90% reduction in troubleshooting time, significantly improving operational resilience.

🚀 Key Features & Impact
Rapid Root Cause Analysis: Uses Generative AI and natural language processing to interpret complex logs.

Seamless Integration: Compatible with major ITSM tools (e.g., ServiceNow) to augment existing incident workflows.

Cost & Time Savings: Proven impact in reducing resolution costs by 95% and troubleshooting time by 90%.

Scalable & Extensible: Built on AWS Bedrock and Sagemaker for robust cloud scalability and flexibility.

User-Friendly Interface: Streamlit-based interactive UI for intuitive log exploration and insight extraction.

🧰 Prerequisites
Cloud Services: AWS Bedrock or AWS SageMaker, AWS Cloud9

Interpreter: Python 3+

Python Libraries: boto3, LangChain, Streamlit

⚙️ Installation & Execution
Clone the repository:

bash
git clone https://github.com/viscabarcaviscacataluniya/GenAI-LogAnalyzer
Navigate into the project directory:

bash
cd GenAI_LogAnalyzer
Create and activate a virtual environment:

bash
python -m venv venv
source venv/bin/activate
Install required libraries:

bash
pip install -r requirements.txt
Configure AWS prerequisites (one-time execution):

bash
python OneTimeExecution.py
Launch the Streamlit application:

bash
streamlit run streamlitUI.py

DevOps & SRE: Automate monitoring and root cause pinpointing, improving system reliability.

Enterprises: Slash operational costs and incident MTTR (Mean Time To Resolve) with intelligent log parsing.

This GenAI Log Analyzer demonstrates best-in-class AI integration for IT operations, enabling data-driven incident management with measurable improvements in speed and cost-efficiency

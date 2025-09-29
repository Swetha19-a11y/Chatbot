# INGRES-AI Virtual Assistance(SIH25066)
"Development of an Al-driven ChatBOT for INGRES as a virtual assistant"




"Overview"

This project presents a Streamlit-based AI Virtual Assistant designed to provide insights into groundwater data, specifically tailored for the "INGRES" portal (Interpreted Normalized Groundwater Resources Estimation System). The application aims to offer a user-friendly, interactive chat experience, enabling users to query groundwater information in natural language and receive both textual responses and dynamic data visualizations. This prototype demonstrates core functionalities such as multilingual support, conversational AI (mocked for this prototype), and interactive data charting, laying the groundwork for a more advanced AI-driven data assistant.





"Features"

Interactive Chat Interface: A clean and intuitive chat window built with Streamlit for seamless user interaction.

Multilingual Support: Users can switch between English and several Indian regional languages (Hindi, Tamil, Telugu, Bangla, Marathi, Gujarati, Kannada, Malayalam, Punjabi, Odia) for an inclusive experience.

Conversational AI (Mocked): Responds to user queries about groundwater status, comparisons, and geographical data (e.g., "Status in Pune, Maharashtra," "Compare 2023 vs 2024 in Tamil Nadu," "Map of over-exploited zones"). Note: The AI responses are currently hardcoded mock data for demonstration purposes.

Dynamic Data Visualizations: Automatically generates interactive bar charts, line charts, or maps based on the AI's response, displayed alongside the chat.

Data Download: Allows users to download the visualized data as a CSV file.

Prompt Suggestions: Provides quick-access suggestion buttons to guide users on possible queries.

User Feedback Mechanism: Simple "👍" and "👎" buttons for users to provide feedback on assistant responses.

Onboarding Tutorial: A collapsible welcome message guiding new users on how to interact with the chatbot.

Responsive Layout: Utilizes Streamlit's layout="wide" for an enhanced viewing experience.





"Technology Stack (Prototype)"

Frontend & UI: Streamlit(For rapid development of the interactive web application).

Data Handling: Pandas(Used for basic data manipulation within the mock visualization dataframes).

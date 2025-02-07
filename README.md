# Event Advisor AI System

Event Advisor Chatbot is a powerful, customizable system that connects event organizers with potential attendees by providing updated, personalized event recommendations. Built on Google Colab using the Falcon‑7B‑Instruct model and integrated with the Google Custom Search API, this chatbot retrieves real‑time event data and delivers a natural conversational experience via a Gradio interface.

## Features

- **Real‑Time Event Data:** Uses the Google Custom Search API to fetch up‑to‑date event information.
- **Personalized Recommendations:** Filters events based on user-defined preferences such as city and interests.
- **Conversational AI:** Powered by the Falcon‑7B‑Instruct model to generate natural and context-aware responses.
- **Interactive Interface:** Provides a simple Gradio-based web interface for testing and interaction.
- **Rapid Prototyping:** Designed to run on Google Colab with GPU support, enabling quick experimentation.

## Example Conversation

Below is an example of how the chatbot interacts with a user:

**User Question:**  
> "Fetch me a list of some upcoming tech events in NYC"

**Chatbot Answer:**  
> "Here are some upcoming tech events in NYC:  
> 1. Aug 13-15: NY Tech Meetup  
> 2. Aug 13-15: NYC Data Science Festival  
> 3. Aug 19-21: Web3 Summit  
> 4. Aug 22-23: Future of Web  
> 5. Aug 28-29: New York AI & Machine Learning Meetup  
> 6. Aug 29-30: NYC Tech Job Fair  
> 7. Aug 30-31: TechCrunch Disrupt NYC  
> 8. Aug 27-28: NYCJS Conference"

*Note:* This sample conversation demonstrates the prototype’s capability to retrieve and present event information. Actual event details may vary and depend on real-time data fetched.

event-advisor-chatbot/

├── EventAISystem.ipynb  # Main Colab notebook

├── README.md                  # This file



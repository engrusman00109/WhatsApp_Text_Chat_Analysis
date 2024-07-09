# WhatsApp Chat Analyzer

The WhatsApp Chat Analyzer is a Python-based tool developed using Streamlit for visualizing and analyzing WhatsApp chat data. It provides comprehensive insights into chat statistics, allowing users to understand communication patterns and trends within their chat groups or individual conversations.

### Key Features:
- **Statistics:** Obtain detailed metrics such as total messages, words, media shared (images, videos), and links shared.
- **Timelines:** Visualize chat activity over time with monthly and daily timelines, helping users track peak messaging periods and trends.
- **Activity Maps:** Identify the most active days and months with intuitive bar charts, offering insights into chat dynamics.
- **Wordcloud:** Generate wordclouds based on chat messages to highlight commonly used words and themes within the conversation.
- **Most Common Words:** Analyze the frequency of words used across messages, providing a snapshot of key topics and discussions.
- **User Selection:** Select specific users to analyze their contribution to the chat, enabling targeted insights into individual participation.

### Technologies Used:
- **Python:** Core programming language for data processing and analysis.
- **Streamlit:** Open-source app framework used for building interactive web applications.
- **Matplotlib and Seaborn:** Libraries for data visualization, used to create insightful charts and plots.
- **Pandas:** Data manipulation and analysis tool, utilized for handling and processing chat data.
- **WordCloud:** Library for generating wordcloud visualizations based on text data.

### Usage:
1. **Upload:** Upload a WhatsApp chat export file (.txt format).
2. **Selection:** Choose a specific user for analysis or view overall group chat statistics.
3. **Explore:** Dive into visualizations including timelines, activity maps, wordclouds, and more to gain valuable insights into your WhatsApp conversations.

### How It Works:
- **Data Preprocessing:** Automatically preprocesses uploaded chat data, extracting messages, users, timestamps, and other relevant information.
- **Visualization:** Generates interactive visualizations and insights through Streamlit, allowing for dynamic exploration and analysis of chat metrics.
- **Customization:** Offers flexibility to explore different aspects of the chat data, such as individual user analysis or overall group trends.

### Future Enhancements:
- Incorporate sentiment analysis to understand the emotional tone of conversations.
- Implement more advanced NLP techniques for topic modeling and keyword extraction.
- Enhance user interface and interactivity for a more intuitive user experience.

This project aims to provide WhatsApp users with a powerful tool for understanding their messaging habits, identifying trends, and gaining actionable insights from their chat data.


# WhatsApp Chat Analyzer

WhatsApp Chat Analyzer is a Python-based application that allows you to analyze and visualize WhatsApp chat data. With this tool, you can gain insights into various aspects of your WhatsApp conversations, including message statistics, timelines, activity maps, word clouds, and more.

## Features

- **Statistics**: Get an overview of the total number of messages, words, media shared, and links shared in the chat.
- **Timelines**: Visualize the chat activity over time with monthly and daily timelines.
- **Activity Maps**: Identify the most busy day, month, and weekly activity patterns in the chat.
- **User Analysis**: Analyze individual users' contributions and identify the busiest users in the group.
- **Word Cloud**: Generate a word cloud visualization to visualize the most common words used in the chat.
- **Emoji Analysis**: Explore the usage of emojis and identify the top emojis used in the chat.

## Prerequisites

Before running the application, make sure you have the following dependencies installed:

- Python 3.7+
- Streamlit
- Matplotlib
- Seaborn
- WordCloud
- Pandas
- Emoji
- urlextract

You can install the dependencies by running the following command:

```
pip install -r requirements.txt
```

## Usage

1. Clone the repository or download the source code.
2. Install the required dependencies using the command mentioned in the Prerequisites section.
3. Run the `main.py` file using the command `streamlit run main.py`.
4. Access the application in your web browser at `http://localhost:8501`.
5. In the sidebar, upload your WhatsApp chat data file in the appropriate time format (24-hour format).
6. Select the user you want to analyze or choose "Overall" for group level analysis.
7. Click on the "Show Analysis" button to generate the visualizations and insights.
8. Explore the various sections and visualizations to gain insights into your WhatsApp chat data.

## Customization

You can customize the application by modifying the code according to your requirements. The preprocessing and analysis functions are provided in the `preprocessor.py` and `helper.py` files, respectively. Feel free to adapt these functions or add additional analysis features as needed.

## Resources

- [Streamlit Documentation](https://docs.streamlit.io)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [WordCloud Documentation](https://amueller.github.io/word_cloud/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Emoji Documentation](https://pypi.org/project/emoji/)
- [urlextract Documentation](https://pypi.org/project/urlextract/)

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute to the project by submitting bug reports, feature requests, or pull requests. Enjoy analyzing your WhatsApp chat data!

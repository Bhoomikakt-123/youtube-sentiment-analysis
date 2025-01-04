

# YouTube Comments Analysis Tool

This project provides a Python-based tool to fetch and analyze comments from YouTube videos using the YouTube Data API. The tool is capable of filtering comments, analyzing sentiment, and visualizing results. 

## Features

- **Fetch Comments**: Retrieve up to 600 comments from any public YouTube video.
- **Sentiment Analysis**: Perform sentiment analysis using the VaderSentiment library.
- **Emoji Detection**: Identify comments containing emojis.
- **Uploader Filter**: Exclude comments made by the video uploader.
- **Visualization**: Display sentiment distribution via charts using Matplotlib.

## Prerequisites

- Python 3.7 or higher
- Google API Key with access to the YouTube Data API v3
- Libraries:
  - `google-api-python-client`
  - `vaderSentiment`
  - `emoji`
  - `matplotlib`
  - `requests`

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Obtain a Google API Key:
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create a project and enable the YouTube Data API v3.
   - Generate an API Key and restrict it to the YouTube Data API.

4. Replace the placeholder in the script with your API Key:
   ```python
   API_KEY = "YOUR_API_KEY"
   ```

## Usage

1. Run the script:
   ```bash
   python main.py
   ```

2. Enter the URL of a YouTube video when prompted.

3. The script will:
   - Extract the video ID from the URL.
   - Fetch and filter comments.
   - Analyze sentiments.
   - Display and visualize the results.

## Example

Input:
```
Enter YouTube Video URL: https://www.youtube.com/watch?v=dQw4w9WgXcQ
```

Output:
```
API key is valid!
Video ID: dQw4w9WgXcQ
Channel ID: UC38IQsAvIsxxjztdMZQtwHA
Fetching Comments...
Sentiment Analysis Complete!
```

## Contributing

Contributions are welcome! If you find a bug or have an idea for a feature, feel free to submit an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [YouTube Data API](https://developers.google.com/youtube/v3)
- [VaderSentiment](https://github.com/cjhutto/vaderSentiment)
- [Emoji Library](https://github.com/carpedm20/emoji)
- [Matplotlib](https://matplotlib.org/)

---

Let me know if you'd like further adjustments or if you want a specific section added!


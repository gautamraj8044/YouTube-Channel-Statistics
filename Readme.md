### YouTube Channel Statistics Analysis

This repository contains Python code to retrieve statistics for specific YouTube channels using the YouTube Data API. The retrieved data includes information such as subscribers, views, and total videos for each channel. Additionally, the code utilizes the Pandas library to organize the data into a DataFrame and the Seaborn library to create visualizations for better understanding and analysis.

#### Contents

1. **Python Script**: The Python script named `youtube_channel_stats.py` retrieves channel statistics using the YouTube Data API, organizes the data into a DataFrame, and generates visualizations using Seaborn.

2. **Dependencies**: Ensure that you have the necessary dependencies installed, including `googleapiclient`, `pandas`, and `seaborn`.

3. **API Key**: Replace the `api_key` variable with your own YouTube Data API key to authenticate requests.

4. **Channel IDs**: Modify the `channel_ids` list to include the IDs of the YouTube channels for which you want to retrieve statistics.

#### Usage

1. **Set Up API Key**: Obtain an API key from the Google Cloud Console and replace the existing `api_key` variable in the script with your key.

2. **Specify Channel IDs**: Update the `channel_ids` list with the desired YouTube channel IDs for which you want to retrieve statistics.

3. **Run Script**: Execute the Python script `youtube_channel_stats.py`. It will fetch channel statistics, organize them into a DataFrame, and display visualizations using Seaborn.

#### Visualization

- **Subscriber Count**: A bar plot displaying the number of subscribers for each channel.
- **Total Views**: A bar plot showing the total number of views for each channel.
- **Total Videos**: A bar plot illustrating the total count of videos uploaded by each channel.

#### Acknowledgments

This project utilizes the YouTube Data API to access publicly available statistics for YouTube channels. Special thanks to the developers of the `googleapiclient`, `pandas`, and `seaborn` libraries for their contributions to making data retrieval and visualization tasks more accessible in Python.
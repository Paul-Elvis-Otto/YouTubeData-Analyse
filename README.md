# YouTube Data Analysis

This project is dedicated to the collection and analysis of YouTube data using `pytube`, `pandas`, `selenium`, and `matplotlib`.

## LinkScraper

The `LinkScraper` script employs a Selenium web browser to gather all video URLs and titles posted under the `youtube/channel-ID/videos` link. The data are named according to the channel ID. The output from the Python script is written to a `.csv` file for subsequent analysis.

### How It Works

1. Initialization of the Selenium browser.
2. Navigation to the specific YouTube channel page.
3. Extraction of video URLs and titles.
4. Saving the collected data into a `.csv` file.

### Output Format

The `.csv` file contains the following columns:

- `Video URL`
- `Title`

## Data Analysis

The second part of the project is presented in a Jupyter Notebook. It includes example functions from `matplotlib` and `numpy` to provide an idea of what future analyses with an adequate dataset might look like.

### Examples of Analyses

- Visualization of views, likes, and comment counts.
- Time series analysis to identify trends.
- Correlation analysis between different metrics.

## Open Tasks

- [ ] Development of additional methods for data collection.
- [ ] Utilizing the additional data for more detailed analyses.
- [ ] Collection of audio data for transcript analysis.
- [ ] Creation of an export-ready table.








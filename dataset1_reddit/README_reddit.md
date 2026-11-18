## Dataset 1: Reddit Data

### Overview
This dataset contains Reddit threads and associated comments that mention our five selected K-dramas: *Mask Girl*, *True Beauty*, *My ID Is Gangnam Beauty*, *Birth of a Beauty*, and *Boys Over Flowers*.

### Data Collection

1. Used the provided Reddit Search Engine Streamlit to search for and download Reddit threads/comments for each drama.
2. Exported the thread metadata into separate JSONL files.
3. Used the thread ids to query the submissions and comments tables in the kdrama_reddit.duckdb database using given code.
4. Extracted the thread submissions and comments and exported into JSONL files.
5. Consolidated the exported files into a single DataFrame and saved the master dataset as a CSV file.
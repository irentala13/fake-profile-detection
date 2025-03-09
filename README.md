
# fake-profile-detection

# Exploratory_Data_Analysis_HU_HT_Dataset

## Data file Overview

Each file name follows the format: `Platform_ID_Video_ID_Session_ID_UserID.csv`

### Where:
- **Platform_ID**: Represents the social media platform (Facebook, Instagram, Twitter).
- **Video_ID**: Identifies the specific video being analysed (1, 2, 3).
- **Session_ID**: Represents the session count, where each session consists of two iterations.
- **UserID**: Identifies the user.

## Folder "1001" Structure

The folder "1001" contains 18 CSV files, each corresponding to a different combination of platform, video, and session.

### Breakdown of Filenames:

#### Platform_ID (First number in the filename)
- `1_x_x_x`: Facebook
- `2_x_x_x`: Instagram
- `3_x_x_x`: Twitter

#### Video_ID (Second number in the filename)
- Represents different video contents.

#### Session_ID (Third number in the filename)
- Sessions indicate multiple interactions with the same video.
- Each session includes two iterations.

#### User_ID (Last part in the filename)
- User identifier (1001 in this case).

## Example File Name Interpretation

- `1_1_1_1001.csv` → Facebook, Video 1, Session 1, User 1001
- `2_3_2_1001.csv` → Instagram, Video 3, Session 2, User 1001
- `3_2_1_1001.csv` → Twitter, Video 2, Session 1, User 1001

Each folder for a different User ID (e.g., "1001") follows the same structure, containing **18 files**, covering all platform, video, and session combinations.

---

## ✅ What This Exploratory_Data_Analysis_HU_HT_Dataset Code Does:

- Uploads CSV file interactively in Colab.
- Computes **summary statistics** on file presence/missingness.
- **Visualizes**:
  - Overall file presence ratio.
  - File-wise missing counts (which files are missing more?).
  - User-wise completion rates.
  - Present vs Missing per User (Bar and Stacked Bar).
  - Scatter of Present vs Missing files to identify anomalies.
  - Histogram of missing file counts for user distribution.
- Displays **summary report** of all key counts (users, files present, files missing).

# Computing with Hypervectors for Speaker Identification
Use an N-gram based model (based on the priciples of Hyperdimensional Computing) to learn the statistics of acoustic signals over both time and frequency so that the unique pronunciation variations (courses of formants over time) between speakers can be captured.

## Data
We used the VoxCeleb dataset [1] to develop and test the algorithm. It consists of speech from 1,251 speakers collected from YouTube videos. Each speaker has a folder, divided into a number
of subfolders that contain the audio files. The subfolders come from different videos and are referred to as different “contexts.” The speech files in the subfolders are called “utterances.”
Following the same procedure as in [2], we reserved one subfolder/context for testing that had the fewest utterances but at least five.

## Setup
1. Clone the repo.
2. Navigate to the directory containing the repo directory.
3. Navigate into the repo and install the requirements using `pip install -r requirements.txt`
4. Download the VoxCleb1 dataset of 1,251 speakers from [1] and place the data folders (id10001, id10002, id10003, ...) inside the repo directory
5. Running the demo notebook: `HD_VoxCeleb_release.ipynb`

## Reference
[1] https://www.robots.ox.ac.uk/%7Evgg/data/voxceleb/vox1.html
[2] Nagrani, Arsha, Joon Son Chung, and Andrew Zisserman. "Voxceleb: a large-scale speaker identification dataset." arXiv preprint arXiv:1706.08612 (2017).

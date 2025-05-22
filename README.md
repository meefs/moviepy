# MoviePy Trailer Example

This repository demonstrates how to cut and compose video clips with [MoviePy](https://zulko.github.io/moviepy/).
The `trailer.py` script loads a sample movie, extracts scenes, adds text overlays, and renders a short trailer.
A Jupyter notebook version is also provided in `trailer.ipynb`.

## Installation

1. Install Python 3.7+.
2. Install MoviePy and NumPy using pip:

```bash
pip install moviepy numpy
```

MoviePy relies on [FFmpeg](https://ffmpeg.org/) for reading and writing video files.
If FFmpeg is not available on your system, install it separately (for example `pip install imageio[ffmpeg]` or via your OS package manager).
Preview windows require `ffplay`, which is distributed with FFmpeg.

## Running the example

Run the script from the repository root:

```bash
python trailer.py
```

The script opens preview windows for each clip and creates `result.mp4` when rendering is finished.
Alternatively, open `trailer.ipynb` in Jupyter Notebook to explore the steps interactively.


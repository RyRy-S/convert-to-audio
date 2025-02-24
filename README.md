
Markdown
# convert-to-audio

Convert all video files to MP3 in a single directory or recursively.

## Prerequisites

- `ffmpeg` must be installed on your system. You can install it using the following commands:
  - On Ubuntu/Debian: `sudo apt-get install ffmpeg`
  - On macOS: `brew install ffmpeg`
  - On Windows: Download and install from the [official site](https://ffmpeg.org/download.html)

- Ensure the `convert-to-audio` script is saved in your PATH to call the script without `./`. You can do this by adding the script directory to your PATH:
  ```bash
  export PATH=$PATH:/path/to/convert-to-audio
Usage
Basic Usage
Convert all video files in a specified directory to MP3:

bash
convert-to-audio /path/to/directory
Recursive Conversion
Recursively convert video files in a directory and its subdirectories to MP3:

bash
convert-to-audio -r /path/to/directory
convert-to-audio -recursive /path/to/directory
Options
-r, -recursive : Recursively process video files in the directory and its subdirectories.
Examples
Convert all video files in a directory
bash
convert-to-audio /foo
Recursively convert video files in a directory and its subdirectories
bash
convert-to-audio -r /foo
convert-to-audio -recursive /foo
Notes
The script will convert supported video file formats (e.g., .mp4, .mkv, .avi, etc.) to MP3.
Make sure ffmpeg is installed and accessible from your command line.
Code
You can add this content to your `README.md` to provide a comprehensive description of the `convert-to-audio` script.

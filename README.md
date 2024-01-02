# File Mover

This Python script is designed to move image files (`.jpg`, `.png`, `.jpeg`, `.gif`) from your Downloads folder to a target directory named "Pics" in your home directory.

### Usage:

1. **Requirements:** Python 3.x
2. Clone or download the repository.
3. Ensure Python is installed.
4. Run the script by executing `python main.py`.

### Functionality:

- **`move_files(src, dst)` function:** Moves image files from the source directory (`src`) to the destination directory (`dst`).
- **Default Paths:**
  - Source: Your Downloads folder.
  - Destination: A folder named "Pics" in your home directory.

### How to Use:

1. Modify the file types (`fileTypes` variable) within the script if you want to include additional or exclude certain file types.
2. Adjust the `targetPath` variable if you want the destination folder to be different.
3. Run the script and observe the files being moved from Downloads to the Pics folder.

### Note:

- If the destination directory "Pics" does not exist, the script will create one.
- Any errors encountered during the file-moving process will be displayed.

Feel free to modify this script to suit your specific needs or integrate it into other projects.

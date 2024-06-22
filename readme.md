# Background Replacement with OpenCV and CVZone

This project demonstrates real-time background replacement using the OpenCV library and the CVZone module. The script captures video from your webcam, replaces the background with preloaded images, and displays the results. Users can cycle through different background images using keyboard inputs.

## Requirements

- Python 3.6 or higher
- OpenCV
- CVZone
- A webcam

## Usage

### Running the Script

1. Ensure you have a folder named `Bag` in your working directory containing the background images you want to use. Each image should be in a format compatible with OpenCV (e.g., JPEG, PNG).

2. Run the `background_replacement.py` script. This script will:
    - Initialize video capture from your webcam.
    - Load and resize background images.
    - Perform real-time background replacement.
    - Display the original and processed video streams.
    - Allow you to switch between different background images using keyboard inputs.

### Controls

- Press `a` to switch to the previous background image.
- Press `d` to switch to the next background image.
- Press `q` to quit the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

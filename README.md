# CO528-Assignment-02-E18285-HTML
CO528 -Applied Software Architecture Assignment 02. Syncing angle selector using HTML and Vanilla JS

# Angle Syncer Application

This is a simple web application that allows users to synchronize an angle value between 0 and 360 across a text box, slider, and a set of radio buttons. The application ensures that all inputs are kept in sync, whether the angle is entered manually, adjusted using the slider, or selected via the radio buttons.

## Features

- **Text Box**: Enter an angle value directly. If the entered value exceeds 360 or is negative, it will be mapped to an equivalent angle within the 0 to 360 range.
- **Slider**: Adjust the angle using a slider. The slider's background fills according to the selected angle, starting from the middle for 0 degrees.
- **Radio Buttons**: Select common angle values (0, 45, 60, 90, 180) using radio buttons. The selected radio button will reflect the current angle.
- **Angle Updating**: When enter a angle greater than 360, it will automatically adjusted to equivalent angle between 0 and 360.

All three controls (text box, slider, and radio buttons) are synchronized. Changing the value in one control will update the other controls to match.

## How to Use

1. **Enter an Angle**: Type a value directly into the text box.
2. **Adjust the Slider**: Move the slider to select an angle.
3. **Select a Preset Angle**: Click on one of the radio buttons to select a common angle.

The controls will automatically update to reflect the selected angle.

## Installation

No installation is required for this application. All you need is a web browser.

### Files

- `index.html`: The main HTML file containing the structure of the application.
- `styles.css`: The CSS file containing styles for the application's layout and appearance.
- `README.md`: This file, describing the application and how to use it.

### How to Start

1. **Download or Clone the Repository**:
   - Clone the repository using Git:
     ```bash
     git clone https://github.com/TharinduChamod/CO528-Assignment-02-E18285-HTML.git
     ```
   - Or download the ZIP file from the repository and extract it.

2. **Open the Application**:
   - Open the `index.html` file in your web browser. There is no need for a web server, as the application is fully client-side.


## Additional Information

This application was created using vanilla JavaScript, HTML, and CSS. It is lightweight and does not require any external libraries or frameworks. The code is organized to be easily understandable and modifiable.

## Author
 - S.M.T.S.C. Ranasinghe
 - E/18/285

Feel free to modify and use this code for your own purposes!


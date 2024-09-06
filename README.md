# Image Filter Previewer

## Description
The **Image Filter Previewer** is a simple web application that allows users to apply and preview different CSS image filters in real-time. Users can adjust the blur, grayscale, brightness, and contrast of a sample image using slider inputs. This tool is useful for graphic designers, web developers, and anyone who wants to experiment with image filters directly in the browser.

## Features
- **Real-time filter preview**: Adjust image filters (blur, grayscale, brightness, contrast) and see the effects applied instantly.
- **Interactive sliders**: Use range sliders to control the intensity of each filter.
- **Responsive design**: The app is built with a responsive layout to work well on various screen sizes.

## Technologies Used
- **HTML5**: For the structure of the webpage.
- **CSS3**: Basic styling and layout of the page, as well as image responsiveness.
- **JavaScript**: Handles the logic for applying CSS filters dynamically as users adjust sliders.

## How to Use
1. Open the `index.html` file in any modern web browser.
2. Adjust the filter sliders (blur, grayscale, brightness, and contrast) to see the changes applied to the image in real-time.
3. The filter values are dynamically applied to the image based on the slider positions.

### Available Filters:
- **Blur**: Adjusts the amount of blur applied to the image (0px to 10px).
- **Grayscale**: Converts the image to grayscale (0% to 100%).
- **Brightness**: Changes the brightness of the image (50% to 150%).
- **Contrast**: Alters the contrast of the image (50% to 150%).

## Code Explanation
- **HTML**: Provides the basic structure of the page with an image element, filter sliders (range inputs), and a heading.
- **CSS**: Styles the page, ensuring the image is responsive, and the layout is centered and user-friendly.
- **JavaScript**: 
  - `applyFilters()`: Retrieves the slider values for each filter and applies them to the image using CSS `filter` property.
  - Each filter is controlled using a range input, and the filter values are updated dynamically with each slider change.

## Installation
1. Download or clone the repository.
2. Open the `index.html` file in your web browser to use the application.

## Future Enhancements
- Add more filter controls such as hue-rotation, sepia, or invert filters.
- Allow users to upload their own images for previewing.
- Implement the ability to download the filtered image.

## License
This project is open source and available under the MIT License.

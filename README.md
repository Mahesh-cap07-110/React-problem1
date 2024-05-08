# React-problem1
Children props in React Component


Explanation:

Gallery Component: The Gallery component accepts a children prop, which represents the child components passed to it. It uses CSS grid layout to display the images in a responsive grid.
Image Component: The Image component is a simple functional component that renders an image with the provided src prop. It ensures that the image width is set to 100% of its container, making it responsive.
Rendering: The ReactDOM.render method is used to render the Gallery component with Image children inside the root div.
Design Choice: I chose a grid layout for the Gallery component because it provides an organized and visually appealing way to display images. The repeat(auto-fill, minmax(200px, 1fr)) value for gridTemplateColumns ensures that the columns adjust dynamically based on the available space, allowing for a flexible and responsive layout. Additionally, the gap property adds spacing between the images for better readability
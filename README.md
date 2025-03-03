# EASING
EASING is a Desktop Application that allows you to create front-end animations in an intuitive way. With its graphical interface, real-time preview, and JSON export functionality, EASING makes it easy to integrate advanced animations into your code using a dedicated JavaScript/TypeScript library.

## :art: Basics Fonctionalities
- **Animation Editor** : Create and fine-tune animations with a graph-based interface and keyframe editor.
![Logo EASING](assets/logo.png)
- **Integrated Web Preview**: Navigate your website within the application, select elements, and see how your animations will look in real time.
- **Real-Time Preview**: Instantly view your animation adjustments, ensuring precise timing and visual feedback.
- **JSON Export**: Export your animations as a JSON file, which can then be easily imported and executed in your projects.
- **Animation Library**: A dedicated JavaScript/TypeScript library that reads the exported JSON and applies the animations to targeted elements in your code.

## :rocket: Getting Started

_EASING is currently in its early stages of development. Contributions are welcome to help shape the project!_

## :smile: Contributing

We welcome contributions from the community. If you’d like to help improve EASING, please take a look at our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to get started. Any feedback, bug reports, or suggestions are greatly appreciated.

## :book: License

EASING is released under the GNU GPLv3 license. See the [LICENSE](LICENSE) file for details.

## Installation (Coming Soon)

The installation instructions will be updated as the project evolves. For now, here is a preliminary outline:

### Desktop Application

1. Clone the repository:  
   `git clone https://github.com/your-username/EASING.git`
2. Navigate to the `src/desktop-app` folder and install the dependencies (e.g., `npm install` if using Electron).
3. Launch the application:  
   `npm start`

### Animation Library

1. Navigate to the `src/easing-library` folder, install dependencies, and build the minified version.
2. Include the library in your HTML/CSS project as follows:

   ```html
   <script src="path/to/easing-library.min.js"></script>
   <script>
     // Example initialization
     EasingLibrary.init('path/to/animations.json');
   </script>

# Tunees Player Application

## Overview

This Music Player Application is a web-based application built using React and Tailwind CSS. It allows users to play songs from a playlist, navigate through the playlist, and toggle the display of the playlist. The design is responsive, ensuring a seamless experience across different devices and screen sizes.

## Features

- Display the currently playing song with its title and artist.
- Control buttons to play, pause, navigate to the next and previous songs.
- Toggle button to show/hide the playlist.
- Playlist displayed as a list with song images, titles, and artists.
- Sticky toggle button that remains on top during scrolling.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Installation

1. **Clone the repository:**


2. **Install the dependencies:**

    ```bash
    npm install
    ```

3. **Run the application:**

    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Code Structure

### Components

- **MusicPlayer.jsx**: The main component that renders the music player and playlist.
- **Playlist.jsx**: A component that displays the list of songs in the playlist.

### Hooks

- **useState**: Manages the state of the currently playing song, play/pause status, and the visibility of the playlist.
- **useEffect**: Listens for scroll events to update the UI accordingly.

### Styles

- **Tailwind CSS**: Used for styling the components, providing a responsive and modern design.


## Contributing

1. Fork the repository.
2. Create your feature branch (`git

 checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project uses [Tailwind CSS](https://tailwindcss.com/) for styling.
- Icons are provided by [SVGRepo](https://www.svgrepo.com/).

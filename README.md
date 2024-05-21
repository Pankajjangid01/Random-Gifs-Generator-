# Random GIFs

This project is a simple React application that displays random GIFs using the Giphy API. It consists of two main components: `Random` and `Tag`. The `Random` component fetches and displays a random GIF, while the `Tag` component (to be implemented) fetches and displays a GIF based on a user-specified tag.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
  - [Random](#random)
  - [Tag](#tag)
- [Custom Hooks](#custom-hooks)
  - [useGif](#usegif)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
    ```

2. Navigate to the project directory:
    ```bash
    cd YOUR_REPOSITORY
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your Giphy API key:
    ```plaintext
    REACT_APP_GIPHY_API_KEY=your_giphy_api_key
    ```

## Usage

1. Start the development server:
    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Components

### Random

The `Random` component fetches and displays a random GIF. It uses the custom hook `useGif` to manage the state and handle the API request.

### Tag

The `Tag` component (to be implemented) will fetch and display a GIF based on a user-specified tag.

## Custom Hooks

### useGif

The `useGif` hook manages the state for GIF fetching. It handles the API request to the Giphy API and provides the `gif` URL and `loading` state.

## Contributing

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/YourFeature
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add your feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/YourFeature
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License.

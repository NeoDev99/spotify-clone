# CorrectProject

CorrectProject is a React application for connecting to Spotify's API and performing various actions like playing tracks, viewing user information, and accessing playlists.

## Technologies Used

- React
- Styled Components

## Libraries and Assets Used

- [Spotify API](https://developer.spotify.com/documentation/web-api/): Spotify API provides endpoints for accessing user-related data, playlists, and tracks.
- [React Icons](https://react-icons.github.io/react-icons/): React Icons library provides a collection of popular icons for use in React applications.
- [Axios](https://axios-http.com/): Axios is a promise-based HTTP client for making requests to APIs.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/correctproject.git
    ```

2. Navigate into the project directory:
    ```cmd
    cd correctproject
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

    or

    ```bash
    yarn install
    ```

## Usage

1. Obtain a Spotify Client ID:

- Register your application on the Spotify Developer Dashboard.
- Copy your Client ID.

2. Set up environment variables:

- Create a .env file in the root directory of the project.
- Add your Spotify Client ID and Redirect URI to the .env file:

    ```bash
    REACT_APP_SPOTIFY_CLIENT_ID=your_client_id_here
    REACT_APP_SPOTIFY_REDIRECT_URI=http://localhost:3000/
    ```


## Features

- Connect to Spotify: Log in with your Spotify account and grant permissions to the application.
- Play Tracks: Play your favorite tracks from Spotify.
- View User Information: Access your profile and user-related data.
- Access Playlists: View and manage your playlists.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the MIT License.
# MERN Stack Development Task 3

This project is a simple webpage developed using the MERN stack. It displays a list of users and the details of a selected user.

## Features

- Displays a list of users with their profile picture and name.
- Shows the details of a selected user on the right-hand side column.
- Uses loaders when data is being fetched from the API.
- Handles API errors gracefully, displaying a message like "No data to show" in case of server error or empty response.

## Design

The UI design is based on a [Figma design](https://www.figma.com/file/L6fBLuaToOzimvKukrx5zM/Untitled?type=design&node-id=0%3A1&mode=design&t=iDYq2k5cPolkVL1y-1). The actual UI is not be the same as the design, but it fulfills the same requirements.

## API

The data for the users is fetched from the following API: https://602e7c2c4410730017c50b9d.mockapi.io/users

## Libraries Used

- ReactJS for the frontend.
- React Bootstrap for the UI components.
- Axios for making API calls.

## Note

- The webpage does not reload at any point in time.
- There is no blank screen when the data is being loaded. Loaders or spinners are used instead.

## Project Link

You can view the project here: [Link](https://assignment-fetchusers.vercel.app/)

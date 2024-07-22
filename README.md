## Project Overview
FlightExplorer is a web application that allows users to log in to manage their flight bookings. It provides a secure login system and interfaces with a MySQL database to authenticate users.

## Base URL

The base URL for the API is: http://127.0.0.1:5000

## Usage
To log in to the application, send a POST request to `/login` with the following JSON body:

{
  "username": "your_username",
  "password": "your_password"
}

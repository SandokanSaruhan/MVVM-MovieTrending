# iOS Movie Trending List App

This is a simple iOS application demonstrating the use of the **Model-View-ViewModel (MVVM)** pattern in Swift. 
The app fetches and displays a list of trending movies. 
The app is designed as an educational project based on the **Swift Academy YouTube** channel's tutorial series. 
This repository showcases core iOS development concepts using the MVVM architecture.

## Features

- Fetches trending movies from a movie API.
- Displays movies in a clean and responsive UI.
- Utilizes the MVVM architecture for a clear separation of concerns.
- Demonstrates network requests and async data loading in Swift.
- Uses modern Swift coding conventions and UIKit for UI design.

## Video Tutorial

This project is inspired by the **Swift Academy** YouTube channel, where you can follow a step-by-step tutorial to build the app. You can watch the video series [here](https://www.youtube.com/playlist?list=PL0xyzaDFbPAfEXWPHc2eknBZkClLmKOJX).

## Requirements

- iOS 14.0+
- Xcode 12.0+
- Swift 5.0+
- Basic knowledge of Swift and UIKit

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Open the project in Xcode:
    ```bash
    open MovieTrendingList.xcodeproj
    ```

3. Install dependencies if required (e.g., via CocoaPods or Swift Package Manager).

4. Build and run the project in the simulator or on a physical device.

## Architecture

This app follows the **MVVM architecture**, where:

- **Model**: Represents the data (e.g., movie details).
- **View**: Handles the presentation layer (e.g., the UI components).
- **ViewModel**: Acts as the intermediary between the Model and the View, handling the logic of fetching and preparing data for display.

### Folder Structure

```plaintext
├── Models
│   └── Movie.swift
├── Views
│   ├── MovieListViewController.swift
│   └── MovieCell.swift
├── ViewModels
│   └── MovieListViewModel.swift
└── Network
    └── MovieService.swift



Models: Contains the data structure (e.g., Movie).
Views: UI components such as view controllers and custom table view cells.
ViewModels: Contains the logic that connects the model with the view.
Network: Handles the API calls to fetch movie data.
API
This app uses the Movie Database (TMDb) API to fetch trending movie data. You need an API key from TMDb to run this app.

Getting an API Key
Sign up on TMDb.
Go to your account settings, and navigate to the "API" section.



Generate your API key.
Add the API key to your project in MovieService.swift

let apiKey = "YOUR_API_KEY"



Credits
This project is inspired by the tutorial series from Swift Academy YouTube Channel. Watch the video tutorials here.

License
This project is licensed under the MIT License. See the LICENSE file for details.

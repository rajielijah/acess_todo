# Photo Gallery & To-Do List App

## Description

This Flutter application combines a To-Do List with a Photo Gallery. Users can manage daily tasks with a simple to-do list interface and explore a gallery of photos fetched from an external API. The app demonstrates effective state management, network requests, and local data persistence.

## Features

- **To-Do List:**
  - Add new to-do items via a popup form.
  - Display a list of tasks with options to check off completed tasks and delete others.
  
- **Photo Gallery:**
  - Fetch and display photos from a predefined API.
  - Persist the first 20 photo items locally for offline access.
  - Display each photo with its title.
  - Gracefully handle loading and error states.

## Project Structure

- `/lib`:
  - `/data`
  - `/domain`
  - `/presentation`
- `/assets`: Static assets like images and icons used in the app.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Flutter SDK
- Android Studio or Visual Studio Code
- An emulator or physical device to run the app

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rajielijah/acess_todo.git
   cd acess_todo
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the app:**
   ```bash
   flutter run
   ```

### Building the app

- **Android:**
  ```bash
  flutter build apk
  ```

- **iOS:**
  ```bash
  flutter build ios
  ```

## Usage

- Tap the '+' icon on the bottom navigation bar to add new to-do items.
- Check off tasks as completed or delete them using the actions on the To-Do List screen.
- Access the Photo Gallery by clicking the menu icon at the top left of the To-Do List screen.
- View photos, their titles, and enjoy offline capabilities for previously loaded images.

# NewsFeedApp

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Setup Instructions](#setup-instructions)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)


## Introduction

NewsFeedApp is a single-screen news feed application built with React Native and TypeScript. The app features a custom-made "Swipe to fetch button" to fetch and display news.

## Features

- React Native setup with TypeScript
- Custom swipe control to fetch news
- Efficient data fetching with SWR
- Clean and maintainable code with inline comments
- User-friendly interface

## Setup Instructions

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Android Studio](https://developer.android.com/studio)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Sankeerth-g7/NewsFeedApp.git
   cd NewsFeedApp
2. Install the dependencies:
   ```sh
   npm install
   ```
   or
   ```sh
   yarn
   ```
3. Start the Metro server:
   ```sh
   npx react-native start
   ```
4. Run the app on an Android emulator or device:
   ```sh
   npx react-native run-android
   ```

## Usage

1. Swipe on the button to fetch news.

## Project Structure

The project structure is as follows:

```sh
NewsFeedApp/
├── android/
├── ios/
├── src/
│   ├── components/
│   │   ├── NewsCard.tsx
│   │   └── SwipeButton.tsx
├── .gitignore
├── App.tsx
├── babel.config.js
├── index.js
├── package.json
├── README.md
└── tsconfig.json
```
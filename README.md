# Knowledge Cafe

A React-based web application designed to display blogs and allow users to bookmark their favorite articles.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Folder Structure](#folder-structure)
5. [Components](#components)
6. [Usage](#usage)
7. [Dependencies](#dependencies)
8. [Contributing](#contributing)
9. [License](#license)

---

## Overview

The **Knowledge Cafe** application is a blog interface where users can browse blogs, view details about the blog authors, and bookmark articles for future reference. 

---

## Features

- **Header Section**: Displays the title and profile image.
- **Blog Listing**: Dynamically loads blogs with details such as author name, post date, and hashtags.
- **Bookmark Functionality**: Users can bookmark blogs with a simple button click.
- **Responsive Design**: Optimized for desktop and mobile screens.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/knowledge-cafe.git
2. Navigate into the project directory:
   ```bash
   cd knowledge-cafe
3. Install the dependencies:
   ```bash
   npm install
4. Start the development server:
   ```bash
   npm run dev
## Folder Structure
src
├── assets               # Contains static files like images
├── components           # React components used in the app
│   ├── Blog             # Single blog component
│   ├── Blogs            # Container for all blogs
│   ├── Bookmarks        # Bookmark management component
│   ├── Header           # Header with title and profile
├── App.css              # Styles for the App component
├── App.jsx              # Main App component
├── index.css            # Global styles
├── index.js             # Entry point for the React application
# Knowledge Cafe

A blogging platform where users can view, bookmark, and read blogs. The layout is responsive and adapts to different screen sizes.

## Components

### 1. Header
- **File**: `components/Header/Header.jsx`
- **Description**: Displays the title "Knowledge Cafe" and a profile picture.

### 2. Blogs
- **File**: `components/Blogs/Blogs.jsx`
- **Description**: Container for listing all blog components.

### 3. Blog
- **File**: `components/Blog/Blog.jsx`
- **Description**: Displays blog details such as:
  - Title
  - Author info
  - Posted date
  - Reading time
  - Hashtags
- Includes a button to bookmark the blog.

### 4. Bookmarks
- **File**: `components/Bookmarks/Bookmarks.jsx`
- **Description**: Displays the list of bookmarked blogs.

## Usage

### Add Bookmarks
Click the bookmark icon next to a blog's reading time to add it to the bookmarks section.

### View Blogs
Blogs are displayed dynamically in the Blogs component.

### Responsive Layout
The application adjusts to different screen sizes seamlessly.

## Dependencies
The following libraries are used in this project:
- **React**: UI library for building components.
- **React Icons**: Provides the bookmark icon.
- **PropTypes**: Used for type-checking props.

```
npm install react react-dom react-icons prop-types
```
## Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

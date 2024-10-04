# Nuxeo UI Layout

This repository contains the custom UI layout for a Nuxeo project, designed to provide an enhanced user interface for viewing, editing, and managing media files. The project primarily uses HTML, CSS, and native JavaScript to extend and customize Nuxeo templates.

## Overview

### Home Layout (Thumbnail View)

- **Thumbnail Display**: Images are displayed in a grid with a small action bar on each thumbnail. The action bar allows users to:
  - **Edit**: Opens a pop-up to modify metadata like the title, type, and description.
  - **View**: Redirects to a detailed view page for the image.
  - **Delete**: Opens a confirmation pop-up for deletion.

### View Page

- **Image Display**: The view page shows the selected image along with metadata (title, description, etc.).
- **Editing Bar**: 
  - **Rotate**: Rotate the image to the right or left.
  - **Zoom**: Zoom in and out of the image, with a toggle zoom function.
  - **Add Tag**: Add tags to specific areas of the image. Tags are saved to the metadata and are shown using bounding boxes around the tagged areas, with titles and edges clearly marked.

### Edit Pop-up

- **Image Editing**: The edit pop-up allows users to:
  - **Crop**: Crop the image and save the changes.
  - **Brightness Slider**: Adjust the brightness of the image.
  - **Black-and-White Filter**: Apply a black-and-white filter to the image.

All changes made within the pop-up are automatically saved and reflected across the UI, including the metadata.

### Location Pop-up

- **Location Tagging**: When adding an event to an image, a location pop-up allows users to search for a location using a map interface, select the desired location, and save it as part of the image’s metadata. This functionality enables location-based search within the application.

## Nuxeo Integration

This project uses Nuxeo’s UI framework, which provides customizable templates for building content management interfaces. Here are the key elements involved in extending Nuxeo's UI:

- **HTML**: The structure of the UI elements is defined using custom HTML.
- **CSS**: Custom styles are applied to match the layout’s design, particularly for thumbnails, pop-ups, and editing components.
- **JavaScript**: Native JavaScript is used to implement interactivity, such as opening pop-ups, rotating and zooming images, managing tags, and making API calls to update metadata.

## Features

- **Dynamic Thumbnail View**: Displays images in a grid with actions for editing, viewing, and deleting.
- **Image Metadata Management**: Users can edit and update the image’s metadata, including adding tags and location details.
- **Image Manipulation Tools**: Allows users to crop, adjust brightness, apply filters, and rotate images, with real-time updates to the UI.
- **Tagging System**: Add and manage tags for images, with a visual bounding box system.
- **Location Search**: Integrated map search for tagging images with location data.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bassanthossamxx/Nuxeo-UI-layout.git
   cd Nuxeo-UI-layout

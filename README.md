# Calendar Application README

Welcome to the Calendar Application! This README provides an overview of the features and capabilities of our web-based calendar application, which utilizes the RESTful web services described in the specification. We've designed the user interface using Bootstrap to create a modern and user-friendly experience.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [API Integration](#api-integration)
5. [Error Handling](#error-handling)
6. [Demo](#demo)
7. [Contact](#contact)

## Introduction <a name="introduction"></a>

Our Calendar Application is a web-based tool that allows users to manage their events and appointments seamlessly. We've implemented this application using a set of RESTful APIs, as described in the provided specification. The application's UI is designed with Bootstrap to ensure a responsive and intuitive user experience.

## Features <a name="features"></a>

### 1. Event Management

- **Create Events**: Users can create new events by specifying event details such as title, location, organizer, date, time, status, and more.

- **View Events**: The application displays a list of all available events for the user's account, complete with event details, category assignments, and optional images.

- **Update Events**: Users can modify existing events, including all event fields, and see the changes reflected in real-time.

- **Delete Events**: Event deletion is as simple as a click, with confirmation to prevent accidental deletions.

### 2. Category Management

- **List Categories**: Our application provides a list of all available categories that users can assign to their events for better organization.

- **Create Categories**: Users can create new categories with a maximum character limit to keep event categorization efficient.

- **Retrieve Categories**: Easily view category details, such as the category name, to ensure accurate categorization.

- **Delete Categories**: Remove unnecessary categories with a straightforward delete operation.

### 3. Category Assignment

- **Add Events to Categories**: Users can categorize events by assigning them to one or more categories for better event organization.

- **Remove Events from Categories**: For flexibility, our application allows users to remove events from categories when needed.

### 4. Image Handling

- **Add Images to Events**: Users can enhance their events by attaching images, helping to provide more context and visual appeal.

- **Remove Images from Events**: When images are no longer needed, users can quickly remove them from events.

### 5. User-Friendly Interface

- **Bootstrap UI**: We've utilized Bootstrap to design a clean and responsive user interface, making it easy for users to navigate, create, and manage their events.

## Getting Started <a name="getting-started"></a>

To get started with the Calendar Application, follow these steps:

1. Clone the given repository and open the index.html file using a compatible web browser.

3. Explore the user-friendly interface, and use the features listed above to create, manage, and organize your events.

4. To make API requests, simply interact with the application's UI. Behind the scenes, the application communicates with the provided RESTful APIs to perform the requested operations.

## API Integration <a name="api-integration"></a>

Our application seamlessly integrates with the RESTful APIs provided in the specification. These APIs handle data storage and management, enabling the application to focus on delivering a rich user experience. Below is an overview of the API endpoints used:

- **Event-related API Endpoints**:
    - Create Event
    - Retrieve All Events
    - Retrieve Event by ID
    - Update Event
    - Delete Event

- **Category-related API Endpoints**:
    - List Categories
    - Create Category
    - Retrieve Category by ID
    - Delete Category

- **Category Assignment API Endpoints**:
    - Add Event to Category
    - Remove Event from Category

- **Image Handling API Endpoints**:
    - Add Image to Event
    - Remove Image from Event

These APIs ensure seamless data management and enable the Calendar Application to provide a complete event management solution.

## Error Handling <a name="error-handling"></a>

The application follows the error handling guidelines specified in the API documentation. In case of API requests resulting in errors, appropriate error messages and status codes are returned to inform the user.

## Demo <a name="demo"></a>

To explore the features and capabilities of our Calendar Application, you can access a live demo [here](https://djon.info/Web_Engeneering_Project). Feel free to interact with the application to get a feel for how it works.

## Contact <a name="contact"></a>

If you have any questions, feedback, or encounter any issues while using our Calendar Application, please don't hesitate to contact us at [deborah.djon@gmail.com]. We are here to assist you and ensure you have the best experience with our application.

Thank you for choosing our Calendar Application, and we hope it simplifies your event management needs!

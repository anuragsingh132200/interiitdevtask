# InterIIT Tech Meet 13.0: Godown Visualization App

This project is a submission for the InterIIT Tech Meet 13.0 Development Team Selection Task. It is a Tree View Application that visually represents the hierarchy of godowns (warehouses), locations, sub-locations, and items stored within them. The application allows users to navigate the godown structure and view details of selected items.

## Features

*   **Tree View:** A sidebar displays the hierarchical structure of godowns, locations, and items. Users can expand and collapse branches to explore the structure.
*   **Product Display:** Selecting an item displays its details in the main section of the application.
*   **Containerization:** The entire system is dockerized for easy deployment and scalability.

## Bonus Features

*   This project implements the containerization bonus feature.

## Tech Stack

*   **Frontend:** React.js, React Router, FramerMotion, shadcn/ui.
*   **Deployement:** Vercel.
*   **Containerization:** Docker.

## Installation and Setup

1.  **Clone the repository:** `git clone https://github.com/anuragsingh132200/interiitdevtask.git`
2.  **Navigate to the project directory:** `cd interiitdevtask`
3.  **Build the Docker image:** `docker build -t interiitdevtask .`
4.  **Run the Docker container:** `docker run -p 5173:5173 interiitdevtask`

## Usage

1.  Access the application in your web browser at `http://localhost:5173/`.
2.  Use the tree view to navigate the godown structure.
3.  Click on an item to view its details.

# login user id- any email with @gmail.com and password- any string.

## Deployment

The application is deployed on \[vercel.com]. The deployment link is: \[https://react-vite-shadcn-ui-five.vercel.app/].

## Video Demonstration

A video demonstrating the project's features is available at \[https://github.com/anuragsingh132200/interiitdevtask/blob/master/Screencast%20from%202024-10-13%2003-17-14.mp4]

## Contact

For any questions, please contact \[anurag132200@gmail.com].

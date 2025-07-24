# Job Listing Application(Next.js, Tailwind CSS and Typescript)

This project is a fully functional, responsive job listing application built with Next.js and styled with Tailwind CSS. It serves as a practical demonstration of modern web development techniques, including component-based architecture, dynamic routing, and data handling from a static JSON file.

This application was developed as part of a task series designed to enhance skills in building real-world web applications. The primary goal was to transform a Figma design into a pixel-perfect, interactive user interface.

## Features

-   **Dynamic Job Dashboard:** Displays a list of available job opportunities from a central data source.
-   **Detailed Job View:** Clicking on a job card navigates the user to a dedicated page with comprehensive details about the position.
-   **Responsive Design:** The layout is fully responsive, providing an optimal viewing experience on devices of all sizes, from mobile phones to desktops.
-   **Component-Based Architecture:** Built with reusable React components for maintainability and scalability.
-   **Modern Styling:** Styled using the utility-first Tailwind CSS framework for rapid and consistent UI development.
-   **Next.js App Router:** Utilizes the latest Next.js features, including dynamic routing for creating unique pages for each job listing.


## Page Previews

Here is a preview of the main pages of the application.

### 1. Job Listing Dashboard

This is the main landing page, showcasing a list of available job opportunities. Each card provides a summary, including the job title, company, location, and key categories.
<img width="904" height="431" alt="image" src="https://github.com/user-attachments/assets/79991405-b109-46d5-9bdc-c7b88db2920d" />
<img width="905" height="419" alt="image" src="https://github.com/user-attachments/assets/ae063dbe-8960-41d8-9374-a8ff7e65384d" />


### 2. Job Detail Page

When a user clicks on a job card from the dashboard, they are navigated to this detailed view. This page provides an in-depth look at the job, including a full description, responsibilities, ideal candidate traits, and required skills.

<img width="817" height="432" alt="image" src="https://github.com/user-attachments/assets/8123e7f2-169d-4ba4-aacb-fa717bbf25c9" />
<img width="764" height="432" alt="image" src="https://github.com/user-attachments/assets/a2985bfa-9611-497c-9d80-87071369090f" />

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have [Node.js](https://nodejs.org/) (version 18.x or later) and npm installed on your computer.

```bash
# Check your Node.js version
node -v
```

### Installation & Setup

1.  **Clone the repository:**
    Open your terminal and clone this repository to your local machine.
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd YOUR_REPOSITORY_NAME
    ```

3.  **Install dependencies:**
    Use npm to install all the required project dependencies listed in `package.json`.
    ```bash
    npm install
    ```

### Running the Application

Once the installation is complete, you can run the development server.

1.  **Start the development server:**
    ```bash
    npm run dev
    ```

2.  **Open the application in your browser:**
    Open your web browser and navigate to [http://localhost:3000](http://localhost:3000). You should now see the Job Listing Dashboard.




## Project Structure

The project follows the standard Next.js App Router structure:

```
/
├── app/                  # Main application folder
│   ├── /components/      # Reusable React components (JobCard, JobCardDetail, Icons)
│   ├── /jobs/            # Dynamic routing for job details
│   │   └── /[id]/
│   │       └── page.tsx  # The template for the job detail page
│   ├── layout.tsx        # Root layout
│   ├── page.tsx          # Home page (Job Listing Dashboard)
│   └── types.ts          # Centralized TypeScript type definitions
├── data/
│   └── data.json         # Static JSON data for job postings
├── public/               # Static assets (images, fonts)
├── screenshots/          # Contains screenshots for the README
└── README.md             # This file
```

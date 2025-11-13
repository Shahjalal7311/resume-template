### Running the environment

#### Running in local

1. Open the terminal / command prompt in your system
1. Clone the repo
   ```
   git remote add origin https://github.com/Shahjalal7311/resume-template.git
   ```
1. Install the dependencies
   ```
   $ npm install
   ```
1. Run the project
   ```
   $ npm run dev
   ```
1. Visit http://localhost:3007/ on your browser

### Run via Docker

Prequisite: Install [Docker](https://docs.docker.com/engine/install/).

1. Open the terminal / command prompt in your system
1. Clone the repo
   ```
   git remote add origin https://github.com/Shahjalal7311/resume-template.git
   ```
1. Run the below command in the terminal from within the cloned project directory

   ```
   $ docker-compose up -d
   ```


# Resume Builder User Guide

Resume Builder works best on a desktop.

## Building a Resume

1. Select "Editor" in the top pane
1. Select "TEMPLATES" in the top pane and select your desired template
1. Select "COLOURS" in the top pane and select your desired color scheme
1. Update the sections in the right pane with your experience
1. When you're done, 
		- Export your data by selecting "Export" in the top pane. This will generate a JSON file that gets downloaded to your local device. Save this file for later use.
		- Download the resume as a PDF by selecting "DOWNLOAD AS PDF" in the top pane

## Editing a Resume[not working currently stop edit form view end]
1. Select "Editor" in the top pane
1. Select "Import in the top pane". Import the JSON that was generated in the [Building a Resume].


## Running the environment locally or in Docker

Run the environment locally or in Docker by following the instructions at [Running the environment].
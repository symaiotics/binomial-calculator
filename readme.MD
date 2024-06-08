# Binomial Confidence Heatmap
This project visualizes the binomial confidence heatmap using Vue.js and Tailwind CSS. It allows users to interactively change the number of people and the probability, and see the resulting confidence levels.

## Prerequisites
Node.js (https://nodejs.org/)
npm (Node Package Manager, comes with Node.js)
Getting Started
1. Clone the Repository
First, clone the repository to your local machine using:

git clone <repository-url>
Replace <repository-url> with the actual URL of your repository.

2. Navigate to the Project Directory
Change your directory to the project folder:

cd <project-directory>
Replace <project-directory> with the actual name of the directory you cloned.

3. Install http-server
http-server is a simple, zero-configuration command-line HTTP server. Install it globally using npm:

npm install -g http-server
4. Launch the Project
To serve the project locally, you need to navigate to the directory containing your heatmap.html file and run http-server:

http-server
By default, http-server serves the files on http://localhost:8080. You can specify a different port if needed:

http-server -p 3000
5. View in Browser
Open your web browser and navigate to:

http://localhost:8080/heatmap.html
Replace 8080 with the port number you specified if you used a different one.

Project Structure
heatmap.html: The main HTML file that includes the Vue.js and Tailwind CSS setup, and the entire application logic.
Usage
Adjust the number of people using the range slider labeled "Number of People".
Adjust the probability using the range slider labeled "Probability".
The calculated confidence will be displayed below the sliders.
The heatmap will update based on the selected number of people and probability, highlighting the corresponding cell.
Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Vue.js
Tailwind CSS
http-server
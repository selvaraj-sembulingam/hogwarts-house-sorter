# 🧙‍♂️ Hogwarts House Sorter

Welcome to the Hogwarts House Sorter! This is a simple, whimsical web application that uses a short quiz and an optional photo upload to determine which of the four Hogwarts houses you belong to.

## Features

* **Interactive Quiz:** Answer three magical questions to find your true house.

* **Photo Upload:** See your portrait magically framed in your house's colors.

* **Dynamic Results:** The app dynamically displays your house and a corresponding image border.

* **Local Sorting:** The entire sorting process happens directly in your browser, no server connection required for the quiz.

## Technical Details

This is a single-page, front-end application built with:

* **HTML5:** For the structure of the web page.

* **CSS3:** For styling, animations, and responsive design. This includes custom fonts and color themes to create a magical atmosphere.

* **JavaScript:** For handling user input, calculating the house based on your answers, and dynamically updating the page content.

## Running Locally

To run this application, you will need a simple web server. This is necessary for some browsers to correctly handle the local image file upload. The easiest way to do this is using Python's built-in server.

1.  **Save the file:** Make sure you have saved the `hogwarts-sorter.html` file to your computer.

2.  **Open your terminal:**

    * On Windows, search for "Command Prompt" or "PowerShell".

    * On macOS or Linux, search for "Terminal".

3.  **Navigate to the file's directory:** Use the `cd` (change directory) command to go to the folder where you saved the HTML file. For example, if it's in your Downloads folder, you would type:

    ```
    cd Downloads
    ```

4.  **Start the server:** Run the following command in your terminal. This will start a local web server.

    ```
    python -m http.server
    ```

5.  **Access the app:** Open your web browser and go to the following address:

    ```
    http://localhost:8000
    ```

    You should now see the Hogwarts House Sorter app ready to go!

<img width="830" height="820" alt="image" src="https://github.com/user-attachments/assets/60f93704-d947-4c7b-8ebb-a8e52203d434" />

## Notes

* The server will run as long as your terminal window is open. To stop the server, press `Ctrl + C` in the terminal.

* The quiz logic is based on a simple scoring system, which randomly sorts you into one of the four houses if there is a tie.

* This application is designed for entertainment and does not use any advanced machine learning or AI to sort you.

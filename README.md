# RelTransWebApp


**Prerequisites**

-   **Node.js and npm:**  You'll need Node.js (a JavaScript runtime environment) and npm (Node.js Package Manager) installed. Get them from the official website:  [https://nodejs.org/](https://nodejs.org/)  (The installer includes both).

**Step-by-Step Guide**

1.  **Install Visual Studio Code**
    
    -   **Download:**  Download the VS Code installer from the official website:  [https://code.visualstudio.com/](https://code.visualstudio.com/)
    -   **Run the Installer:**  Follow the on-screen prompts. Installation is straightforward for most platforms.
2.  **Install Angular CLI (Globally)**
    
    -   **Open Terminal/Command Prompt:**  Open a command-line interface (Terminal on macOS/Linux or Command Prompt on Windows).
    -   **Install:**  Run the following command:
        
        Command
        
        ```
        npm install -g @angular/cli  
        
        ```
        
3.  **Clone the Angular Project**
    
    -   **Git:**  Make sure you have Git installed ([https://git-scm.com/downloads](https://git-scm.com/downloads)).
    -   **Navigate to the desired directory:**  In your terminal, use the  `cd`  command to navigate to where you want to clone the project.
    -   **Clone:**  Run the following command, replacing the URL with the actual Git repository URL:
        
        Command
        
        ```
        git clone https://github.com/aluwanineth/RelTransWebApp.git 
        
        ```
        
        
        
4.  **Install Project Dependencies (`npm i`)**
    
    -   **Navigate to the Project Folder:**  In your terminal, use  `cd`  to change the directory to the root of the cloned project.
    -   **Install Dependencies**: Run the following command:
        
        Command
        
        ```
        npm i  
        
        ```
        
      
   
        This will download all the necessary packages specified in the project's  `package.json`  file.

**You're all set!** Now you can open the cloned project folder in Visual Studio Code and start working on your Angular application.

navigate to route folder and run below command, it will run application and open it in new default browser http://localhost:4200

 Command
        
        ```
        npm run start   
        
        ```

**Additional Tips**

-   **Verify Installations:**  After each installation, check the version to ensure everything was successful (e.g.,  `ng --version`  for Angular CLI).

**Project Structure**
**Root Directory**

-   **.vscode**  (likely): This folder indicates the project is set up for Visual Studio Code and might contain configuration files for the editor (extensions, shortcuts, tasks).
-   **src**  : This folder typically contains the source code of the Angular application.

**Source Code Folders**

-   **app**  : This folder likely contains the core application logic and components of the Angular application.
    -   **_helpers**  : This folder's purpose is not entirely clear from the name, but it might house helper functions, utility classes, or generic components reused throughout the application.
    -   **app-routing.module.ts**  : This file likely defines the routing configuration for the application, specifying how the application responds to different URL paths.
    -   **app.component.html**  : This file contains the HTML template for the root component of the application.
    -   **app.component.sass**  (or .scss) : This file contains the styles written in Sass (or SCSS) for the root component.
    -   **app.component.spec.ts**  : This file likely contains unit tests for the root component (`app.component.ts`).
    -   **app.component.ts**  : This file likely contains the TypeScript code for the root component of the application. It controls the component's view and behavior.
    -   **app.module.ts**  : This file is the main module of the Angular application. It defines the components, directives, pipes, and services used in the application.
    -   **components**  : This folder likely contains various reusable UI components used throughout the application.
        -   **change-password-form**  : This folder likely contains components related to a change password form functionality.
        -   _change-password-form.component.html_  : This file contains the HTML template for the change password form component.
        -   _change-password-form.component.sass_  (or .scss) : This file contains the styles for the change password form component.
        -   _change-password-form.component.spec.ts_  : This file likely contains unit tests for the change password form component.
        -   _change-password-form.component.ts_  : This file likely contains the TypeScript code for the change password form component, controlling its behavior and interaction with other parts of the application.
        -   ... ( more component folders for customer ga etc)
    -   **directives**  : This folder contains custom directives that can be used to manipulate the DOM or add functionalities to HTML elements.
    -   **models**  : This folder contains model classes representing the data structures used by the application.
    -   **pipes**  : This folder contains custom pipes for data transformation or formatting within the application's templates.
    -   **services**  : This folder contains service classes that encapsulate application logic or interact with external systems (data access, authentication).
-   **shared**  : This folder contains components, directives, pipes, or services that are shared across multiple features or modules within the application.

**Other Files**

-   **favicon.ico**  : This file defines the small icon displayed in the browser tab or address bar.
-   **index.html**  : This is the main HTML file that bootstraps the Angular application in the browser.
-   **main.ts**  : This file is the entry point of the Angular application. It bootstraps the main  `AppModule`  and starts the application.
-   **polyfills.ts**  : This file includes polyfills for functionalities that might not be natively supported by older browsers.
-   **styles.sass**  (or .scss) : This file contains global styles applied throughout the application.
-   **tsconfig.app.json**  : This file is a configuration file for the TypeScript compiler specific to the application code in the  `src`  folder.
-   **tsconfig.spec.json**  : This file is a configuration file for the TypeScript compiler specific to the test code.
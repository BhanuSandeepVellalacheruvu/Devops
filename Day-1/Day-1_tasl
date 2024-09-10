# Installing Medusa CLI and Setting Up a New Medusa Store

The Medusa CLI is a tool that helps developers create and manage Medusa.js e-commerce projects. Below is a detailed guide on how to install the Medusa CLI and set up a new project.

## Step 1: Verify Node.js Installation

To check if Node.js is installed on your system, use the following command:

```bash
node -v


Step 2: Install Yarn
Medusa uses Yarn as its package manager. If you don’t have Yarn installed, you can install it using Homebrew:

bash
Copy code
brew install yarn
Verify the installation by checking Yarn's version:

bash
Copy code
yarn -v
Step 3: Install Medusa CLI Globally
Once Node.js and Yarn are installed, you can install Medusa CLI globally using Yarn:

bash
Copy code
yarn global add @medusajs/medusa-cli
This command installs Medusa CLI globally on your system, making it accessible from any directory.

Step 4: Verify Medusa CLI Installation
To ensure the CLI was installed correctly, check its version:

bash
Copy code
medusa --version
Step 5: Create a New Medusa Store
Now that Medusa CLI is installed, you can create a new Medusa store project:

bash
Copy code
medusa new my-medusa-store
If you see an error indicating that the directory already exists, you can delete it using the following command:

bash
Copy code
sudo rm -r my-medusa-store
Then, rerun the medusa new command to set up your new store.

Step 6: Install Project Dependencies
Medusa will automatically install all required dependencies for your project. If you encounter warnings or errors related to deprecated packages, they can be ignored for now, but consider running:

bash
Copy code
npm audit fix
This will fix non-breaking vulnerabilities, and you can run the following to fix all issues:

bash
Copy code
npm audit fix --force
Step 7: Set Up the Database
Medusa will prompt you to set up a PostgreSQL database with credentials. You can choose to continue with the suggested credentials:

bash
Copy code
Will attempt to setup Postgres database "medusa-db-dr0hp" with credentials:
  user: bhanusandeepvellalacheruvu
  password: ***
  port: 5432
  host: localhost
Do you wish to continue with these credentials?
You can proceed with these or modify them according to your needs.

Step 8: Start the Medusa Project
After the database setup is complete, you can navigate to your project directory and start the development server:

bash
Copy code
cd my-medusa-store
medusa develop
This command starts your Medusa store, and you can begin building and managing your e-commerce project.

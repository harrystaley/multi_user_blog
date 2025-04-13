# Multi User Blog

## Project Overview

The Multi User Blog is a collaborative blogging platform, developed as a part of the Udacity Full Stack Nanodegree program. This project is designed to support multiple users who can create, edit, and share blog posts. It also allows users to comment on each other's posts, fostering an interactive community environment.

This application is built using Python and leverages Google App Engine, a robust platform for developing and hosting web applications. The project structure is organized as follows:

- `app.yaml`: Configuration file for Google App Engine.
- `blog.py`: Main Python script that handles routing and controllers.
- `models/`: Directory containing data models for Google Datastore entities.
- `templates/`: Folder for HTML templates for rendering views.
- `static/`: Contains CSS files for styling the website.

## Setup and Installation

### Prerequisites

To run this project, you'll need:

- Python 3.7 or above
- Google Cloud SDK
- A Google Cloud Platform account

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/multi_user_blog.git
   cd multi_user_blog
   ```

2. **Install Dependencies**

   It's recommended to create a virtual environment:

   ```bash
   python -m venv myvenv
   source myvenv/bin/activate  # On Windows use `myvenv\Scripts\activate`
   ```

   Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Local Development Server**

   Start the local development server provided by Google App Engine:

   ```bash
   dev_appserver.py app.yaml
   ```

   The app should now be running on `http://localhost:8080`.

4. **Deploying to Google App Engine**

   To deploy the application to Google App Engine, run:

   ```bash
   gcloud app deploy
   ```

   Follow the prompts to select your project and configure its settings.

## Usage

After setting up the project, you can access the blog at `http://localhost:8080` or through the link provided by Google App Engine after deployment.

- **Creating a Post**: Sign up and log in to create a blog post.
- **Viewing Posts**: Browse posts created by other users.
- **Commenting**: Comment on posts to engage with other users.

## Contributing

Contributions to the Multi User Blog are welcome!

1. **Fork the Repository** - Start by forking the repository to your GitHub account.
2. **Clone the Forked Repository** - Clone the repository to your local machine.
3. **Create a New Branch** - Create a branch for your modifications.
4. **Make Changes and Test** - Make your changes and ensure they are thoroughly tested.
5. **Submit a Pull Request** - Submit a pull request to the original repository for review.

Before contributing, please also check for any specific contribution guidelines posted by the repository owner.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
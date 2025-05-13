# 📌 markdown-blog-platform

A lightweight, customizable markdown-based blogging platform that allows users to write, manage, and publish blog posts using markdown files.

---

## 🔧 Tech Stack

- Python 3.x
- Flask
- Jinja2
- Markdown
- HTML/CSS
- JSON

---

## 🧑‍💻 Contributors

| Name  | GitHub                                         | Role                     |
| ----- | ---------------------------------------------- | ------------------------ |
| Sneha | [@Snehashri25](https://github.com/Snehashri25) | Project Lead & Developer |

---

## 🚀 Setup Instructions

````bash
git clone https://github.com/Snehashri25/markdown-blog-platform.git
cd markdown-blog-platform

# Create virtual environment
python -m venv venv
source venv/Scripts/activate  # For Git Bash on Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py

## 🛠️ How to Contribute

1. Fork the repository by clicking on the "Fork" button at the top-right of the repository page.
2. Clone your forked repository to your local machine:

    ```bash
    git clone https://github.com/your-username/markdown-blog-platform.git
    ```

3. Navigate to the project directory:

    ```bash
    cd markdown-blog-platform
    ```

4. Create a new branch for your feature or bugfix:

    ```bash
    git checkout -b feature/your-feature
    ```

5. Make your changes and commit them:

    ```bash
    git commit -m "Added feature xyz"
    ```

6. Push to your branch on GitHub:

    ```bash
    git push origin feature/your-feature
    ```

7. Go to the original repository on GitHub and click on the "Pull Requests" tab.
8. Click on the "New Pull Request" button.
9. Select the branch you just pushed from your fork and the base branch of the original repository (usually `main`).
10. Add a descriptive title and comment for your pull request, then click "Create Pull Request".

Once your PR is reviewed, it will be merged into the main repository.

markdown-blog-platform/
├── blog_posts/          # Stores markdown files for blog posts
├── templates/           # HTML templates for rendering blog posts
├── static/              # Static files (CSS, JS, Images)
│   └── themes/          # Theme-related static files
├── output/              # Generated HTML output from markdown files
├── assets/              # Additional assets (fonts, icons)
├── main.py              # Main entry point for the app
├── utils.py             # Utility functions
├── config.json          # Configuration file
├── README.md            # Project documentation

````

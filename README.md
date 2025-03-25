# jekyll-theme
Hoverkraft Jekyll Theme

## How to Use the Hoverkraft Jekyll Theme with GitHub Pages

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Jekyll](https://jekyllrb.com/docs/installation/)

### Installation

1. **Fork and Clone the Repository**

   Fork the repository on GitHub and clone it to your local machine.

   ```sh
   git clone https://github.com/hoverkraft-tech/jekyll-theme.git
   cd jekyll-theme
   ```

2. **Install Dependencies**

   Install the required dependencies using Bundler.

   ```sh
   bundle install
   ```

3. **Run the Jekyll Server**

   Start the Jekyll server to preview the theme locally.

   ```sh
   bundle exec jekyll serve
   ```

   Open your web browser and navigate to `http://localhost:4000` to see the theme in action.

### Configuration

You can customize the theme by modifying the `_config.yml` file. Here are some of the key settings you can change:

- `title`: The title of your site.
- `description`: A brief description of your site.
- `url`: The base URL of your site.
- `author`: The author of the site.

### Deployment

To deploy your Jekyll site with the Hoverkraft theme to GitHub Pages, follow these steps:

1. **Create a GitHub Repository**

   Create a new repository on GitHub to host your Jekyll site.

2. **Push Your Site to GitHub**

   Push the contents of your Jekyll site to the GitHub repository.

   ```sh
   git remote add origin https://github.com/your-username/your-repo.git
   git branch -M main
   git push -u origin main
   ```

3. **Configure GitHub Pages**

   Go to the repository settings on GitHub, scroll down to the "GitHub Pages" section, and select the branch you want to use for GitHub Pages (e.g., `main`).

   Your site should now be live at `https://your-username.github.io/your-repo`.

### Customization

You can further customize the theme by editing the following files:

- `_layouts/default.html`: The default layout for your site.
- `_includes/header.html`: The header section of your site.
- `_includes/footer.html`: The footer section of your site.
- `assets/css/main.scss`: The main SCSS file for styling your site.
- `assets/js/main.js`: The main JavaScript file for adding functionality to your site.

### License

This theme is open source and available under the [MIT License](LICENSE).

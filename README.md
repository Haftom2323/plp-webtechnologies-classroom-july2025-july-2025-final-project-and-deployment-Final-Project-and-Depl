# 🚀 PLP Portfolio Website

A responsive, multi-page portfolio website built with HTML5, CSS3, and JavaScript. This project showcases my skills, projects, and contact information as part of the Power Learn Project (PLP) curriculum.

## 🏠 Pages

- **Home**: Introduction and featured projects
- **About**: Detailed information about me and my skills
- **Projects**: Showcase of my work with descriptions and technologies used
- **Contact**: Contact form and information with interactive map

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts

## 🚀 Deployment

### Option 1: Deploy to GitHub Pages

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com/new)
   - Name your repository `username.github.io` (replace 'username' with your GitHub username)
   - Make sure it's set to Public
   - Click "Create repository"

2. **Push Your Code**
   ```bash
   # Initialize git repository (if not already done)
   git init
   
   # Add all files
   git add .
   
   # Commit changes
   git commit -m "Initial commit"
   
   # Add the remote repository
   git remote add origin https://github.com/username/username.github.io.git
   
   # Push to GitHub
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings"
   - In the left sidebar, click on "Pages"
   - Under "Source", select the `main` branch
   - Click "Save"
   - Your site will be live at `https://username.github.io` (it may take a few minutes)

### Option 2: Deploy to Vercel

1. **Create a Vercel Account**
   - Go to [Vercel](https://vercel.com/signup)
   - Sign up with your GitHub account

2. **Import Your Project**
   - Click "Add New..." → "Project"
   - Import your GitHub repository
   - Vercel will automatically detect it's a static site
   - Click "Deploy"

3. **Configure Domain (Optional)**
   - After deployment, go to your project in Vercel
   - Click on "Settings" → "Domains"
   - Add a custom domain if desired

4. **Your site will be live at:** `https://your-project-name.vercel.app`

## 🔍 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/username/portfolio-website.git
   cd portfolio-website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python's built-in server
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000` in your browser.

## 📝 Customization

1. **Update Personal Information**
   - Edit the content in HTML files
   - Update images in the `assets` folder
   - Modify colors and styles in `css/styles.css`

2. **Update Projects**
   - Edit the projects in `projects.html`
   - Add/remove project cards as needed

3. **Update Contact Information**
   - Update the contact form action in `contact.html`
   - Update the map location in `contact.html`

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px and above)
- Laptops (992px - 1199px)
- Tablets (768px - 991px)
- Mobile devices (up to 767px)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Power Learn Project](https://powerlearnproject.org/) for the opportunity
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography

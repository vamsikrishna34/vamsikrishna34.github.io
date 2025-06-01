# Portfolio Website Deployment Instructions

## Overview
This document provides instructions for deploying your React/Tailwind portfolio website. The site has been built and optimized for production, ready to be hosted on any static site hosting service.

## Production Build
The production-ready files are located in the `dist` directory. These files are optimized for performance and ready to be deployed.

## Deployment Options

### Option 1: GitHub Pages
GitHub Pages is a free hosting service that's perfect for portfolio websites.

1. Create a new GitHub repository (or use your existing username.github.io repository)
2. Push the contents of the `dist` folder to the repository
3. Enable GitHub Pages in the repository settings
   - Go to Settings > Pages
   - Select the branch containing your dist files (usually main or master)
   - Save the settings

Your site will be available at `https://yourusername.github.io/repository-name` or `https://yourusername.github.io` if using the special username.github.io repository.

### Option 2: Netlify
Netlify offers free hosting with a simple drag-and-drop deployment:

1. Go to [Netlify](https://www.netlify.com/) and create an account or log in
2. Drag and drop the `dist` folder onto the Netlify dashboard
3. Netlify will automatically deploy your site and provide a URL
4. You can set up a custom domain in the Netlify settings if desired

### Option 3: Vercel
Vercel is another excellent platform for hosting static sites:

1. Go to [Vercel](https://vercel.com/) and create an account or log in
2. Create a new project and import your GitHub repository
3. Set the output directory to `dist`
4. Deploy the site

## Custom Domain Setup
If you have a custom domain, you can configure it with any of the hosting options above:

1. Purchase a domain from a domain registrar (e.g., Namecheap, GoDaddy)
2. Follow the hosting provider's instructions for adding a custom domain
3. Update your domain's DNS settings to point to your hosting provider

## Updating Your Site
To update your site after making changes:

1. Make your changes to the source code
2. Run `pnpm run build` to generate a new production build
3. Upload the new contents of the `dist` folder to your hosting provider

## Resume File
Don't forget to upload your resume PDF file to the hosting service. The site is configured to link to `/resume.pdf` in the root directory.

## Testing After Deployment
After deploying, verify that:
- All pages load correctly
- Navigation works properly
- Contact form functions as expected (if using a form handling service)
- The site is responsive on different devices
- All links to external resources work

## Need Help?
If you encounter any issues during deployment, most hosting providers offer comprehensive documentation and support:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Netlify Documentation](https://docs.netlify.com/)
- [Vercel Documentation](https://vercel.com/docs)

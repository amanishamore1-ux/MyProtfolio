# Deploy the portfolio

Upload the complete contents of `Anisha-More-Portfolio`: `index.html`, the other HTML pages, the entire `assets` folder and the documentation. Do not upload just the ZIP, and do not add an extra enclosing folder when the hosting service expects `index.html` at the root.

## GitHub Pages

1. Create or open a repository in your GitHub account.
2. Upload the files and folders inside `Anisha-More-Portfolio` to the repository root.
3. In Settings → Pages, choose Deploy from a branch, select your publishing branch and `/ (root)`, and save.
4. Open the published address after deployment. Relative paths support both an account site and a repository site.

## Netlify

For manual deployment, drag the extracted `Anisha-More-Portfolio` folder onto Netlify's deployment area. For repository deployment, use no build command and set the publish directory to `.` when the project files are at the repository root.

## Vercel

Import a repository containing the complete project. Choose Other as the framework preset, use the repository root as the project root, leave the build command empty and serve the root directory `.`. No environment variables or backend are required.

## After publishing

Check every page, the local resume PDF, project dialogs, social links, all four themes and music. The site intentionally has no guessed canonical domain or portfolio URL. For social-platform preview compatibility, change `og:image` and `twitter:image` in the five portfolio pages to the absolute URL of the supplied portrait on your actual published domain, and add the appropriate canonical URL if desired.

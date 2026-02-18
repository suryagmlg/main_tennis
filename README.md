# Tennis Americano Score by SG

A beautiful and modern web application for managing Tennis Americano tournaments.

## Features

- 🎾 Create and manage multiple tournaments
- 👥 Player management with gender tracking
- 🏆 Automatic leaderboard calculation
- 🎲 Smart round generation (Classic & Grading modes)
- 📊 Real-time scoring and statistics
- 💾 Local storage persistence
- 📱 Responsive mobile-friendly design

## Deployment

### Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel
   ```

3. **Follow the prompts**:
   - Set up and deploy: Yes
   - Which scope: Select your account
   - Link to existing project: No
   - Project name: (press enter to use default)
   - In which directory is your code located: ./
   - Want to override settings: No

4. **Production deployment**:
   ```bash
   vercel --prod
   ```

### Manual Deployment

You can also deploy by:
1. Pushing this repository to GitHub
2. Importing the repository in Vercel dashboard
3. Vercel will automatically detect and deploy the static site

## Local Development

Simply open `main_tennis.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000`

## Technology Stack

- Pure HTML/CSS/JavaScript (no dependencies)
- Local Storage for data persistence
- Modern CSS with animations and gradients
- Responsive design

## Created By

Surya G. · 2026 · Beta Version v1.0



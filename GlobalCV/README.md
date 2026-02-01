# GlobalCV Deployment Guide

## 🚀 Quick Deploy to Vercel

### Files in this folder:
- `globalcv-site.html` - Main marketing website
- `cv-builder.html` - CV builder application
- `vercel.json` - Vercel configuration
- `package.json` - Project metadata

### Deployment Steps:

1. **Sign up for Vercel**
   - Go to https://vercel.com
   - Sign up with GitHub (recommended) or email

2. **Deploy your site**
   
   **Option 1: Drag & Drop (Easiest)**
   - Go to https://vercel.com/new
   - Drag the entire folder onto the page
   - Click "Deploy"
   - Done! Your site will be live at `your-project.vercel.app`

   **Option 2: Vercel CLI**
   ```bash
   npm install -g vercel
   cd globalcv
   vercel
   ```

3. **Custom Domain (Optional)**
   - In Vercel dashboard, go to your project
   - Click "Settings" → "Domains"
   - Add your custom domain (e.g., globalcv.com)
   - Follow DNS instructions

### URLs after deployment:
- Homepage: `https://your-project.vercel.app/`
- CV Builder: `https://your-project.vercel.app/builder`

### Making Updates:
1. Edit your HTML files locally
2. Drag the folder to Vercel again (it will update)
3. Or use `vercel --prod` if using CLI

---

## 📝 Notes

- The site is completely static (no backend needed)
- Free hosting on Vercel forever
- Automatic HTTPS
- Global CDN for fast loading worldwide
- Perfect for your MVP launch!

## 🔧 Future Enhancements

When you're ready to add:
- User authentication → Add Supabase
- Database → Already planned (Supabase)
- Payment processing → Stripe integration
- AI features → Claude API (already planned)

---

Built with ❤️ for GlobalCV

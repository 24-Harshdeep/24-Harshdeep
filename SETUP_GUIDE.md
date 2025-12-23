# 🔧 How to Get Your Real GitHub Data

Follow these steps to replace placeholder data with your actual GitHub information:

---

## 1️⃣ Replace Username in README

Open `Readme.md` and find **all instances** of `HARSHDEEP24`. Replace with your GitHub username.

### Quick find & replace:
```bash
# In VS Code: Press Ctrl+H (or Cmd+H on Mac)
# Find: HARSHDEEP24
# Replace with: YOUR_GITHUB_USERNAME
```

Or use command line:
```bash
sed -i 's/HARSHDEEP24/YOUR_GITHUB_USERNAME/g' Readme.md
```

---

## 2️⃣ Update Social Links

### LinkedIn
1. Go to your LinkedIn profile
2. Copy the URL: `https://linkedin.com/in/your-profile-name`
3. Replace in README: `https://linkedin.com/in/your-linkedin`

### Discord
1. Open Discord → User Settings → Advanced → Enable Developer Mode
2. Right-click your profile → Copy User ID
3. Replace in README: `https://discord.com/users/your-discord-id`
4. Or use: `https://discord.gg/your-server-invite` for server invite

### Email
Replace `youremail@gmail.com` with your actual email

### Portfolio (optional)
Replace `https://your-portfolio.com` with your portfolio URL, or remove the badge if you don't have one

---

## 3️⃣ GitHub Stats Services (All Auto-Update!)

The following services automatically fetch your real GitHub data once you replace the username:

### GitHub Readme Stats
- **Stats Card**: `https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME`
- **Language Stats**: `https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME`
- Docs: https://github.com/anuraghazra/github-readme-stats

### GitHub Streak Stats
- **Streak Card**: `https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME`
- Docs: https://github.com/DenverCoder1/github-readme-streak-stats

### Activity Graph
- **Contribution Graph**: `https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME`
- Docs: https://github.com/Ashutosh00710/github-readme-activity-graph

### Profile Trophy
- **Trophies**: `https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME`
- Docs: https://github.com/ryo-ma/github-profile-trophy

### Profile Views Counter
- **Views**: `https://komarev.com/ghpvc/?username=YOUR_USERNAME`
- Auto-increments on each profile view

---

## 4️⃣ Optional: WakaTime Stats (Coding Activity)

To show your weekly coding activity:

1. Create account at https://wakatime.com
2. Install WakaTime plugin in VS Code/IDE
3. Get your username from WakaTime dashboard
4. The stats will auto-populate in your README

If you don't use WakaTime, **remove this line** from README:
```markdown
<img src="https://github-readme-stats.vercel.app/api/wakatime?username=HARSHDEEP24&theme=tokyonight&hide_border=true&layout=compact" width="49%"/>
```

---

## 5️⃣ Update Project Links

In the **Featured Projects** table:

1. Replace GitHub repo URLs with your actual repository links
2. Add live demo links (Vercel, Netlify, etc.) or remove `[Demo](#)` if not deployed
3. Update project descriptions to match your actual projects

Example:
```markdown
| 🤖 **Your Project** | Your description | Your tech | [Code](https://github.com/YOUR_USERNAME/repo) • [Demo](https://your-app.vercel.app) |
```

---

## 6️⃣ Verify Images Are Loading

After making changes:

1. Commit and push to GitHub:
   ```bash
   git add Readme.md
   git commit -m "Update README with real GitHub data"
   git push origin main
   ```

2. Go to your GitHub profile page: `https://github.com/YOUR_USERNAME`
3. Check if all badges, stats, and graphs are loading correctly

### Common issues:
- **Images not showing?** → Check username spelling (case-sensitive!)
- **Stats showing 0?** → Services need a few minutes to fetch data first time
- **404 errors?** → Verify the service URL format matches the docs

---

## 7️⃣ Customize Themes

All services support color themes! Popular ones:

- `theme=radical`
- `theme=tokyonight` (currently used)
- `theme=dracula`
- `theme=github_dark`
- `theme=monokai`

Change `theme=tokyonight` to your preferred theme in each URL.

---

## 🎨 Pro Tips

1. **Keep it updated**: The stats auto-update, but keep project links current
2. **Test locally**: Use VS Code preview (Ctrl+Shift+V) to check markdown formatting
3. **Mobile-friendly**: Test on mobile by viewing your GitHub profile on phone
4. **Add screenshots**: Create `docs/images/` folder and add project screenshots
5. **Pin repositories**: Go to GitHub profile → Customize pins → Select best 6 repos

---

## ✅ Checklist

- [ ] Replace `HARSHDEEP24` with my GitHub username
- [ ] Update LinkedIn URL
- [ ] Update Discord link
- [ ] Update email address
- [ ] Update/remove portfolio link
- [ ] Update project repository links
- [ ] Add real demo links or remove placeholders
- [ ] Remove WakaTime stats if not using
- [ ] Commit and push changes
- [ ] Verify all images load on GitHub profile

---

**Need help?** Check the documentation links above or open an issue on the respective service repos!

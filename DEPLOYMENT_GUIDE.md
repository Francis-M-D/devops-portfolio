# 🚀 DevOps Portfolio - Deployment Guide

## Quick Start (5 minutes)

Your portfolio is ready to deploy! Follow these steps to get it live on GitHub Pages.

---

## Step 1: Create a New Repository on GitHub

1. Go to **github.com/new**
2. Create a repository named: **`devops-portfolio`**
3. Initialize with **empty** (no README, .gitignore, or license)
4. Click **Create repository**

---

## Step 2: Clone the Repository Locally

```bash
git clone https://github.com/YOUR_USERNAME/devops-portfolio.git
cd devops-portfolio
```

Replace `YOUR_USERNAME` with your actual GitHub username.

---

## Step 3: Add Your Portfolio Files

Place these files in the repository root:

```
devops-portfolio/
├── index.html              # Main portfolio page
├── architecture.html       # Architecture diagrams
└── README.md              # Portfolio documentation
```

---

## Step 4: Create a README.md

Create `README.md` with this content:

```markdown
# DevOps Portfolio - Maria Francis D

## 🎯 About This Portfolio

A professional DevOps portfolio showcasing real-world CI/CD pipelines, cloud infrastructure automation, and containerized deployments.

### 📋 Featured Projects

#### 1. **MindTrack CI/CD Pipeline**
- **Tech Stack**: AWS CodePipeline, CodeBuild, Docker, Amazon ECR, Kubernetes (EKS)
- **Achievement**: 40% reduction in deployment time
- **Repository**: [github.com/Francis-M-D/DevOps_Project_1_MindTrack](https://github.com/Francis-M-D/DevOps_Project_1_MindTrack)

#### 2. **TrendStore CI/CD Pipeline**
- **Tech Stack**: Jenkins, Terraform, Docker, Kubernetes, Prometheus, Grafana
- **Achievement**: 50% infrastructure setup time reduction
- **Repository**: [github.com/Francis-M-D/DevOps_Project_2_TrendStore](https://github.com/Francis-M-D/DevOps_Project_2_TrendStore)

#### 3. **React Application Deployment Pipeline**
- **Tech Stack**: Jenkins, Docker, Terraform, Ansible, AWS EC2
- **Achievement**: 60% reduction in manual deployment effort
- **Repository**: [github.com/Francis-M-D/DevOps_Project_3_Reactjs_E-commerce_Application](https://github.com/Francis-M-D/DevOps_Project_3_Reactjs_E-commerce_Application)

### 🔧 Technical Skills

- **Cloud**: AWS (EC2, EKS, S3, IAM, VPC, CloudWatch, ECR, CodePipeline, CodeBuild)
- **Containers**: Docker, Kubernetes, Amazon EKS
- **CI/CD**: Jenkins, AWS CodePipeline, AWS CodeBuild
- **IaC**: Terraform, Ansible
- **Monitoring**: Prometheus, Grafana, CloudWatch
- **Infrastructure**: Linux, Windows Server, VMware, Nutanix

### 💼 Professional Experience

**DevOps Engineer** - HCL Technologies (January 2024 - Present)
- Managed 100+ virtual machines across VMware and Nutanix environments
- Achieved 99.9% system uptime
- Automated routine tasks, reducing manual effort by ~25%
- Resolved 20+ incidents per week within SLA timelines

**Software Developer** - HCL Technologies (August 2022 - December 2023)
- Developed backend applications using Python and Java
- Improved module efficiency by ~20%
- Collaborated in SDLC processes

### 📚 Certifications

- AWS Cloud and DevOps Fundamentals
- CCNA
- MCSA
- Red Hat Partner Program (Premier)

### 📞 Contact

- **Email**: francis2882001@gmail.com
- **LinkedIn**: [maria-francis-d-987ba128b](https://linkedin.com/in/maria-francis-d-987ba128b)
- **GitHub**: [Francis-M-D](https://github.com/Francis-M-D)
- **Phone**: +91 6369135156

---

## 🌐 Portfolio Links

- **Live Portfolio**: [https://YOUR_USERNAME.github.io/devops-portfolio](https://github.github.io/devops-portfolio)
- **Architecture Diagrams**: [https://YOUR_USERNAME.github.io/devops-portfolio/architecture.html](https://github.github.io/devops-portfolio/architecture.html)

---

## 📝 License

© 2025 Maria Francis D. All rights reserved.
```

---

## Step 5: Push to GitHub

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit: DevOps portfolio with projects and diagrams"

# Push to GitHub
git push -u origin main
```

---

## Step 6: Enable GitHub Pages

1. Go to your repository settings: **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select branch: **main** and folder: **/ (root)**
4. Click **Save**

Your portfolio will be live at: `https://YOUR_USERNAME.github.io/devops-portfolio`

---

## ✅ Verification Checklist

After deployment, verify:

- [ ] Portfolio homepage loads correctly
- [ ] All navigation links work
- [ ] Projects section displays all 3 projects
- [ ] Architecture diagrams render properly
- [ ] Contact links are clickable
- [ ] Responsive design works on mobile
- [ ] GitHub links point to correct repositories

---

## 🎨 Customization Tips

### Update Personal Information

Edit `index.html` and replace:
- `Maria Francis D` with your name
- Email, phone, LinkedIn, GitHub links with your details
- Project descriptions with your achievements
- Tech stack tags with your technologies

### Modify Colors

In `index.html`, change CSS variables in the `:root` section:

```css
:root {
    --primary: #0f172a;           /* Dark background */
    --secondary: #1e293b;         /* Card background */
    --accent: #3b82f6;            /* Primary color (blue) */
    --accent-bright: #60a5fa;     /* Light blue */
    --text-primary: #f1f5f9;      /* Text color */
    --text-secondary: #cbd5e1;    /* Secondary text */
}
```

### Add More Projects

1. Copy a project card in the `projects-grid` section
2. Update title, description, tech tags, features, and GitHub link
3. Save and push changes

---

## 🔗 Recommended Next Steps

### 1. Add Screenshots to Projects

Create an `/assets` folder and add project screenshots:

```html
<img src="assets/project-screenshot.png" alt="Project screenshot" style="max-width: 100%; margin-top: 1rem; border-radius: 0.5rem;">
```

### 2. Create Individual Project Pages

Create separate HTML files for each project with detailed case studies:
- `project-1-mindtrack.html`
- `project-2-trendstore.html`
- `project-3-react-app.html`

### 3. Add Blog Section

Create a `/blog` folder with markdown files documenting your DevOps learnings.

### 4. Integrate Analytics

Add Google Analytics or Plausible to track visitors:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_GA_ID');
</script>
```

### 5. Set up Custom Domain

1. Purchase a domain (Namecheap, GoDaddy, etc.)
2. In repository settings, add custom domain under **Pages**
3. Update DNS records to point to GitHub Pages

---

## 📊 Portfolio Performance Tips

1. **Mobile Responsive**: Already optimized! Check on all devices
2. **SEO Optimized**: Add meta tags for better search visibility
3. **Fast Loading**: HTML/CSS is lightweight - loads instantly
4. **Accessibility**: Uses semantic HTML and ARIA labels

---

## 🐛 Troubleshooting

### Portfolio not showing up?
- Check GitHub Pages is enabled in Settings
- Wait 5-10 minutes for initial deployment
- Verify files are in the correct location

### CSS/styling not loading?
- Clear browser cache (Ctrl+Shift+Delete)
- Check file names are exactly `index.html` and `architecture.html`

### Links not working?
- Verify GitHub username in all links
- Ensure project repositories are public
- Check navigation links point to correct sections

---

## 💡 Interview Pro Tips

### When Sharing Your Portfolio:

1. **Lead with Architecture Diagrams**
   - "This shows the end-to-end flow of my CI/CD pipeline"
   - Explain each stage and the tools used

2. **Discuss Trade-offs**
   - "I chose Kubernetes over EC2 because..."
   - "I implemented Terraform for IaC to reduce setup time"

3. **Highlight Metrics**
   - "40% reduction in deployment time"
   - "99.9% system uptime achieved"
   - "60% reduction in manual effort"

4. **Talk About Real Challenges**
   - "I faced X issue with Kubernetes networking and solved it by..."
   - "Managing secrets in EKS was tricky, so I implemented..."

---

## 📈 Next Career Steps

After your portfolio is live:

1. ✅ Start sharing on LinkedIn
2. ✅ Add link to your resume
3. ✅ Share in DevOps communities (Reddit, Dev.to, Hashnode)
4. ✅ Write blog posts about your projects
5. ✅ Open-source some DevOps tools/scripts
6. ✅ Contribute to DevOps projects on GitHub

---

**Your portfolio is now ready to impress! 🎉**

Questions? Check the individual project repositories for implementation details.

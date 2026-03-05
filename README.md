# SW Platform API Documentation Portal - SDLC Official

## 🎨 SDLC-Branded Developer Portal

Complete, production-ready API documentation portal with official SDLC branding, real swagger specifications, sequence diagrams, and interactive API testing.

## ✨ What's Included

### Official Branding
- ✅ SDLC official colors (#19407F navy, #6193CD light blue, #fdc300 yellow, #2fac66 green)
- ✅ Lusail font family (Arabic + English support)
- ✅ Brand-compliant dark theme
- ✅ Gradient accent bars with all SDLC colors

### Real Production Assets
- ✅ 5 actual OpenAPI/Swagger YAML files from your system
- ✅ Sequence diagrams (submission, cancellation, request flow)
- ✅ SW Platform official logo

### Complete Documentation
- ✅ Homepage with API overview
- ✅ Interactive Swagger UI (test APIs in browser)
- ✅ Service catalog
- ✅ Architecture documentation  
- ✅ Authentication guides
- ✅ Getting started guide

### Developer Experience
- ✅ Single-window navigation (sticky sidebar)
- ✅ Smooth scrolling & animations
- ✅ Professional dark theme (easy on eyes)
- ✅ Mobile responsive
- ✅ Copy-to-clipboard code examples

## 📁 Portal Structure

```
portal-final/
├── index.html                              # Homepage
├── assets/
│   └── sdlc-theme.css                      # SDLC official theme
├── pages/
│   ├── interactive-api.html                # Swagger UI
│   ├── service-catalog.html                # API catalog
│   ├── architecture.html                   # Architecture docs
│   ├── authentication.html                 # Auth guides
│   └── getting-started.html                # Quick start
├── data/                                   # Real Swagger files
│   ├── SW_Request_Submission_API.yaml
│   ├── SW_Request_Completion_API.yaml
│   ├── SW_Cancel_Request_API.yaml
│   ├── SW_Manual_Approval_API.yaml
│   └── SW_Approval_Decisions_Callback_API.yaml
├── flows/                                  # Sequence diagrams
│   ├── Request Submission Flow.svg
│   ├── submission.png
│   └── cancellation.png
└── fonts/                                  # Lusail fonts
    ├── Lusail-Regular.otf
    ├── Lusail-Medium.otf
    ├── Lusail-Bold.otf
    └── (+ TTF versions)
```

## 🚀 Quick Deploy

### Option 1: GitHub + Vercel (Recommended)

```bash
cd portal-final

# Initialize git
git init
git add .
git commit -m "SW Platform API Documentation - SDLC Branded"

# Connect to GitHub
git remote add origin https://github.com/YOUR_USERNAME/SW.git
git branch -M main
git push -u origin main --force

# Deploy to Vercel
# Visit vercel.com → New Project → Import SW repository → Deploy
```

### Option 2: Direct Deploy

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
cd portal-final
vercel --prod
```

### Option 3: Any Static Host

Upload the `portal-final` folder to:
- Netlify
- GitHub Pages  
- AWS S3
- Your own server

## 🎨 SDLC Brand Colors

The theme uses official SDLC colors:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Navy Blue | `#19407F` | Primary branding, buttons |
| Light Blue | `#6193CD` | Links, interactive elements |
| Yellow | `#fdc300` | Accent highlights |
| Green | `#2fac66` | Success indicators, POST methods |
| Light Grey | `#ededed` | Primary text |
| Dark Grey | `#b2b2b2` | Secondary text |

## 📊 Key Features

### 1. Interactive API Testing
- Swagger UI with try-it-out functionality
- Test all 5 APIs in browser
- Download YAML specs
- Import to Postman

### 2. Visual Documentation
- Sequence diagrams showing request flows
- Architecture overview
- Clear API organization

### 3. Developer Tools
- Code examples
- Authentication guides
- Quick start tutorials
- Error handling guides

### 4. Professional Design
- SDLC brand compliance
- Dark theme (reduces eye strain)
- Smooth animations
- Mobile responsive

## 🔧 Customization

### Update URLs

Search and replace in all HTML files:
- Update sandbox/production API URLs
- Update support email
- Update statistics

### Customize Content

Edit pages in `pages/` folder:
- Add more documentation
- Update code examples
- Add FAQ sections

## 📖 Usage

### For Developers Integrating:
1. Visit homepage → understand overview
2. Read Getting Started → quick integration path
3. Try Interactive API → test endpoints
4. Download swagger specs → import to tools
5. Integrate!

### For Your Team:
1. Deploy portal
2. Share URL with integration partners
3. Monitor usage
4. Update swagger files as APIs evolve

## 🎯 Success Metrics

Portal provides:
- ✅ Self-service integration
- ✅ Reduced support burden
- ✅ Professional brand image
- ✅ Fast partner onboarding
- ✅ Always up-to-date specs

## 🆘 Support

Portal includes:
- Interactive testing
- Complete documentation
- Code examples
- Troubleshooting guides

## 📝 License

© 2026 SW Platform. All rights reserved.

## 🎉 What Makes This Special

This portal combines:
- Your actual production swagger files
- SDLC official branding
- Interactive testing capability
- Professional documentation
- Simple deployment

**Result:** A world-class developer portal that matches enterprise standards from companies like Stripe, Twilio, and AWS.

---

**Ready to deploy? Just push to GitHub and deploy to Vercel!** 🚀

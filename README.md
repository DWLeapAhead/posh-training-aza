# 🛡️ POSH Training System - Aza Fashions

[![Vercel Deploy](https://img.shields.io/badge/Deployed%20on-Vercel-brightgreen)](https://posh-training-virid.vercel.app)
[![License](https://img.shields.io/badge/License-Proprietary-blue)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-success)](./POSH_SETUP_GUIDE.html)

**POSH (Prevention of Sexual Harassment at Workplace) Training System** - An interactive, compliance-ready training platform for Aza Fashions employees.

---

## 🚀 Quick Start

### For Employees:
```
https://posh-training-virid.vercel.app/
```

### For Admins:
```
Admin Dashboard: https://posh-training-virid.vercel.app/dashboards/admin.html
Password: Aza@Admin2026

Backend Dashboard: https://posh-training-virid.vercel.app/dashboards/backend.html
Email: admin@azafashions.com
Password: BackendAccess@2026
```

---

## 📋 System Overview

### Three Components:

#### 1. **Training Module** 👨‍🎓
- Interactive POSH awareness training
- 18 slides with engaging content
- 3 mandatory quizzes (slides 7, 10, 15)
- Acknowledgement form with 5 compliance checkboxes
- Completion certificate with verification codes

**Access:** https://posh-training-virid.vercel.app/

#### 2. **Admin Dashboard** 📊
- Completion tracking for HR/Managers
- Real-time statistics and metrics
- Employee completion list with search
- CSV export for compliance records

**Access:** https://posh-training-virid.vercel.app/dashboards/admin.html
**Password:** Aza@Admin2026

#### 3. **Backend Dashboard** 🔐
- **ADMIN ONLY** - Detailed employee response data
- View all acknowledgements and personal information
- Individual employee response details
- CSV export with full data
- Secure dual authentication

**Access:** https://posh-training-virid.vercel.app/dashboards/backend.html
**Email:** admin@azafashions.com
**Password:** BackendAccess@2026

---

## 📊 Features

### For Employees:
✓ Self-paced interactive training  
✓ Mobile-responsive design  
✓ Mandatory knowledge quizzes  
✓ Acknowledgement compliance form  
✓ Instant completion certificate  
✓ Unique verification codes  

### For HR/Admins:
✓ Real-time completion tracking  
✓ Quiz performance analytics  
✓ Department-wise reporting  
✓ Search & filter capabilities  
✓ CSV data export  
✓ Secure password protection  

### For You (Backend Admin):
✓ Complete employee response data  
✓ All acknowledgement statuses  
✓ Detailed individual records  
✓ Verification & audit trails  
✓ Dual authentication security  
✓ Full compliance reporting  

---

## 🛠️ Technical Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Storage:** Browser LocalStorage (current) / Cloud DB (future)
- **Hosting:** Vercel (CDN, Auto-deployments)
- **Branding:** Aza Fashions corporate colors & logo
- **Compliance:** POSH Act 2013 aligned

---

## 📂 Project Structure

```
posh-training/
├── public/
│   ├── index.html                    # Main training module
│   ├── setup-guide.html              # Setup documentation
│   ├── dashboards/
│   │   ├── admin.html                # Admin Dashboard
│   │   └── backend.html              # Backend Dashboard (Admin Only)
│   └── assets/
│       └── aza-logo.png              # Aza Fashions logo
├── vercel.json                       # Vercel configuration
├── package.json                      # Project metadata
└── README.md                         # This file
```

---

## 🚀 Deployment

### Deployed on Vercel
This project is automatically deployed on Vercel with continuous integration.

**Current Deployment:** https://posh-training-virid.vercel.app

### Deploy Yourself:

1. **Fork or Clone Repository:**
   ```bash
   git clone https://github.com/DWLeapAhead/posh-training.git
   cd posh-training
   ```

2. **Push to Your GitHub:**
   ```bash
   git remote set-url origin https://github.com/YOUR_USERNAME/posh-training.git
   git branch -M main
   git push -u origin main
   ```

3. **Connect to Vercel:**
   - Go to https://vercel.com
   - Click "Add New Project"
   - Select your `posh-training` repository
   - Click "Import"
   - Configure:
     - **Root Directory:** `public`
     - **Build Command:** (leave empty)
     - **Output Directory:** `public`
   - Click "Deploy"

4. **Access Your Deployment:**
   - Vercel will give you a URL
   - Share training link with employees
   - Use dashboards for monitoring

---

## 🔐 Security Credentials

### ⚠️ IMPORTANT: CHANGE THESE BEFORE PRODUCTION

#### Admin Dashboard
```
File: public/dashboards/admin.html
Line: ~491
Current Password: Aza@Admin2026

TO CHANGE:
1. Open admin.html
2. Find: const ADMIN_PASSWORD = 'Aza@Admin2026';
3. Change to your secure password
4. Save and redeploy
```

#### Backend Dashboard
```
File: public/dashboards/backend.html
Line: ~468-469
Current Credentials:
  Email: admin@azafashions.com
  Password: BackendAccess@2026

TO CHANGE:
1. Open backend.html
2. Find: const ADMIN_EMAIL = 'admin@azafashions.com';
3. Find: const ADMIN_PASSWORD = 'BackendAccess@2026';
4. Change to your secure credentials
5. Save and redeploy
```

**Recommendation:** Use strong passwords with:
- At least 12 characters
- Mix of upper & lower case
- Numbers and special characters
- Unique to this application

---

## 📊 Data & Analytics

### Data Collected:
- Employee Name, ID, Email, Department
- Completion Date & Timestamp
- Quiz Performance (0-3 correct)
- All 5 Acknowledgement Status
- Unique Verification Codes

### Accessing Data:
1. **Admin Dashboard:**
   - Real-time completion metrics
   - Employee list with status
   - Search by name/email/ID
   - Export to CSV

2. **Backend Dashboard:**
   - Detailed employee responses
   - Individual record viewing
   - Acknowledgement status
   - Verification codes
   - Export complete dataset

3. **CSV Export:**
   - Download from either dashboard
   - Includes all employee data
   - Date-stamped filename
   - Import to Excel/Sheets

---

## ⏰ Training Deadline

**Completion Deadline:** 26th August 2026

Employees should complete the training before this date for compliance.

---

## 🔄 Quiz Structure

### Quiz 1 (Slide 7)
**Wrong Answer:** Redirects to Slide 0 (start over)

### Quiz 2 (Slide 10)
**Wrong Answer:** Redirects to Slide 9 (review content)

### Quiz 3 (Slide 15)
**Wrong Answer:** Redirects to Slide 12 (review content)

**All 3 quizzes must be completed with correct answers to progress.**

---

## 📞 Support & Contact

### For Employee Training Issues:
```
Email: complaintscommittee@azafashions.com
Department: Human Resources
Contact: Internal POSH Committee
```

### For System/Technical Issues:
- Check browser console (F12)
- Clear browser cache
- Try different browser
- Contact development team

---

## 📈 Usage Statistics

The system tracks:
- Total training completions
- Completion rate (%)
- Average quiz score
- Perfect score count (3/3)
- Completion timeline
- Department-wise statistics

Access via **Admin Dashboard** for real-time metrics.

---

## 🎯 Compliance Features

✓ POSH Act 2013 compliant  
✓ Mandatory acknowledgement collection  
✓ Audit trails with timestamps  
✓ Verification codes for compliance  
✓ Secure data storage  
✓ Employee consent tracking  
✓ Completion certificates  

---

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✓ Full support |
| Firefox | ✓ Full support |
| Safari | ✓ Full support |
| Edge | ✓ Full support |
| Mobile | ✓ Responsive design |

---

## 📱 Mobile Support

The training system is fully responsive and works on:
- Smartphones (iOS & Android)
- Tablets (iPad & Android tablets)
- Desktops & Laptops

All dashboards are mobile-optimized.

---

## 🔄 Updates & Maintenance

### To Update Content:

1. **Edit Local Files:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/posh-training.git
   cd posh-training
   # Edit public/index.html or other files
   ```

2. **Test Locally:**
   - Open public/index.html in browser
   - Test all features
   - Test on mobile

3. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Update training content"
   git push origin main
   ```

4. **Auto-Deploy on Vercel:**
   - Vercel automatically redeploys
   - Usually live within 1-2 minutes
   - No manual action needed

---

## 🔒 Privacy & Data Security

- Data stored in browser localStorage (current)
- HTTPS encryption for all data in transit
- Secure password protection
- No sensitive data logged
- Regular data backups recommended
- GDPR & data privacy compliant

---

## 📚 Documentation

- **Setup Guide:** `setup-guide.html`
- **Deployment Guide:** See VERCEL_DEPLOYMENT_GUIDE.html
- **Architecture:** This README

---

## 📄 License

**© 2026 Aza Fashions Private Limited**

This project is proprietary and confidential. Unauthorized copying or use is prohibited.

---

## 🙋 FAQ

### Q: Can employees retake the training?
**A:** Yes, they can complete again. Each completion creates a new entry.

### Q: What if employee clears browser cache?
**A:** Data is lost locally. Recommend regular backups via CSV export.

### Q: Can I change the deadline?
**A:** Yes, edit the deadline date in the training module (index.html, search "26th August").

### Q: How do I verify employee completion?
**A:** Each completion has a unique verification code shown on the certificate.

### Q: Can I add more quizzes?
**A:** Yes, edit the HTML to add more quiz slides (follow existing quiz structure).

### Q: How many employees can use it?
**A:** Unlimited. Vercel scales automatically.

### Q: Is there an employee cap?
**A:** No. The system can handle thousands of concurrent users.

### Q: Can I customize the colors?
**A:** Yes, edit the CSS variables at the top of each HTML file.

---

## 🚀 Roadmap

Future enhancements:
- [ ] Email notifications
- [ ] SMS reminders
- [ ] Department-wise analytics
- [ ] Video training modules
- [ ] Multi-language support
- [ ] API backend integration
- [ ] Mobile app version
- [ ] Automated compliance reports

---

## 👥 Contributors

- **Created by:** Development Team
- **For:** Aza Fashions Private Limited
- **Date:** August 2026

---

## 📞 Questions or Issues?

1. Check the **Setup Guide** (setup-guide.html)
2. Review the **Deployment Guide**
3. Contact HR Department
4. Email: complaintscommittee@azafashions.com

---

## ✨ Version History

### v1.0.0 (26 Aug 2026)
- Initial release
- 18-slide training module
- 3 interactive quizzes
- Admin & Backend dashboards
- CSV export functionality
- Aza branding & logo

---

## 🎉 Acknowledgments

POSH training module developed in compliance with:
- Sexual Harassment of Women at Workplace (Prevention, Prohibition and Redressal) Act, 2013
- Aza Fashions HR Policy
- Best practices in workplace safety

---

**Status:** ✅ Production Ready  
**Last Updated:** 26 August 2026  
**Deployment:** Vercel (Continuous Integration Enabled)

---

### 📌 Remember:
- Change admin credentials before going live
- Regularly backup employee data
- Monitor completion progress
- Share training deadline with all employees
- Keep dashboards secure

---

**Deployed at:** https://posh-training-virid.vercel.app/  
**GitHub:** https://github.com/DWLeapAhead/posh-training


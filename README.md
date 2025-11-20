# ProgFinalPOE
# Contract Monthly Claim System

## PROG6212 Programming 2B - POE Submission

### Student Information
- **Name:** Given Luna Summerton
- **Student Number:** ST10434685
- **Module:** PROG6212 - Programming 2B

### Project Overview
A comprehensive web application for managing academic claims with automated workflows for lecturers, coordinators, managers, and HR staff.

### Features Implemented

####  Lecturer View Automation
- Real-time auto-calculation of claim amounts
- Comprehensive validation (hours: 0.5-100, rates: $50-$1000)
- Claim status tracking and history

####  Coordinator/Manager View Automation  
- Two-level approval workflow (Coordinator → Manager)
- Smart dashboard with progress tracking
- Professional rejection handling with reasons

####  HR View Automation
- Comprehensive statistics dashboard
- Automated report generation
- Payment processing simulation
- System validation tools

### Technology Stack
- **Backend:** ASP.NET Core MVC, C#, Entity Framework
- **Frontend:** Razor Views, JavaScript, jQuery, Bootstrap 5
- **Database:** SQLite with Code-First approach
- **Version Control:** Git with strategic commit history
git add Views/Home/ClaimStatus.cshtml wwwroot/css/site.css
## git commit -m "FEAT: Add claim status tracking and improved UI
- Real-time status tracking for lecturers
- Professional status badges (Approved/Pending/Rejected)
- Responsive table design with Bootstrap
- Enhanced visual feedback system"
git push
### git add Controllers/AdminController.cs Views/Admin/Dashboard.cshtml
git commit -m "FEAT: Implement coordinator approval workflow
- Two-level approval system (Coordinator → Manager)
- Smart dashboard for pending claims
- Progress indicators and workflow tracking
- Quick action buttons for approvals"
git push

### git add Views/Admin/AllClaims.cshtml
git commit -m "FEAT: Add comprehensive claims management
- All claims overview with filtering
- Statistics dashboard with totals
- Professional table design with status indicators
- Export-ready data presentation"
git push

### git add Controllers/AdminController.cs
git commit -m "FEAT: Implement HR automation features
- Automated report generation system
- Payment processing simulation
- System-wide validation checks
- JSON-based data export functionality"
git push 

### git add Models/Claim.cs Controllers/HomeController.cs
git commit -m "FIX: Resolve SQLite decimal aggregation issues
- Implement client-side calculation strategy
- Fix NotSupportedException for decimal operations
- Maintain all automation features while fixing limitations
- Enhanced error handling and user feedback"
git push

### git add Views/Shared/_Layout.cshtml wwwroot/css/site.css Views/Home/Index.cshtml
git commit -m "STYLE: Enhance user interface and experience
- Professional Bootstrap styling throughout
- Responsive design for all screen sizes
- Improved navigation and layout
- Real-time statistics on homepage"
git push

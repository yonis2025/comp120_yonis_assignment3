# HirePath

HirePath is a professional frontend-only job platform starter built with plain HTML, CSS, and JavaScript.

## What is included
- Public marketing site
- Applicant dashboard pages
- Employer dashboard pages
- Admin dashboard pages
- Branded HirePath logo system
- Google Fonts-based typography system
- Real remote stock imagery
- Demo avatars and company visuals
- localStorage-based auth simulation
- Demo test accounts
- Strong frontend validation rules
- Resume file validation
- Employer job-post validation
- UI feedback, loading states, and password strength meter

## Demo accounts
- Applicant: `applicant@hirepath.com` / `Test@1234`
- Employer: `employer@hirepath.com` / `Test@1234`
- Admin: `admin@hirepath.com` / `Admin@1234`

## Run locally
Because the project loads JSON files, open it with a local server.

### VS Code
1. Open the project folder in VS Code
2. Install the Live Server extension if needed
3. Right-click `index.html`
4. Choose **Open with Live Server**

## Validation rules
### Password
- Minimum 8 characters
- At least 1 uppercase letter
- At least 1 lowercase letter
- At least 1 number
- At least 1 special character from `!@#$%^&*`
- No spaces
- Common passwords are rejected

### Email
- Proper email format required
- Uniqueness is simulated in frontend using `localStorage`

### Username
- Minimum 3 characters
- Letters and numbers only
- No spaces

### Phone
- International format accepted
- Numbers only, optional leading `+`

### Resume upload
- PDF, DOC, DOCX only
- Max size 2MB

### Employer job post
- Job title required
- Salary must be numeric
- Location required
- Description minimum 50 characters

## Important implementation note
This project is still frontend-only. Features such as email verification, social login, subscriptions, AI resume matching, messaging, and interview scheduling are simulated for demo and presentation purposes.

## Asset notes
See `assets/ASSET-GUIDE.md` for stock image sources and font references.

## Future backend upgrade
Later you can connect this structure to:
- Node/Express, Laravel, Django, or Spring backend
- Database for users/jobs/applications
- Real auth and session handling
- Payment provider
- Email provider
- File storage provider
- AI resume matching service
- Real-time messaging and notifications

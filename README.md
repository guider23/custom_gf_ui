Google Form Submission Demo
A sleek, futuristic web app to generate and deploy custom forms that integrate seamlessly with Google Forms. Built with a cyberpunk-inspired UI, this project combines dynamic form creation, real-time validation, and Vercel deployment for a smooth user experience.
Features

Dynamic Form Generation: Input a Google Form link and JSON data to create custom forms instantly.
Real-Time Validation: Validates Google Form URLs and JSON data with clear feedback.
Vercel Deployment: Deploy forms with a single click and track deployment history.
Cyberpunk Aesthetic: Neon gradients, particle animations, and 3D tilt effects powered by GSAP and Vanilla Tilt.
JSON Extraction Tool: Copy-paste code to extract form fields directly from Google Forms.
Responsive Design: Optimized for desktop and mobile with a glassmorphic UI.
Credit: Made by Siddarth, proudly displayed with a GitHub profile avatar.

Tech Stack

HTML5, CSS3, JavaScript: Core web technologies for a lightweight build.
GSAP: Smooth animations for a dynamic feel.
Vanilla Tilt: 3D tilt effects for interactive elements.
JSZip: Handles file generation for deployment.
Vercel API: Seamless deployment integration.
Fonts: Orbitron and Roboto Mono for a sci-fi vibe.

Getting Started

Clone the Repo:git clone https://github.com/guider23/google-form-submission-demo.git


Open index.html:
Serve locally using a tool like live-server or open directly in a browser.


Usage:
Paste a Google Form link and JSON data (use the provided extraction code in the help popup).
Click "Generate Form" to create your form.
Deploy to Vercel with the "Deploy" button and view links in the history panel.



How It Works

Form Extraction: Use the JavaScript snippet in the help popup to extract entry.* fields from any Google Form.
Form Creation: Input extracted JSON to generate input fields dynamically.
Submission: Forms submit data to Google Forms via POST requests (CORS handled with no-cors mode).
Deployment: The Vercel API hosts the generated form, with URLs stored in the deployment history.

Screenshots

Contributing
Pull requests are welcome! For major changes, open an issue to discuss your ideas. Ensure code follows the project's style guide (consistent formatting, clear comments).
License
MIT License - feel free to use, modify, and distribute.
Credits
Developed by Siddarth with a passion for clean code and futuristic design.

# NIKHIL Electronics & Service Care — Website

A responsive, single-page business website created from the supplied NIKHIL Electronics & Service Care visiting-card photo.

## Included
- Responsive Home, Services, About and Contact sections
- Appliance illustrations stored locally in `assets/`
- Supplied visiting-card photo in the About section
- Tap-to-call phone link
- WhatsApp enquiry links
- Mobile navigation
- Basic SEO title and description
- No build tools or package installation required

## Business details used
- **Business:** NIKHIL Electronics & Service Care
- **Proprietor:** Tushar Ahire
- **Phone / WhatsApp:** 90677 51593
- **Services shown:** Fridge, TV, Aqua, Washing Machine, Air Conditioner, Microwave, Inverter and Deep Freezer

> Please verify the business name, spelling of “Aqua”, phone number and service list before publishing. The address was not visible on the supplied card, so it has not been invented or added.

## Run locally
1. Extract the ZIP file.
2. Open the `nikhil-electronics-website` folder in VS Code.
3. Open `index.html` in a browser, or use the **Live Server** extension in VS Code and choose **Open with Live Server**.

No `npm install` is needed. This is a static HTML/CSS/JavaScript website.

## Change business information
- Edit the business name, proprietor and services in `index.html`.
- Update the phone number in the `tel:` links and the WhatsApp links (`wa.me/919067751593`) if required.
- Replace `assets/business-card.jpeg` with an updated business-card photo if needed.
- Edit colors, fonts and layout in `style.css`.

## Publish online
### GitHub Pages
1. Create a GitHub repository, for example `nikhil-electronics-service`.
2. Upload all files and folders from this project (keep the `assets` folder).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide the public website URL after deployment.

You can also deploy this static folder using Netlify or another static hosting provider.

## Notes
- Appliance graphics are simple local SVG illustrations, so they load without third-party image hosting.
- Google Fonts are loaded from Google Fonts when internet access is available; system fonts are used as fallback.
- The site does not currently include online booking, payment, admin login or a backend.

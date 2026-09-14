# Dipak Pariyar — Personal Portfolio (Vercel Ready)

A responsive, static personal-brand website built with plain HTML, CSS and JavaScript.

## Included
- Professional responsive design
- Dipak Pariyar as the primary professional/legal display name
- Dipendra Sonam retained for social identity
- Education timeline
- BBS and ACCA journey
- 8 ACCA papers passed + AA exam sat / result awaiting
- Public speaking gallery
- Achievements and skills
- CV PDF
- Social/contact links
- Google Form inquiry button
- No framework or build step required

## Google Form
Open `config.js` and set:

`const GOOGLE_FORM_URL = "YOUR_GOOGLE_FORM_LINK";`

Example:
`const GOOGLE_FORM_URL = "https://docs.google.com/forms/d/e/XXXXXXXX/viewform";`

Send the actual Google Form link to ChatGPT and it can be inserted into the final package.

## Vercel deployment
1. Create a GitHub repository.
2. Upload all files in this folder.
3. Import the repository into Vercel.
4. Deploy. No build command is required.
5. In Vercel Project Settings → Domains, add `pariyardipak.com.np`.
6. At the `.np` domain provider/DNS, use the DNS records Vercel gives for the project.

## Files
- `index.html`
- `config.js`
- `assets/` (photos + CV)

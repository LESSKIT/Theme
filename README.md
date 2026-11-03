# Syrene Help Center — GitHub Pages

A build-free, English-language documentation and support website. No npm installation or server is required to host the static pages.

## Deploy

1. Create a GitHub repository for this website only. Do not upload the theme source, test data, session files, or audit backups.
2. Upload the contents of this folder to the repository root. The root must contain index.html and .nojekyll, rather than an extra enclosing folder.
3. Open Settings > Pages. Select Deploy from a branch, choose main and /(root), then Save.
4. Open the published URL. Project sites normally appear at https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/ . All internal links are relative and work under that subpath.
5. Check guide.html, modules.html, support.html, and privacy.html on desktop and mobile.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Activate and test the support form — required

The form uses FormSubmit and sends requests to wukaicheng@iadlink.com. GitHub Pages itself cannot receive or email submissions.

1. After publishing, submit one test request using an email address you control. This has NOT been submitted or activated by the developer assistant.
2. Open the activation email received at wukaicheng@iadlink.com and confirm the form. Check spam if needed.
3. Submit a second test from the published site, with an attachment. Confirm the support email arrives and Reply goes to the requester.
4. Verify the automatic acknowledgment reaches the requester's email. reCAPTCHA remains enabled because FormSubmit requires it for automatic responses.
5. Verify errors, mobile behavior, file-size validation, and spam checks. The form uses normal POST, not AJAX. The provider controls its final confirmation page.

Do not claim the contact form is working until these checks pass. Email confirmation, service availability, delivery, spam filtering, and any provider limits must be verified in the deployed environment. The HTML form action can be replaced with another service if needed. Do not place an API secret in this public repository.

Form provider documentation: https://formsubmit.co/documentation

## URLs for the theme listing

After deployment and form activation, use the actual public URLs:

- Documentation: your published guide.html URL.
- Support: your published support.html URL.

Update theme_documentation_url and theme_support_url in the theme's config/settings_schema.json, as well as the Theme Store listing. This website archive is NOT the Shopify theme ZIP.

## Maintain

Edit the HTML to update content. All pages share styles.css and site.js. The guide covers version 0.2.1; module settings were generated from its current section schemas. Update the documents whenever theme behavior or labels change. Review the privacy notice for your organization's practices before publication. No analytics or advertising scripts are included.

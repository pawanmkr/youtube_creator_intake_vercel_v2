YOUTUBE CREATOR STRATEGY INTAKE — VERCEL DEPLOYMENT

1. Open index.html and replace:
   const WHATSAPP_NUMBER = "REPLACE_WITH_YOUR_NUMBER";
   with your WhatsApp number in international format, digits only, e.g. India: 919876543210.

2. Deploy on Vercel:
   - Upload index.html to a GitHub repository.
   - Import the repository at https://vercel.com/
   - Choose Framework Preset: Other.
   - No build command is needed for this static site.
   - Deploy and test the live URL on a phone.

3. Edit anytime:
   Update index.html and push to GitHub; Vercel redeploys automatically.

NOTES
- Single-page, responsive questionnaire with blue theme and Hinglish copy.
- Existing-channel questions appear only when the respondent selects an existing channel.
- Submit opens WhatsApp with a prefilled message. Respondent must manually tap Send.
- Very long WhatsApp messages can exceed app/URL limits. Copy/download fallbacks are provided.
- No database/backend is included.

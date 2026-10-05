JALEEZUR & SHRIN - NIKAH INVITATION WEBSITE

Files
  index.html     the whole website (one file)
  og-image.jpg   the picture WhatsApp shows when the link is shared
  nasheed.mp3    background nasheed, starts when the guest taps the wax seal
  kondattam-logo.webp  logo on the last page

Before sharing - open index.html in a text editor, find "const CONFIG" near the
start of the <script> part, and fill in:
  mapsUrl         the real Google Maps pin link for Kavin Mahal
  whatsappNumber  already set to +91 96557 03434 (change it in index.html if needed)

To put it online: upload all the files together to Netlify Drop, Vercel, GitHub Pages
or your own hosting. Then change og:image in index.html to the full web address
of og-image.jpg (e.g. https://yoursite.com/og-image.jpg) so WhatsApp shows the preview.

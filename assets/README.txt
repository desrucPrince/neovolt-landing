ASSETS NEEDED FOR NEOVOLT LANDING PAGE
=============================================

DROP THESE FILES INTO THIS /assets FOLDER:

1. icon.png
   - Your app icon export
   - Size: 1024x1024px recommended (will display at 26x26 in nav)
   - Format: PNG, no transparency on root (Apple requirement)

2. screen-1.png through screen-4.png
   - iPhone screenshots from App Store Connect or Simulator
   - Size: 390x844px (iPhone 14) or 1290x2796px (iPhone 15 Pro Max)
   - Format: PNG or JPG
   - Recommended shots:
     1. Home tab with battery hero and status
     2. Stats tab with port details and LCD view
     3. Settings tab with controls
     4. Device info and settings

3. og-image.png
   - Social share preview image (shows when you share the URL on Twitter/iMessage/Slack)
   - Size: 1200x630px exactly
   - Content: App name + tagline + icon on dark background (#111113)
   - You can generate this with Nano Banana Pro or Figma

DEPLOY CHECKLIST:
[ ] All images added to assets/
[ ] App Store URL updated in index.html APP config (search: appStoreUrl)
[ ] Subdomain CNAME added in Cloudflare DNS
[ ] Custom domain added in Cloudflare Pages project settings
[ ] Privacy policy URL tested: neovolt.neocortez.com/privacy.html
[ ] Support URL tested: neovolt.neocortez.com/support.html
[ ] Paste both URLs into App Store Connect before submission

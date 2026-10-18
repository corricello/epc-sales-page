# The Empowered Parent Collective: sales page and webinar page

This folder has two web pages: the **sales page** (`index.html`) and the **webinar registration page** (`webinar/index.html`), plus the images and your brand font. You can change it yourself by asking an AI tool like Claude or ChatGPT. You don't need to know how to code.

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The sales page: all the words, colors and buttons |
| `webinar/index.html` | The Child Compass Free Masterclass registration page |
| `webinar/child-compass-mockup.webp` | The Organizer picture on the webinar page |
| `lisa.jpg` | Your photo in the "Meet your guide" section |
| `inside-bg.jpg` | The soft purple background behind "What's inside" |
| `fonts/` | Glacial Indifference, your body font (free to use under the SIL Open Font License; the license file is in the folder) |

Keep everything together in the same folder. If a file goes missing, its image or font disappears from the page.

## How to see the page

Double-click `index.html`. It opens in your browser. Refresh the browser after any change.

## How to change something using AI

1. Open Claude or ChatGPT.
2. Attach `index.html` (drag it into the chat).
3. Paste the message below, then say what you want changed.
4. The AI gives you a new version of the file. Save it over the old `index.html`, then refresh your browser.

**Copy and paste this:**

> This is the sales page for my membership, the Empowered Parent Collective. It's a single HTML file. I'm not a developer. Please make only the change I ask for and leave everything else exactly as it is. Give me the complete updated file back, so I can save it over the old one. The prices, checkout links and dates are in the SETTINGS block at the bottom of the file, and the instructions at the top of the file explain how it's organised. Here's what I'd like changed:

Then write your change in plain words, for example:
- "Change the monthly price to $69 and the annual price to $690."
- "Update the enrollment dates to 1 to 8 March."
- "Replace the second testimonial with this one: ..."
- "Rewrite the 'Meet your guide' section so it's shorter."

## Things you'll need to fill in

Look for anything in [square brackets] on the page. Right now that's mainly:
- The enrollment dates are set to November 6 to 12 (top of the page and the last line before the footer). To change them, edit `bannerText` and `closingText` in the settings.
- The checkout link is set (both join buttons use the same ThriveCart page, which opens in a new tab). To change it, edit `monthlyCheckoutUrl` and `annualCheckoutUrl` in the settings.
- The private support FAQ currently says to email lisacorricello@gmail.com. Change it if you'd like a different address.
- The terms and conditions link is set. If there's a separate privacy policy page, add it to the footer.

All of these except the private support wording are in the SETTINGS block at the bottom of `index.html`. Ask your AI: "Put my checkout link [paste link] into the settings."

## Swapping a photo

Save your new image with the **same name** (`lisa.jpg` or `inside-bg.jpg`) in this folder, replacing the old one. Photos with a plain, calm background work best behind text.

## Good to know

- **Check after every change.** Look at the whole page, including on your phone, before sharing it.
- **Keep a copy.** Before a big change, duplicate the folder so you can go back.
- **Don't let the AI add things you haven't said.** If it adds a testimonial, number, guarantee or promise you didn't give it, delete it.
- **Testimonials:** use words your clients actually said, and ask their permission to use their name or initial.

## The webinar registration page

The page for the free Child Compass masterclass lives at `webinar/index.html`. It works exactly like the sales page, and the same AI instructions above apply. When you attach the file, attach `webinar/index.html`.

At the bottom of that file is a SETTINGS block with:
- `webinarDate` and `webinarTime`: update these and the date and time change everywhere on the page.
- `registerUrl`: where every "Save my seat" button goes. It's currently the bit.ly link, so you can repoint that link without touching the page.
- `termsUrl`: the terms and conditions link in the footer.

Example requests:
- "Change the webinar to Thursday, December 3 at 6pm PT / 9pm ET."
- "Replace the registration link with this one: ..."
- "Add a line to the FAQ explaining how to join the webinar."

**Things to check after any change**
- The photo on this page is `lisa.jpg` in the main folder, shared with the sales page.
- If the webinar is hosted somewhere that needs an account, add a line to the FAQ so people know before they register.
- The Organizer ($17) is described as an optional extra. Only keep that section if the Organizer is still offered at registration.

## Where the pages live

The two pages are served from this folder at your subdomain:
- Sales page: the main address
- Webinar page: the main address followed by `/webinar/`

After you save a change to the files on GitHub, the live page updates within a minute or two. Hard-refresh your browser (Cmd+Shift+R on a Mac, Ctrl+Shift+R on Windows) to see it.

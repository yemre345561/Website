# Website

Course project for ACM 262.4 by Yunusemre Açıkoğlu: a multi-page HTML and CSS website for a travel company called PRIOR.

All pages live in the folder `YUNUSEMRE AÇIKOĞLU ACM 262.4 Web Page Project/`. Each page includes its own copy of the top navigation and its CSS in a `<style>` block. There is no separate stylesheet and no JavaScript. Destination photographs (JPEG files) sit in that same folder, next to the HTML.

## Pages

| File | Purpose |
|------|---------|
| `default.html` | Home |
| `about.html` | About |
| `travel.html` | Travel overview |
| `egypt.html`, `india.html`, `nepal.html`, `piedmont.html`, `seville.html`, `yucatan.html` | Destination pages |
| `application.html` | Application |
| `subscription.html` | Subscription |
| `faq.html` | FAQ |
| `contact.html` | Contact |

## How to view

Clone the repository, open the project folder, and open `default.html` in a browser. No build step and no local server are required. Links between pages are relative paths in that folder.

```bash
git clone https://github.com/yemre345561/Website.git
```

This is a static student website, not a deployed product. The application, subscription, and contact forms post to the W3Schools sample endpoint `https://www.w3schools.com/action_page.php`. Submitting them does not create a membership, take a payment, or book a trip. The home page embeds a YouTube video and the contact page embeds a Google Map. Those frames load only when the browser can reach those sites.

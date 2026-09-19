## wede-part-2
# part 2
External stylesheet styles.css linked to every page (the inline <style> block was removed from index.html).
Relative units (rem, %) for type, spacing and widths.
Design tokens (colours, fonts) kept in :root custom properties so the scheme can change in one place.
# Changelog
# entry in part 2
on the 16th of September 2026  i removed the inline <style> block and added <link rel="stylesheet" from the index.html file also added href="styles.css"> in the <head>
in the file syle.css i had created the external stylesheet, moved every rule from the inline block into it and added a CSS reset. The repeated margin: 0; padding: 0 declarations on ul.contact-list, .header h1, .header p and .value were removed because the reset covers them and Changed all px font sizes, padding and widths to rem and % and Labels changed from 11px uppercase grey (#888) to 0.875rem sentence case in a lighter colour, Changed the page from a single 420px card to a wider card. The contact list is now a CSS Grid with 3 columns on desktop, 2 on tablet and 1 on mobile, Card centring moved from body { display: flex } to margin: auto on .card, added :hover, :active and :focus-visible styles for links, buttons and contact tiles, Added media queries at 62rem (tablet) and 40rem (mobile), including a full-width button and edge-to-edge card on mobile
Added prefers-reduced-motion rule
by the index.html i Added the "Book your haircut" button linking to WhatsApp booking

# references
Eric Kayz Barbershop. n.d. Eric Kayz Barbershop. Available at: https://erickayz.com (Accessed: 15 August 2026).
Google Fonts. n.d. Barlow Condensed and Source Sans 3. Available at: https://fonts.google.com (Accessed: 16 september 2026).
MDN Web Docs. n.d. CSS grid layout. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout (Accessed: 16 september 2026).

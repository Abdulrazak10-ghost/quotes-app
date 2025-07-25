# Quote App

A simple web application that displays a random quote of the day, with options to share on Twitter and WhatsApp.

## Features
- Fetches a random quote and author from an API
- Displays the quote and author in a styled quote box
- Responsive design for mobile and desktop
- Twitter share button (posts quote and author)
- WhatsApp share button (posts quote and author to WhatsApp Status)
- Custom blue "Q" favicon for branding

## Files
- `index.html`: Main HTML file containing the app structure and logic
- `style.css`: Styles for the quote box and buttons, including responsive design
- `icon.JPG`: Icon used for the share buttons

## How it works
- On page load, fetches a random quote from `https://dummyjson.com/quotes/random`
- Displays the quote and author
- "New Quote" button fetches a new random quote
- "Post" button opens Twitter with the quote and author pre-filled
- "WhatsApp" button opens WhatsApp Status with the quote and author pre-filled

## Customization
- The favicon is a blue "Q" generated with SVG
- Button styles and layout are responsive and can be adjusted in `style.css`

## Requirements
- Internet connection (to fetch quotes from the API)
- Modern web browser

## Usage
1. Open `index.html` in your browser
2. Click "New Quote" to get a new quote
3. Use the share buttons to post to Twitter or WhatsApp Status

## Credits
- Quotes API: [dummyjson.com](https://dummyjson.com/quotes/random)
- Favicon: Inline SVG

---


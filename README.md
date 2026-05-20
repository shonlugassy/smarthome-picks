# 🛍️ SmartHome Picks

A professional Amazon Affiliate marketing website featuring curated home products. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies.

**Live Site:** [smarthome-picks.vercel.app](https://smarthome-picks.vercel.app)

## Features

- 5 curated Amazon affiliate products with real links
- Real-time search bar filtering by name, category, or description
- Category filter tabs (Home Cleaning, Bedroom Ambiance, Kitchen Organization, Laundry Solution, Home Decor)
- Product cards with star ratings, reviews count, and crossed-out original price
- Best Seller and Popular This Week badges
- Free Shipping badge on every product
- Social proof view counter per product
- You Might Also Like recommendations inside each card
- Recently Viewed section powered by localStorage
- Promo video with mute/unmute toggle
- Fully mobile responsive
- Amazon affiliate disclosure
- Deploy-ready for Vercel

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- Google Fonts (Inter)
- Amazon Associates affiliate links
- Hosted on Vercel

## Adding a New Product

Open `index.html` and add a new object to the `products` array:

```js
{
    tag:           "Category Name",
    name:          "Product Name",
    desc:          "Short description.",
    features:      ["Feature 1", "Feature 2", "Feature 3"],
    price:         "$XX – $XX",
    originalPrice: "$XX",
    image:         "https://m.media-amazon.com/images/I/XXXXX.jpg",
    link:          "https://www.amazon.com/dp/ASIN?tag=smarthomep0e2-20",
    rating:        4.5,
    reviews:       1000,
    views:         500,
    bestSeller:    false,
    popular:       false,
    video:         ""
}

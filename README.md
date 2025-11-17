# Season Ticket Calculator 🚇

A simple, minimalist web app to calculate whether buying a transit season ticket is worth it based on your travel habits.

## How It Works

Enter your:

- Monthly pass cost
- Discount percentage per trip
- Single trip cost
- Number of trips per month (optional)

The calculator will tell you:

- If the season ticket is worth it
- How much you'll save (or lose)
- The break-even point

## Adding New Presets

Want to add a transit package for your city?

1. Fork this repository
2. Edit `index.html` and add your preset to the `presets` array:

```javascript
{ id: 'your-id', name: 'Your Package Name', cost: '10', discount: '20' }
```

3. Submit a pull request!

## Deployment

This app is automatically deployed to GitHub Pages via GitHub Actions.

### Setup

1. Fork or clone this repository
2. Go to Settings → Pages
3. Under "Source", select "GitHub Actions"
4. Push to main branch - it deploys automatically!

## License

MIT License - feel free to use and modify!

# Birthday Web App - Photo Instructions 📸

## How to Add Your Photos

1. **Prepare 6 photos** that you want to include in the birthday web app
2. **Rename them** as follows:
   - `photo1.jpg`
   - `photo2.jpg`
   - `photo3.jpg`
   - `photo4.jpg`
   - `photo5.jpg`
   - `photo6.jpg`

3. **Place all photos** in this `photos` folder

## Supported Formats
- `.jpg` or `.jpeg` (recommended)
- `.png`
- `.gif`

## Recommendations
- Use high-quality photos (but not too large - ideally under 2MB each)
- Recommended dimensions: 800x600 or similar aspect ratio
- Photos will be automatically cropped to fit the cards

## Customizing Messages
To customize the messages that appear when you flip each photo card:
1. Open `index.html`
2. Find each photo card's `photo-back` section
3. Edit the text inside `<p class="photo-message">` tags

Example:
```html
<div class="photo-back">
    <p class="photo-message">Your custom message here! 💖</p>
</div>
```

## Adding Background Music (Optional)
1. Get a birthday music file (MP3 format recommended)
2. Create a `music` folder in the main directory
3. Place your music file as `birthday.mp3`
4. Uncomment the source line in `index.html`:
```html
<source src="music/birthday.mp3" type="audio/mpeg">
```

Enjoy creating amazing birthday memories! 🎉

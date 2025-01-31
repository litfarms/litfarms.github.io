# LitFarms Product Listing

![LitFarms Product Listing Interface](litfarms.gif)

A dynamic, real-time product listing web application for LitFarms THCA products. This application provides a modern, responsive interface for viewing and monitoring product availability with advanced filtering and notification capabilities.

## Features

### Product Display
- Real-time product updates
- Responsive grid layout
- Beautiful product cards with images
- Strain type indicators
- Detailed pricing by tier and weight
- Stock status indicators

### Advanced Filtering
- Search products by name
- Filter by tier (Essential, Preferred, Supreme)
- Filter by strain type (Sativa, Indica, Hybrid)
- Filter by weight (28g, 3.5g)
- Sort by name (A-Z, Z-A) or price
- Toggle between all items and in-stock only

### Notification System
- Real-time product monitoring
- Customizable update frequency
- Notifications for:
  - New products
  - Stock changes
  - Price updates
  - Product removals
- Multiple notification methods:
  - Mobile app notifications via Ntfy
  - Email notifications
- Filter notifications by:
  - Product tiers
  - Product weights
  - Specific products

## Setup

### Basic Usage
1. Visit the website at [litfarms.github.io](https://litfarms.github.io)
2. Use the filters at the top to find specific products
3. Click on any product card to view more details on the main LitFarms website

### Setting Up Notifications

#### Mobile App Notifications
1. Download the Ntfy app:
   - [iOS App Store](https://apps.apple.com/us/app/ntfy/id1625396347)
   - [Google Play Store](https://play.google.com/store/apps/details?id=io.heckel.ntfy)
2. Click the settings gear icon in the bottom right of the website
3. Enable "App Notifications"
4. Generate a unique topic name or enter your own
5. In the Ntfy app:
   - Tap "Add subscription"
   - Enter your topic name exactly as shown in the settings
   - Save the subscription

#### Email Notifications
1. Click the settings gear icon
2. Enable "Email Notifications"
3. Enter your email address
4. Save the settings

### Customizing Notifications
1. Set update frequency (how often to check for changes)
2. Choose which tiers and weights to monitor
3. Select specific products to track (optional)
4. Toggle notifications for:
   - New products
   - Stock changes
   - Removed products

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Responsive design for all screen sizes
- Local storage for settings persistence
- Cache system for improved performance
- Real-time product monitoring

## Browser Compatibility

The application is compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Privacy

- No user data is collected
- All settings are stored locally in your browser
- Notifications are sent through encrypted channels
- Email addresses are only used for notifications

## Contributing

Feel free to submit issues and enhancement requests!

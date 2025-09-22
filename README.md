# Agora RTC Standard Duration Calculator

A web-based calculator for computing Agora RTC standard duration based on different roles and video types. Built with a dark theme matching the Agora console aesthetic.

## Features

- **Three Role Types**: Host, Interactive Live Audience, and Broadcast Streaming Audience
- **Five Video Types**: Audio, HD Video, Full HD, 2K, and 2K+
- **Real-time Calculations**: Shows detailed breakdown for each input
- **Inline Results**: Calculations appear directly under each input field
- **Professional Formatting**: Numbers display with comma separators for easy reading
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Matches Agora console styling

## Usage

1. Open `index.html` in your web browser
2. Enter minutes for any combination of roles and video types
3. View real-time calculations and totals
4. See conversion coefficients in the sidebar reference

## Conversion Coefficients

| Role | Audio | HD Video | Full HD | 2K | 2K+ |
|------|-------|----------|---------|----|----|
| Host | 1 | 4 | 9 | 16 | 36 |
| Interactive Live Audience | 1 | 4 | 9 | 16 | 36 |
| Broadcast Streaming Audience | 0.57 | 2 | 4.57 | 8 | 18 |

## Example

Entering 1000 minutes for HD Video as a Host:
- Input: 1000 minutes
- Calculation: 1,000 × 4 = 4,000 standard minutes
- Result: 4,000 standard minutes

## Technical Details

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Responsive grid layout
- Real-time calculation updates
- Professional number formatting

## Browser Support

Works in all modern browsers that support:
- CSS Grid
- JavaScript ES6+
- Number formatting APIs

## License

Open source - feel free to use and modify as needed.

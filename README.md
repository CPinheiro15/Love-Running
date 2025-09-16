# Love Running

🔗 **Live Site**: [Love Running](https://d2ty24l1gpxkta.cloudfront.net/)

A responsive website for a Dublin-based running community that organizes regular group runs at various urban and trail locations. The site showcases the physical, mental, and social benefits of running, features a gallery of diverse running events, and includes a sign-up form for new members.

## Features

- **Home Page**: Highlights benefits of running with a weekly schedule of organized runs
- **Gallery**: Showcases various running events, races, and fun runs
- **Sign Up**: Form for new members to join the community with preferences for road/trail running
- **Responsive Design**: Mobile-first approach ensuring accessibility across all devices

## Technologies Used

- HTML5
- CSS3
- AWS S3 (static website hosting)
- AWS CloudFront (CDN with Origin Access Control for secure access)

## User Experience

The website targets running enthusiasts of all levels looking to join a supportive community. It emphasizes:

- Physical health benefits of regular running
- Mental wellbeing through exercise and social connection
- Community spirit and group motivation

## Deployment

The site is deployed on AWS S3 with CloudFront:

1. Uploaded static files (HTML, CSS, images) to a private S3 bucket
2. Configured CloudFront distribution with Origin Access Control to securely serve the content
3. Enabled HTTPS and caching via CloudFront for global accessibility and improved performance
4. Site is accessible via the CloudFront URL: https://d2ty24l1gpxkta.cloudfront.net

## Testing

- Tested across multiple browsers (Chrome, Firefox, Safari)
- Responsive design checked on various device sizes
- Form validation ensures proper data collection

## Future Enhancements

- Interactive maps for running routes
- Member profiles and achievements
- Integration with fitness tracking apps

## Credits

- All images are royalty-free stock photos
- Content written specifically for Love Running community
- Icons from Font Awesome

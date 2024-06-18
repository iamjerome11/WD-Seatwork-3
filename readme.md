# Overview

## Header and Footer Components

This project consists of a simple HTML and CSS structure that includes headers and footers for a sports-themed website. Each section of the website is represented by different headers and footers, showcasing various sports such as Basketball, Volleyball, Tennis, Football, and Soccer. The headers include navigation links, and the footers provide different types of information and links.

### Header

The header component is designed to provide a consistent navigation experience across the website. Each header includes:
- A logo and title for the sport.
- Navigation links to Home, Contact, Services, and About pages.
- Icons from Font Awesome for enhanced visual representation.

### Footer

There are five types of footers implemented, each serving a different purpose:

1. **Basic Footer**: A simple footer with a copyright notice.
2. **Social Media Footer**: Includes links to social media profiles (Facebook, Twitter, Instagram, TikTok) with corresponding icons.
3. **Navigation Footer**: Contains navigation links similar to the header for easy access.
4. **Contact Information Footer**: Displays contact information including an email address and a phone number.
5. **Newsletter Subscription Footer**: Provides a form for users to subscribe to a newsletter.

### Technologies Used

- **HTML**: To structure the content of the web pages.
- **CSS**: For styling the headers and footers.
- **Font Awesome**: For including icons in the headers and footers.

### How to Use

1. Include the HTML structure in your main HTML file.
2. Link to the provided CSS file for styling.
3. Ensure Font Awesome is linked in the HTML `<head>` for the icons to display correctly.

### File Structure

- `index.html`: Contains the HTML structure for headers and footers.
- `style.css`: Includes the CSS styles for the headers and footers.
- `assets/`: Directory containing images and other assets used in the headers.

### Example

Below is a simple example of how the header and footer are implemented in HTML and styled using CSS:

#### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footers</title>
    <link rel="stylesheet" href="./assets/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <!-- Example Header -->
    <header>
        <div class="logo">
            <img src="./assets/img/basketball.jpg" alt="Basketball">
            <h2>BASKETBALL</h2>
        </div>
        <div class="nav">
            <a href="#"><i class="fas fa-home"></i> Home</a>
            <a href="#"><i class="fas fa-phone"></i> Contact</a>
            <a href="#"><i class="fas fa-check-circle"></i> Services</a>
            <a href="#"><i class="fas fa-user-circle"></i> About</a>
        </div>
    </header>

    <!-- Example Footer -->
    <footer id="basic-footer">
        <p>&copy; 2024 Basketball. All Rights Reserved.</p>
    </footer>
</body>
</html>

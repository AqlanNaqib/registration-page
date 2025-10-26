# FitnessHub Registration Page

A modern, responsive HTML5 registration form with comprehensive validation and interactive features.

## Features

### ✅ Required Elements

1. **Semantic HTML5 Structure**
   - `<header>` - Logo and branding
   - `<main>` - Main content area
   - `<section>` - Registration section
   - `<footer>` - Copyright and contact info

2. **Complete Registration Form**
   - Full Name (text input with pattern validation)
   - Email Address (email type with required attribute)
   - Password with confirmation (password type with strength meter)
   - Date of Birth (date picker)
   - Phone Number (tel type with pattern)
   - Username (text input with datalist suggestions)
   - Gender (radio buttons)
   - Interests (checkboxes)
   - Profile Picture Upload (file input)
   - Submit and Reset buttons

3. **HTML5 Validation**
   - `required` - Ensures fields are not empty
   - `pattern` - Validates password format, phone number, username
   - `min/max` - Date range validation
   - `minlength/maxlength` - Character limits
   - `autofocus` - Focuses first field on page load
   - `placeholder` - User-friendly hints
   - `autocomplete` - Browser autocomplete support

### 🎁 Bonus Features

1. **Password Strength Meter** - Real-time visual feedback using `<meter>` element
2. **Color Picker** - Users can choose a theme color with `<input type="color">`
3. **Audio/Video Elements** - Placeholders for welcome video and background music
4. **Modern CSS Styling**
   - Gradient background
   - Centered form with rounded corners
   - Hover effects on buttons
   - Responsive mobile-friendly layout
   - Custom focus states
   - Error message styling

## How to Use

1. Open `index.html` in any modern web browser
2. The form will automatically validate inputs as you type
3. Watch the password strength meter update in real-time
4. Try the color picker to customize the theme
5. Fill in all required fields (marked with red asterisks *)
6. Select at least one interest checkbox
7. Click "Create Account" to submit (triggers validation)
8. Click "Reset" to clear all fields

## File Structure

```
registration_page/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
└── README.md       # This file
```

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Form Validation Rules

- **Full Name**: 2-50 characters, letters only
- **Email**: Must be valid email format
- **Password**: Minimum 8 characters with letters and numbers
- **Date of Birth**: Must be before 2010
- **Phone**: International format supported
- **Username**: 3-20 characters, alphanumeric and underscore only
- **Gender**: Must select one option
- **Interests**: Must select at least one

## Customization

### Change Theme Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    /* ... */
}
```

### Add Audio/Video Content
Replace the `#` placeholders in the HTML with actual file paths:
```html
<source src="path/to/video.mp4" type="video/mp4">
<source src="path/to/audio.mp3" type="audio/mpeg">
```

## Accessibility Features

- Semantic HTML5 elements for screen readers
- Proper label associations
- Keyboard navigation support
- ARIA-friendly error messages
- High contrast color scheme
- Focus indicators on interactive elements

## Credits

Created for educational purposes demonstrating HTML5 form elements and validation.


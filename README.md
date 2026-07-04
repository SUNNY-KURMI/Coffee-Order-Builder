# ☕ Coffee Order Builder

An interactive web application for building and customizing coffee orders with real-time visual feedback and pricing calculation.

## Features

- **Drink Selection**: Choose from 5 different beverages
  - Espresso
  - Latte
  - Cappuccino
  - Matcha
  - Chai

- **Size Options**: Small, Medium, or Large with size-based pricing

- **Milk Choices**: Regular, Oat, Almond, Soy, or No Milk

- **Extras & Add-ons**: 
  - Extra Shot
  - Vanilla Syrup
  - Caramel Syrup
  - Whipped Cream

- **Visual Coffee Cup**: Interactive cup that changes color and fill level based on your selections

- **Live Order Summary**: Real-time display of your selections with itemized pricing and total cost

- **Responsive Design**: Works seamlessly across different screen sizes

## Project Structure

```
Coffee-Order-Builder/
├── index.html      # HTML structure and markup
├── style.css       # Styling and animations
├── script.js       # Interactive functionality and state management
└── README.md       # Documentation (this file)
```

## How to Use

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. **Customize your order** by selecting:
   - Your preferred drink
   - Cup size
   - Milk type
   - Any extras you'd like to add
4. **View the results** in real-time:
   - The coffee cup visualization updates with the drink color and fill level
   - Badges appear on the cup to indicate selected extras
   - The summary panel shows itemized costs and total price

## Technologies Used

- **HTML5**: Semantic markup with ARIA labels for accessibility
- **CSS3**: Modern styling with CSS variables, flexbox, and animations
- **JavaScript (ES6+)**: Dynamic state management and DOM manipulation

## Pricing

Prices are displayed in Indian Rupees (₹):

**Base Drinks:**
- Espresso: ₹2.50
- Latte: ₹3.80
- Cappuccino: ₹3.60
- Matcha: ₹4.00
- Chai: ₹3.40

**Size Upcharges:**
- Small: No upcharge
- Medium: +₹0.50
- Large: +₹1.00

**Extras:**
- Extra Shot: +₹0.75
- Vanilla Syrup: +₹0.60
- Caramel Syrup: +₹0.60
- Whipped Cream: +₹0.50

## Features Highlights

### Interactive Cup Visualization
- The cup color changes based on the selected drink
- The fill level adjusts according to the cup size
- Badges with symbols appear on the cup to show selected extras

### Live Summary
- Real-time calculation of total cost
- Itemized breakdown of all selections
- Accessible order summary with live region updates

### Accessibility
- Semantic HTML structure
- ARIA labels for visual elements
- Keyboard navigable form controls

## Future Enhancements

- Add order history tracking
- Implement "Favorite Orders" feature
- Add seasonal drink specials
- Include allergen information
- Add local storage for saved orders
- Implement order submission functionality

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available for personal and educational use.

## Author

Created by [SUNNY-KURMI](https://github.com/SUNNY-KURMI)

---

Enjoy building your perfect coffee order! ☕✨

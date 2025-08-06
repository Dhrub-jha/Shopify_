# Prachi & Sisters - E-Commerce Platform

A handcrafted floral jewelry e-commerce website built with vanilla HTML, CSS, and JavaScript. This single-page application provides a complete shopping experience with product browsing, cart management, and checkout functionality.

## 🌟 Features

### Core Functionality
- **Product Display**: Grid-based product showcase with dynamic filtering
- **Shopping Cart**: Sidebar cart with add/remove/quantity management
- **Search**: Real-time product search functionality
- **Responsive Design**: Mobile-first approach with responsive layouts
- **Interactive UI**: Smooth animations and hover effects

### Product Categories
- Necklaces
- Earrings
- Bangles
- Jewelry Sets

### Cart Features
- Add/remove products
- Quantity adjustment
- Price calculation with tax and shipping
- Persistent cart state during session
- Empty cart state handling

## 🏗️ Architecture

### File Structure
```
Shopify_/
└── shopify-clone.html    # Single-page application containing all code
```

### Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Icons**: Font Awesome 6.0.0
- **Fonts**: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, etc.)

## 📱 Components

### 1. Header & Navigation
```html
<header>
  <nav>
    <a href="#" class="logo">Prachi & Sisters</a>
    <ul class="nav-links">...</ul>
    <div class="nav-actions">
      <div class="search-bar">...</div>
      <button class="cart-btn">...</button>
    </div>
  </nav>
</header>
```

**Features:**
- Sticky navigation bar
- Logo with leaf icon
- Search functionality
- Cart button with item counter
- Responsive navigation (mobile-friendly)

### 2. Hero Section
```html
<section class="hero">
  <h1>Handcrafted Floral Jewelry</h1>
  <p>Beautiful traditional designs for every occasion</p>
  <button class="cta-btn">Shop Now</button>
</section>
```

**Features:**
- Gradient background
- Call-to-action button
- Smooth scroll to products section

### 3. Products Section
```html
<section class="products-section">
  <div class="section-header">...</div>
  <div class="filters">...</div>
  <div class="products-grid">...</div>
</section>
```

**Features:**
- Category filtering system
- Dynamic product grid
- Product cards with hover effects
- Add to cart functionality

### 4. Cart Sidebar
```html
<div class="cart-sidebar">
  <div class="cart-header">...</div>
  <div class="cart-items">...</div>
  <div class="cart-total">...</div>
</div>
```

**Features:**
- Slide-in sidebar animation
- Item quantity controls
- Price calculations (subtotal, tax, shipping)
- Checkout functionality

### 5. Footer
```html
<footer>
  <div class="footer-content">...</div>
  <div class="footer-bottom">...</div>
</footer>
```

**Features:**
- Multi-column layout
- Social media links
- Contact information
- Company branding

## 💾 Data Structure

### Product Object
```javascript
{
  id: number,           // Unique identifier
  title: string,        // Product name
  description: string,  // Product description
  price: number,        // Price in USD
  category: string,     // Product category
  icon: string         // Emoji icon for display
}
```

### Cart Item Object
```javascript
{
  ...product,          // All product properties
  quantity: number     // Quantity in cart
}
```

## 🔧 Key Functions

### Product Management
- `displayProducts(productsToShow)` - Renders product grid
- `filterProducts(category)` - Filters products by category
- Search functionality through event listener

### Cart Management
- `addToCart(productId)` - Adds product to cart
- `updateCartDisplay()` - Updates cart UI and calculations
- `updateQuantity(productId, change)` - Modifies item quantity
- `removeFromCart(productId)` - Removes item from cart
- `toggleCart()` - Shows/hides cart sidebar

### Utility Functions
- `checkout()` - Processes checkout (demo mode)
- Smooth scrolling for navigation
- Search filtering

## 🎨 Styling Features

### CSS Architecture
- **Reset**: Universal box-sizing and margin/padding reset
- **Variables**: Consistent color scheme and spacing
- **Grid System**: CSS Grid for product layout
- **Flexbox**: Navigation and component alignment
- **Animations**: Hover effects, transitions, and keyframe animations

### Color Palette
- Primary: `#5C6AC4` (Purple)
- Secondary: `#27ae60` (Green)
- Accent: `#ff4757` (Red for cart counter)
- Text: `#333` (Dark gray)
- Background: `#f8f9fa` (Light gray)

### Responsive Breakpoints
- Mobile: `max-width: 768px`
- Tablet: `768px - 1200px`
- Desktop: `1200px+`

## 📱 Responsive Design

### Mobile Optimizations
- Hidden navigation links on mobile
- Full-width cart sidebar
- Reduced search bar width
- Smaller grid columns
- Touch-friendly button sizes

### Tablet Adaptations
- Flexible grid system
- Maintained sidebar width
- Optimized spacing

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required (static HTML file)

### Installation
1. Clone or download the repository
2. Open `shopify-clone.html` in a web browser
3. No build process or dependencies required

### Usage
1. Browse products using category filters
2. Search for specific items
3. Add products to cart
4. Manage cart quantities
5. Proceed to checkout (demo mode)

## 🔄 State Management

### Client-Side State
- Cart items stored in JavaScript array
- No persistent storage (resets on page reload)
- Real-time UI updates

### Data Flow
1. User interaction triggers event
2. JavaScript function updates data
3. UI components re-render
4. Visual feedback provided

## 🎯 Performance Features

### Optimization Techniques
- Single HTML file (minimal HTTP requests)
- CSS animations for smooth interactions
- Efficient DOM manipulation
- Lazy rendering of cart items

### User Experience
- Instant visual feedback on interactions
- Smooth transitions and animations
- Loading states and empty states
- Error handling for edge cases

## 🔮 Future Enhancements

### Potential Features
- User authentication
- Product image gallery
- Wishlist functionality
- Order history
- Payment integration
- Product reviews and ratings
- Advanced filtering (price range, ratings)
- Multi-language support
- Dark mode theme

### Technical Improvements
- State persistence (localStorage)
- API integration
- Component modularity
- Testing framework
- Build optimization
- Progressive Web App features

## 📄 License

This project is for educational and demonstration purposes. All product data is fictional.

## 👥 Contributing

This is a demo project. For educational purposes, feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Report issues

## 📞 Contact

- Email: payalagrawal084@gmail.com
- Website: Prachi & Sisters (Demo)

---

*Built with ❤️ for handcrafted jewelry lovers*

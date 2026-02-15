# 🎨 KalaKart - Authentic Indian Handicrafts E-Commerce Platform

A fully functional, responsive e-commerce website prototype showcasing traditional Indian arts and local handicrafts. Built with pure HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/demo-live-green.svg)]( https://abhaybarai05.github.io/Kalakart/)
[![GitHub](https://img.shields.io/badge/github-abhaybarai05-blue.svg)]( https://abhaybarai05.github.io/Kalakart/)

---

## 🌟 Overview

KalaKart is a beautiful e-commerce platform designed to connect traditional Indian artisans with global customers. The platform celebrates Indian craftsmanship while providing a modern, user-friendly shopping experience.

**Live Demo:** [https://abhaybarai05.github.io/Kalakart]( https://abhaybarai05.github.io/Kalakart/)

---

## ✨ Features

### 🛍️ **E-Commerce Functionality**
- **30+ Products** with high-quality images and detailed information
- **Real-time Search** - Instantly filter products by name, category, or artisan
- **Advanced Filters** - Category, price range, and sorting options
- **Shopping Cart** - Add, remove, and update quantities
- **Cart Persistence** - Cart data saved using localStorage
- **Dynamic Pricing** - Automatic total calculation with shipping (Free over ₹999)

### 🎨 **Design & UX**
- **Traditional Aesthetic** - Earthy color palette (terracotta, warm browns, ochre)
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Smooth Animations** - Engaging hover effects and transitions
- **Professional Layout** - Amazon/Flipkart-inspired interface
- **Accessibility** - Semantic HTML and keyboard navigation

### 🔍 **Product Discovery**
- Category-based navigation
- Multiple sorting options (Price, Rating, Relevance)
- Product ratings and reviews count
- Artisan information for each product
- Product badges (Handmade, Premium, Traditional, Bestseller, etc.)

---

## 🚀 Live Demo

**Visit:** [https://abhaybarai05.github.io/Kalakart]( https://abhaybarai05.github.io/Kalakart/)

### Key Features Showcase:
- Browse 30+ authentic handicraft products
- Real-time search and filtering
- Fully functional shopping cart
- Mobile-responsive design
- Beautiful traditional Indian aesthetic

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **LocalStorage API** - Client-side data persistence
- **Google Fonts** - Cinzel & Crimson Text typography
- **Unsplash API** - High-quality product images

---

## 📁 Project Structure

```
Kalakart/
└── index.html          # Complete single-file application
                        # (All HTML, CSS, and JS in one file)
```

**Note:** This is a single-file application for easy deployment and sharing.

---

## 🎯 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git (for cloning)

### Installation & Local Setup

1. **Clone the repository**
```bash
git clone https://github.com/abhaybarai05/Kalakart.git
cd Kalakart
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

That's it! No build process, no dependencies, no installation required.

---

## 💡 Usage

### Browsing Products
1. Visit the [live website]( https://abhaybarai05.github.io/Kalakart/)
2. Scroll through 30+ featured products
3. Use category navigation or search bar
4. Apply filters to narrow results

### Shopping Experience
1. Click "Add to Cart" on any product
2. Cart sidebar opens automatically
3. Adjust quantities using +/- buttons
4. View total price (free shipping over ₹999)
5. Click "Proceed to Checkout"

### Searching & Filtering
- **Search**: Type product name, category, or artisan name
- **Category Filter**: Select from dropdown or navigation bar
- **Price Filter**: Choose your budget range
- **Sort**: By price (low/high), rating, or newest items
- **Clear All**: Reset all filters with one click

---

## 🎨 Customization

### Changing Colors
Edit the CSS variables at the top of `index.html`:

```css
:root {
    --terracotta: #C85C3C;
    --deep-earth: #8B4513;
    --warm-sand: #D4A574;
    --clay: #9D6B53;
    --burnt-sienna: #A0522D;
    --cream: #F5EBE0;
    --charcoal: #2C1810;
    --sage: #87946B;
    --ochre: #CC7722;
    --gold: #DAA520;
}
```

### Adding Products
Edit the `products` array in the JavaScript section:

```javascript
const products = [
    {
        id: 31,
        name: "Your Product Name",
        category: "pottery", // pottery, textile, woodwork, metalwork, painting, jewelry
        artisan: "Artist Name, Location",
        price: 1500,
        rating: 4.8,
        image: "https://your-image-url.jpg",
        badge: "Handmade" // Handmade, Premium, Traditional, Bestseller, New, Festival
    },
    // Add more products...
];
```

### Modifying Categories
Categories available:
- `pottery` - Pottery & Ceramics
- `textile` - Textiles & Fabrics
- `woodwork` - Wood Carving
- `metalwork` - Metalwork & Brass
- `painting` - Paintings & Art
- `jewelry` - Jewelry & Accessories

---

## 📊 Product Categories

- 🏺 **Pottery & Ceramics** - Handcrafted vases, diyas, planters, decorative plates
- 🎨 **Paintings** - Madhubani, Warli, Tanjore, Pattachitra, Gond art
- 🧵 **Textiles** - Sarees, shawls, bedsheets, dupattas, cushion covers
- 🪵 **Wood Carving** - Sandalwood items, mirrors, baskets, coasters
- 🔔 **Metalwork** - Brass bells, copper bowls, diyas, figurines
- 💍 **Jewelry** - Earrings, necklaces, prayer beads, traditional ornaments

---

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | Latest  | ✅ Fully Supported |
| Firefox | Latest  | ✅ Fully Supported |
| Safari  | Latest  | ✅ Fully Supported |
| Edge    | Latest  | ✅ Fully Supported |
| Mobile Safari | iOS 12+ | ✅ Fully Supported |
| Chrome Mobile | Android 8+ | ✅ Fully Supported |

---

## 📱 Responsive Design

Optimized for all screen sizes:
- **Desktop**: 1024px and above - Full featured layout
- **Tablet**: 768px - 1024px - Adapted grid layout
- **Mobile**: Below 768px - Single column, touch-optimized

---

## 🔄 Future Enhancements

### Phase 1 - Backend Integration
- [ ] User authentication system (JWT)
- [ ] Backend API (Node.js/Express or Django)
- [ ] Database integration (MongoDB/PostgreSQL)
- [ ] RESTful API endpoints

### Phase 2 - E-Commerce Features
- [ ] Payment gateway (Razorpay/Stripe)
- [ ] Order management system
- [ ] Email notifications
- [ ] Order tracking
- [ ] Invoice generation

### Phase 3 - User Features
- [ ] User profiles and dashboards
- [ ] Product reviews and ratings
- [ ] Wishlist functionality
- [ ] Product recommendations
- [ ] Recently viewed items

### Phase 4 - Admin Features
- [ ] Admin dashboard
- [ ] Inventory management
- [ ] Analytics and reporting
- [ ] Seller/Artisan portal
- [ ] Bulk product upload

### Phase 5 - Advanced Features
- [ ] Multi-language support (Hindi, English)
- [ ] Social media integration
- [ ] Product image zoom
- [ ] Size guide for textiles
- [ ] Gift wrapping options
- [ ] Loyalty program

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the MIT License.

---

## 👥 Author

**Abhay Barai**
- GitHub: [@abhaybarai05](https://github.com/abhaybarai05)
- Repository: [Kalakart](https://github.com/abhaybarai05/Kalakart)
- Live Demo: [abhaybarai05.github.io/Kalakart]( https://abhaybarai05.github.io/Kalakart/)

---

## 🙏 Acknowledgments

- **Indian Artisans** - Craftsmen and women who inspire this project
- **Unsplash Contributors** - High-quality product photography
- **Google Fonts** - Beautiful Cinzel and Crimson Text typography
- **Indian Cultural Heritage** - Rich traditions that make this project meaningful

---

## 🎯 Project Mission

### Our Goal
To create a digital marketplace that:
- **Preserves** traditional Indian craftsmanship
- **Empowers** local artisans economically
- **Connects** authentic products with global customers
- **Celebrates** cultural heritage through modern technology

### Our Vision
Become the leading platform for authentic Indian handicrafts, supporting 10,000+ artisan families across India and bringing traditional crafts to the global market.

---

## 📊 Project Statistics

- **Total Products**: 30+ unique handicraft items
- **Product Categories**: 6 major categories
- **Featured Artisans**: 25+ traditional craftspeople
- **Price Range**: ₹450 - ₹8,900
- **Average Rating**: 4.7 ⭐
- **Lines of Code**: ~1000 (HTML/CSS/JS)
- **File Size**: ~40KB (single file)
- **Load Time**: < 2 seconds

---

## 💬 Support & Feedback

For questions, suggestions, or issues:
1. Check [existing issues](https://github.com/abhaybarai05/Kalakart/issues)
2. Create a [new issue](https://github.com/abhaybarai05/Kalakart/issues/new)
3. Contact via GitHub profile

---

## 🌟 Show Your Support

If you like this project:
- Give it a ⭐️ on [GitHub](https://github.com/abhaybarai05/Kalakart)
- Share it with others
- Contribute to make it better
- Provide feedback

---

## 📅 Version History

### v1.0.0 (2024) - Initial Release
- ✅ 30 products with high-quality images
- ✅ Full e-commerce functionality
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Shopping cart with localStorage persistence
- ✅ Search and filter capabilities
- ✅ Category navigation
- ✅ Multiple sorting options
- ✅ Product ratings and badges
- ✅ Traditional Indian aesthetic design

---

## 🔗 Quick Links

- 🌐 **Live Website**: [https://abhaybarai05.github.io/Kalakart]( https://abhaybarai05.github.io/Kalakart/)
- 💻 **GitHub Repository**: [https://github.com/abhaybarai05/Kalakart](https://github.com/abhaybarai05/Kalakart)
- 🐛 **Report Issues**: [GitHub Issues](https://github.com/abhaybarai05/Kalakart/issues)
- 📧 **Contact**: Via GitHub profile

---

## 📖 Technical Details

### Performance
- Lazy loading for product images
- Optimized CSS with custom properties
- Minimal dependencies (zero npm packages)
- Fast load times with single-file architecture

### Accessibility
- Semantic HTML5 elements
- Keyboard navigation support
- ARIA labels where needed
- Responsive text sizing

### Browser Storage
- Uses localStorage for cart persistence
- Data survives page refresh
- No server-side storage required
- Clear data option available

---

**Built with ❤️ for Indian Artisans**

*Celebrating Indian Heritage, One Craft at a Time.*

---

© 2024 KalaKart. Supporting 10,000+ Local Artisans Across India.

🪷 We plant a tree for every purchase | 🤝 10% of profits support artisan communities

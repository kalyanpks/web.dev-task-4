# Personal Portfolio Website

A modern, responsive multi-page personal portfolio website with built-in interactive tools including a To-Do list app and Product Showcase.

## 🌟 Features

### 📱 Responsive Design
- Mobile-first approach with responsive breakpoints
- Modern UI with smooth animations and transitions
- Cross-browser compatibility

### 🏠 Homepage (index.html)
- Hero section with typing animation effect
- Professional profile introduction
- Skills preview with animated cards
- Smooth scroll navigation

### 👤 About Page (about.html)
- Personal information and background
- Animated progress bars for skills
- Interactive timeline for education and experience
- Services offered section

### 🛠️ Projects Page (projects.html)
- **To-Do List Application**
  - Add, edit, delete tasks
  - Filter by status (All, Pending, Completed)
  - Local storage persistence
  - Real-time statistics
  - Clear completed/all tasks functionality

- **Product Showcase**
  - Dynamic product cards
  - Category filtering
  - Sorting by name, price, rating, date
  - Product detail modal
  - Interactive rating system

### 📞 Contact Page (contact.html)
- Contact form with real-time validation
- Professional contact information
- Social media links
- Form submission handling
- Success/error notifications

## 🛠️ Tech Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality
- **LocalStorage API** - Data persistence for To-Do app
- **AOS (Animate On Scroll)** - Smooth scroll animations
- **Font Awesome** - Icon library

## 📁 Project Structure

```
portfolio/
├── index.html              # Homepage
├── about.html              # About page
├── projects.html           # Projects page with tools
├── contact.html            # Contact page
├── css/
│   ├── style.css           # Main stylesheet
│   ├── about.css           # About page styles
│   ├── projects.css        # Projects page styles
│   └── contact.css         # Contact page styles
├── js/
│   ├── app.js              # Main JavaScript functionality
│   ├── todo.js             # To-Do list application
│   ├── products.js         # Product showcase functionality
│   └── contact.js          # Contact form handling
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. **Clone or download the project**
   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. **Open in browser**
   - Double-click `index.html` to open in your default browser
   - Or use a local server for better development experience

3. **Using a local server (recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the website**
   - Open your browser and navigate to `http://localhost:8000`

## 🎯 Key Features Explained

### To-Do List Application
- **Local Storage**: Tasks persist between browser sessions
- **CRUD Operations**: Create, Read, Update, Delete tasks
- **Filtering**: View all, pending, or completed tasks
- **Statistics**: Real-time count of total, completed, and pending tasks
- **Responsive**: Works seamlessly on all device sizes

### Product Showcase
- **Dynamic Content**: Products loaded from JavaScript array
- **Filtering**: Filter by category (Web, Mobile, Design, Tools)
- **Sorting**: Sort by name, price, rating, or date added
- **Modal Details**: Click to view detailed product information
- **Interactive**: Add to cart functionality with notifications

### Contact Form
- **Real-time Validation**: Instant feedback on form inputs
- **Email Validation**: Proper email format checking
- **Loading States**: Visual feedback during submission
- **Success Handling**: Confirmation messages and form reset
- **Extensible**: Ready for integration with Formspree or EmailJS

## 🎨 Customization

### Personal Information
Update the following files to customize your information:
- `index.html` - Hero section, name, title
- `about.html` - Personal details, skills, experience
- `contact.html` - Contact information
- `js/products.js` - Product showcase items

### Styling
- Modify `css/style.css` for global styles
- Update color scheme in CSS variables
- Customize animations and transitions

### Adding New Features
- Extend the To-Do app with categories or due dates
- Add more interactive elements to the product showcase
- Integrate with external APIs for dynamic content

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please open an issue in the repository or contact the developer.

---

**Built with ❤️ using modern web technologies** 
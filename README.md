# 🎯 Sorting Visualizer

<p align="center">
  <a href="https://sorting-proj-nyfd.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-View%20Here-brightgreen?style=for-the-badge" alt="Live Demo"/>
  </a>
  <a href="https://github.com/pran-ekaiva006/sorting-project" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub Repo"/>
  </a>
  <img src="https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=for-the-badge&logo=javascript" alt="Made with JavaScript"/>
  <img src="https://img.shields.io/badge/Responsive-Design-purple?style=for-the-badge" alt="Responsive Design"/>
</p>

<p align="center">
  <b>An interactive web application that brings sorting algorithms to life through stunning visualizations</b>
</p>

<p align="center">
  The Sorting Visualizer is built with HTML, CSS, and JavaScript to demonstrate how different sorting algorithms work step by step. Users can adjust array size and animation speed to better understand algorithm behavior, featuring clear visual representations of comparisons and swaps that make learning sorting algorithms engaging and intuitive.
</p>

---

## 📑 Table of Contents
- [🚀 Live Demo](#-live-demo)  
- [📂 Repository](#-repository)  
- [✨ Features](#-features)  
- [🛠️ Tech Stack](#️-tech-stack)  
- [📂 Folder Structure](#-folder-structure)  
- [📸 Preview](#-preview)  
- [⚙️ Installation & Setup](#️-installation--setup)  
- [🎮 Usage](#-usage)  
- [📖 Learning Outcomes](#-learning-outcomes)  
- [🤝 Contributing](#-contributing)  
- [📜 License](#-license)  
- [💡 Author](#-author)  

---

## 🚀 Live Demo

Experience the interactive sorting visualizer in action:

🔗 **[Sorting Visualizer Live Demo](https://sorting-proj-nyfd.vercel.app)**

---

## 📂 Repository

Access the complete source code:

🔗 **[GitHub Repository](https://github.com/pran-ekaiva006/sorting-project)**

---

## ✨ Features

- 🎨 **Interactive Visualization** - Watch algorithms come to life with smooth animations
- ⚡ **Customizable Parameters** - Adjust array size (10-100 elements) and animation speed
- 📊 **Multiple Algorithms** supported:
  - **Bubble Sort** - Simple comparison-based algorithm
  - **Selection Sort** - Find minimum and swap approach  
  - **Insertion Sort** - Build sorted array one element at a time
  - **Merge Sort** - Efficient divide-and-conquer algorithm
  - **Quick Sort** - Fast partition-based sorting
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- 📈 **Performance Metrics** - Real-time comparison and swap counters
- 🎨 **Color-Coded Elements** - Visual indicators for different algorithm states
- 🔄 **Reset Functionality** - Generate new random arrays instantly

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Modern styling with Flexbox/Grid |
| **JavaScript (ES6+)** | Algorithm logic and DOM manipulation |
| **CSS Animations** | Smooth visual transitions |
| **Vercel** | Deployment and hosting |
| **Git** | Version control |

---

## 📂 Folder Structure  

```bash
sorting-project/
├── 📄 index.html          # Main entry point with HTML structure
├── 🎨 style.css           # Comprehensive styling and animations
├── ⚙️ script.js           # Core logic & sorting algorithm implementations
├── 📁 assets/             # Static resources
│   └── 🖼️ preview.png     # Application screenshot
└── 📋 README.md           # Project documentation
```

---

## 📸 Preview

![Sorting Visualizer Screenshot](assets/preview.png)

*Interactive visualization showing real-time algorithm execution with color-coded elements*

---

## ⚙️ Installation & Setup

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Text editor (VS Code recommended)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/pran-ekaiva006/sorting-project.git
   cd sorting-project
   ```

2. **Launch the application**
   
   **Option 1: Direct Browser Opening**
   ```bash
   # Simply double-click index.html or open with browser
   ```
   
   **Option 2: Local Server (Recommended)**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the application**
   ```
   http://localhost:8000
   ```

---

## 🎮 Usage

### Getting Started
1. **Open the application** in your web browser
2. **Select an algorithm** from the dropdown menu
3. **Adjust settings**:
   - **Array Size**: Control the number of elements (10-100)
   - **Animation Speed**: Set visualization speed (1ms-200ms delay)
4. **Generate New Array** to create random data
5. **Start Sort** to begin the visualization

### Visual Indicators
| Color | Meaning |
|-------|---------|
| 🔵 **Blue** | Unsorted elements |
| 🔴 **Red** | Elements being compared |
| 🟢 **Green** | Elements in final sorted position |
| 🟡 **Yellow** | Pivot element (Quick Sort) or current key (Insertion Sort) |

### Performance Metrics
- **Comparisons**: Number of element comparisons made
- **Swaps**: Number of element swaps performed  
- **Time**: Real-time execution duration

---

## 📖 Learning Outcomes

After exploring this visualizer, you'll gain:

- 📚 **Algorithm Understanding**: Step-by-step comprehension of how sorting algorithms work
- ⏱️ **Time Complexity Insights**: Visual understanding of algorithm efficiency differences
- 🎯 **Performance Analysis**: Ability to compare algorithm performance metrics
- 💻 **Technical Skills**: Knowledge of DOM manipulation and CSS animations
- 🧠 **Problem-Solving**: Enhanced algorithmic thinking and optimization concepts

### Educational Benefits
- **Visual Learning**: See abstract concepts in action
- **Interactive Exploration**: Hands-on experience with different parameters
- **Comparative Analysis**: Direct comparison between algorithm behaviors
- **Real-time Feedback**: Immediate visualization of algorithm decisions

---

## 🤝 Contributing

We welcome contributions! Here's how to get involved:

### How to Contribute
1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit** your changes
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push** to your branch
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open** a Pull Request

### Contribution Ideas
- 🔧 **New Algorithms**: Heap Sort, Radix Sort, Counting Sort
- 🎨 **UI Improvements**: Enhanced animations, dark/light theme toggle
- 📊 **Features**: Algorithm complexity information, sound effects
- 📱 **Mobile**: Touch gesture controls, mobile-optimized interface
- 🧪 **Testing**: Unit tests, performance benchmarks

### Development Guidelines
- Follow existing code style and conventions
- Add comments for complex logic
- Test thoroughly across different browsers
- Update documentation for new features

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Feel free to use, modify, and distribute
```

---

## 💡 Author

**Pranjal Kumar Verma**

- 📧 **Email**: [pranjalverma975@gmail.com](mailto:pranjalverma975@gmail.com)
- 🔗 **GitHub**: [@pran-ekaiva006](https://github.com/pran-ekaiva006)
- 💼 **LinkedIn**: [Connect with me](https://linkedin.com/in/pranjal-verma)
- 🌐 **Portfolio**: [View my work](https://pranjal-portfolio.vercel.app)

---

<div align="center">

### ⭐ Show Your Support

If this project helped you learn something new, please give it a ⭐!

**Made with ❤️ and lots of ☕**

[⬆ Back to Top](#-sorting-visualizer)

</div>

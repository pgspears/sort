# 🔬 Sorting Algorithmns Visualized and Compared

**Interactive Sorting Algorithm Visualizer & Educational Laboratory**

An immersive, browser-based application for learning and comparing sorting algorithms through real-time visualization, comprehensive educational content, and objective performance metrics. Created using Gemini 3 Pro and Claude 4.5.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## ✨ Features

### 🎯 Real-Time Visualization
- Watch 16 different sorting algorithms execute step-by-step
- Color-coded operations: comparisons, swaps, writes, and sorted elements
- Adjustable array size (20-200 elements) and animation speed
- Audio feedback that maps element values to frequencies

### 🏆 Live Leaderboard
- Real-time performance comparison across all algorithms
- Track comparisons, memory operations, and completion time
- Automatic ranking with gold/silver/bronze medals
- Visual progress bars showing algorithm completion status

### 🏁 Race Mode
- Generate identical datasets for all algorithms
- Fair, scientific comparison under controlled conditions
- See which algorithms truly perform best on the same data

### 📚 Interactive Textbook
- 9 comprehensive chapters covering sorting theory
- Topics from basic foundations to quantum computing
- Code examples, complexity analysis, and historical context
- Beautifully formatted with callouts, tables, and syntax highlighting

---

## 📊 Algorithms Included

| Algorithm | Time Complexity | Space | Stable | Category |
|-----------|----------------|-------|--------|----------|
| Bubble Sort | O(n²) | O(1) | ✅ | Educational |
| Selection Sort | O(n²) | O(1) | ❌ | Educational |
| Insertion Sort | O(n²) | O(1) | ✅ | Adaptive |
| Quick Sort | O(n log n) | O(log n) | ❌ | Divide & Conquer |
| Merge Sort | O(n log n) | O(n) | ✅ | Divide & Conquer |
| Heap Sort | O(n log n) | O(1) | ❌ | Selection |
| Shell Sort | O(n log² n) | O(1) | ❌ | Gap Sequence |
| Tim Sort | O(n log n) | O(n) | ✅ | Hybrid |
| Counting Sort | O(n+k) | O(k) | ✅ | Non-Comparison |
| Radix Sort (LSD) | O(nk) | O(n+k) | ✅ | Non-Comparison |
| Bucket Sort | O(n+k) | O(n) | ✅ | Distribution |
| Cocktail Shaker | O(n²) | O(1) | ✅ | Bidirectional |
| Gnome Sort | O(n²) | O(1) | ✅ | Simple |
| Comb Sort | O(n²/2^p) | O(1) | ❌ | Gap Sequence |
| Odd-Even Sort | O(n²) | O(1) | ✅ | Parallel |
| Pancake Sort | O(n²) | O(1) | ❌ | Reversal |

---

## 📖 Educational Content

The built-in textbook covers:

1. **Introduction** - Why sorting is the "fruit fly" of computer science
2. **Foundations** - Deep dive into quadratic algorithms
3. **Complexity** - The O(n log n) lower bound proof
4. **Divide & Conquer** - Merge Sort, Quick Sort, and Heap Sort
5. **Hardware** - Cache hierarchies and memory access patterns
6. **Hybrids** - Tim Sort and Introsort explained
7. **Non-Comparison** - Breaking the theoretical barrier
8. **Exotic** - Unusual and specialized sorting methods
9. **The Future** - GPU sorting, ML-based sorting, quantum algorithms

---

## 🚀 Getting Started

### Option 1: Direct Use
Simply open `index.html` in any modern web browser. No server or build process required.

---

## 🎮 How to Use

### Controls

| Control | Function |
|---------|----------|
| **Array Size** | Adjust the number of elements (20-200) |
| **Speed** | Control animation speed (1-100%) |
| **Visualizers** | View all algorithm cards |
| **Leaderboard** | See performance rankings |
| **Race** | Generate identical data for fair comparison |
| **Reset** | Generate new random data |
| **Run All** | Start all algorithms simultaneously |
| **Learn** | Open the educational sidebar |

### Color Legend

| Color | Meaning |
|-------|---------|
| 🟡 Yellow | Elements being compared |
| 🔴 Red | Elements being swapped |
| 🟣 Purple | Element being written |
| 🟢 Green | Element in final sorted position |

---

## 🛠️ Technical Details

### Built With
- **Pure HTML5, CSS3, JavaScript** - No frameworks or dependencies
- **Web Audio API** - Real-time audio synthesis
- **CSS Grid & Flexbox** - Responsive layout
- **ES6+ Features** - Generators, async iteration, template literals

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### Performance
- Optimized DOM manipulation
- RequestAnimationFrame-based animation loop
- Efficient generator-based algorithm implementations
- Minimal reflows and repaints

---

## 🎓 Learning Objectives

After using this tool, you will understand:

- ✅ How different sorting strategies work visually
- ✅ Why O(n log n) is the theoretical limit for comparison sorts
- ✅ The trade-offs between time complexity, space, and stability
- ✅ How hardware constraints affect algorithm performance
- ✅ When to use which sorting algorithm in practice
- ✅ How hybrid algorithms combine multiple techniques

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

<p align="center">
  <strong>Happy Sorting! 🎉</strong>
</p>

<p align="center">
  <em>"The study of sorting is the study of computation itself."</em>
</p>

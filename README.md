# Smart City Management System

A comprehensive city management system implementing advanced data structures and algorithms with a modern, professional frontend.

## 🎯 Project Overview

This project demonstrates the implementation of various data structures and algorithms in a real-world Smart City Management System. It includes both C++ backend implementations and a modern HTML/CSS/JavaScript frontend.

## 📚 Implemented Data Structures

### 1. **Binary Search Tree (BST)**
- **Location**: Citizen Management Module
- **Operations**: Insert (O(log n)), Search (O(log n)), Delete (O(log n))
- **Features**: In-order traversal for sorted display
- **Use Case**: Efficient searching and sorting of citizen records by ID

### 2. **Hash Table**
- **Location**: Citizen & Utility Management Modules
- **Operations**: Insert (O(1)), Search (O(1) average), Delete (O(1))
- **Features**: Fast lookups by key (ID or Type)
- **Use Case**: Quick citizen lookup and utility type-based queries

### 3. **Linked List**
- **Location**: Hospital Management Module
- **Operations**: Insert (O(1) at beginning/end, O(n) sorted), Search (O(n)), Delete (O(n))
- **Features**: Dynamic size, sorted insertion
- **Use Case**: Managing patient records with flexible insertion

### 4. **Priority Queue (Min Heap)**
- **Location**: Complaint Management Module
- **Operations**: Enqueue (O(log n)), Dequeue (O(log n))
- **Features**: Automatic priority-based ordering
- **Use Case**: Processing complaints by urgency (Emergency > Urgent > Normal)

### 5. **Stack (LIFO)**
- **Location**: Traffic Management Module
- **Operations**: Push (O(1)), Pop (O(1)), Peek (O(1))
- **Features**: Last In First Out processing
- **Use Case**: Managing traffic violations (latest first)

### 6. **Queue (FIFO)**
- **Location**: Complaint Management Module
- **Operations**: Enqueue (O(1)), Dequeue (O(1))
- **Features**: First In First Out processing
- **Use Case**: Standard complaint processing order

### 7. **Graph**
- **Location**: Data Structures Header (Available for city route planning)
- **Operations**: Shortest path (Dijkstra's algorithm)
- **Features**: Adjacency list representation
- **Use Case**: City route optimization

## 🔄 Sorting Algorithms

### 1. **Quick Sort**
- **Time Complexity**: O(n log n) average, O(n²) worst case
- **Space Complexity**: O(log n)
- **Use Case**: Sorting citizens by name, traffic violations by fine

### 2. **Merge Sort**
- **Time Complexity**: O(n log n) guaranteed
- **Space Complexity**: O(n)
- **Use Case**: Sorting citizens by age, utilities by bill amount

## 📁 Project Structure

```
SmartCityProject/
├── SmartCity_Backend/
│   ├── data_structures.h          # All data structure implementations
│   ├── enhanced_citizen_backend.cpp      # BST & Hash Table
│   ├── enhanced_complaint_backend.cpp    # Priority Queue & Queue
│   ├── enhanced_hospital_backend.cpp     # Linked List
│   ├── enhanced_traffic_backend.cpp      # Stack
│   └── enhanced_utility_backend.cpp      # Array & Hash Table
├── SmartCity_Frontend/
│   ├── index.html                # Main dashboard
│   ├── citizen.html              # Citizen management
│   ├── complaint.html           # Complaint management
│   ├── hospital.html             # Hospital management
│   ├── traffic.html              # Traffic management
│   ├── utility.html              # Utility management
│   └── style.css                 # Modern styling
├── SmartCity_Data/
│   ├── citizen.txt
│   ├── complaint.txt
│   ├── hospital.txt
│   ├── traffic.txt
│   └── utility.txt
└── README.md
```

## 🚀 Features

### Backend (C++)
- ✅ Complete CRUD operations for all modules
- ✅ File-based data persistence
- ✅ Advanced data structure implementations
- ✅ Multiple sorting algorithms
- ✅ Statistics and analytics
- ✅ Error handling and validation

### Frontend (HTML/CSS/JavaScript)
- ✅ Modern, responsive UI design
- ✅ Smooth animations and transitions
- ✅ Interactive data structure operations
- ✅ Real-time statistics display
- ✅ LocalStorage for demo purposes
- ✅ Professional color scheme and typography

## 💻 How to Run

### Backend (C++)
1. Navigate to `SmartCity_Backend/` directory
2. Compile any module:
   ```bash
   g++ -std=c++17 enhanced_citizen_backend.cpp -o citizen
   ./citizen
   ```

### Frontend
1. Open `SmartCity_Frontend/index.html` in a web browser
2. Navigate through different modules
3. Use the interactive operations to test data structures

## 📊 Module Details

### 1. Citizen Management
- **Data Structures**: BST, Hash Table, Array
- **Operations**: Add, Search, Delete, Sort, Statistics
- **Sorting**: Quick Sort (by name), Merge Sort (by age)

### 2. Complaint Management
- **Data Structures**: Priority Queue, Queue, Stack
- **Operations**: Add, Process Next, Display by structure type
- **Priority Levels**: Emergency (1), Urgent (2), Normal (3)

### 3. Hospital Management
- **Data Structures**: Singly Linked List
- **Operations**: Add, Search, Delete, Display, Reverse
- **Features**: Sorted insertion by Patient ID

### 4. Traffic Management
- **Data Structures**: Stack
- **Operations**: Push, Pop, Peek, Display, Sort
- **Sorting**: Quick Sort by fine amount

### 5. Utility Management
- **Data Structures**: Array, Hash Table (Map)
- **Operations**: Add, Search, Delete, Sort, Filter by Type
- **Sorting**: Merge Sort by bill amount

## 🎨 Frontend Features

- **Modern Design**: Gradient backgrounds, glassmorphism effects
- **Animations**: Smooth transitions, hover effects, fade-ins
- **Responsive**: Works on desktop, tablet, and mobile
- **Interactive**: Real-time operations with visual feedback
- **Statistics**: Comprehensive analytics for each module

## 🔧 Technical Stack

- **Backend**: C++17
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Data Storage**: File-based (Backend), LocalStorage (Frontend Demo)

## 📈 Time Complexity Summary

| Operation | BST | Hash Table | Linked List | Priority Queue | Stack | Queue |
|-----------|-----|------------|-------------|----------------|--------|-------|
| Insert    | O(log n) | O(1) | O(1)/O(n) | O(log n) | O(1) | O(1) |
| Search    | O(log n) | O(1) | O(n) | - | - | - |
| Delete    | O(log n) | O(1) | O(n) | O(log n) | O(1) | O(1) |
| Access    | O(log n) | O(1) | O(n) | O(log n) | O(1) | O(1) |

## 🎓 Learning Outcomes

This project demonstrates:
- Implementation of fundamental data structures
- Understanding of time/space complexity
- Real-world application of algorithms
- Professional frontend development
- System design and architecture

## 📝 Notes

- The frontend uses LocalStorage for demonstration purposes
- Backend files use actual file I/O for data persistence
- All data structures are implemented from scratch (no STL containers for core structures)
- The project is educational and demonstrates best practices

## 👨‍💻 Author

Smart City Project - Advanced Data Structures Implementation

## 📄 License

Educational Project - Free to use and modify

---

**Made with ❤️ for learning Data Structures and Algorithms**


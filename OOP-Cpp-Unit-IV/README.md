# C++ Programming Project - Unit IV

## Student Details
- **Name**: Harsh penjarla
- **PRN**: 125UAD1139
- **Class/Division**: S.Y. B.Tech (AI & DS)
- **Course Name**: Object Oriented Programming with C++ (ADPC303)
- **Unit**: Unit IV - Files and Streams

---

## Repository Structure
```
OOP-Cpp-Unit-IV/
├── README.md
├── Program_01/
│   └── program01.cpp
├── Program_02/
│   └── program02.cpp
└── Program_03/
    └── program03.cpp
```

---

## List of Programs

### 1. Program 01: Student Record File System
- **File**: `Program_01/program01.cpp`
- **Description**: This program demonstrates file I/O operations using `ofstream` and `ifstream`. It writes student records into a CSV file (`students.csv`), reads them back using `getline()` parsing, and displays a formatted report.

### 2. Program 02: Server Log Analyzer
- **File**: `Program_02/program02.cpp`
- **Description**: This program creates and analyzes server logs. It searches through log lines for error levels (`ERROR` and `CRITICAL`) and aggregates critical system events using vectors and strings.

### 3. Program 03: Binary File for Fixed-Size Records
- **File**: `Program_03/program03.cpp`
- **Description**: This program shows binary file handling in C++. It writes fixed-size image metadata structures to a binary file (`images.bin`) using `write()`, and reads them back sequentially using `read()`.

---

## How to Run the Programs

```bash
# Program 1
g++ Program_01/program01.cpp -o program01
./program01

# Program 2
g++ Program_02/program02.cpp -o program02
./program02

# Program 3
g++ Program_03/program03.cpp -o program03
./program03
```

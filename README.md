# 🚀 CRC-A Network Enhancer

A C++ simulation tool for CRC (Cyclic Redundancy Check)-based error detection in digital communication systems.  
This project was developed as part of the **Computer_Networks_CS425 (2024)** by **Surendra Kumar Ahirwar (Roll No: 211083)**.

# for more information refer to https://github.com/surendrak21/Computer_Networks_CS425

---

## 📌 Overview

**CRC-A Network Enhancer** is a console-based application designed to:
- Generate random binary messages and polynomials.
- Compute CRC and Frame Check Sequence (FCS).
- Introduce random transmission errors.
- Validate the integrity of received frames.

It demonstrates core networking concepts such as:
- Bit-wise XOR operation
- Polynomial division (modulo-2)
- Error detection via CRC remainder analysis

---

## 🧮 Key Features

- ✅ Automatic message and polynomial generation  
- 🧠 Realistic CRC implementation  
- ⚠️ Introduces transmission errors for testing  
- 🧪 Validates frame using CRC remainder  
- 👨‍💻 Offers both randomized and fixed input modes  

---

## 🔧 How to Run

### 1. Clone the Repository

git clone https://github.com/your-username/crc-a-network-enhancer.git
cd crc-a-network-enhancer


## Compile the Code (using g++)
 g++ crc_program.cpp -o crc_program

 ## Run the Executable
    ./crc_program      # On Linux/macOS
    crc_program.exe    # On Windows


### Demo Preview
Upon running the program, you'll be prompted to choose one of the following:

1. Generate CRC from two random strings
2. Generate a 15-bit frame, introduce some errors, and check validity

### Sample Output:
Message M = 110101, Pattern P = 1011
CRC = 100, FCS = 110101100
FCS is Valid! accepted.


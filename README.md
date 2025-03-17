# Memory Management

## Overview
This project focuses on memory management techniques in operating systems. It demonstrates how memory is allocated, managed, and freed efficiently using various memory allocation strategies.

## Features
- Implementation of different memory management techniques
- Simulating memory allocation and deallocation
- Performance analysis of memory management algorithms

## Technologies Used
- C/C++ (for memory management implementation)
- Data structures such as linked lists, arrays
- Operating system concepts

## Installation
1. Clone the repository:

   git clone https://github.com/p-v-srinag/Memory-management.git

2. Navigate to the project directory:

   cd Memory-management

3. Compile the code (if using C or C++):

   gcc memory_management.c -o memory_management   # For C
   g++ memory_management.cpp -o memory_management # For C++

4. Run the program:

   ./memory_management


## Usage
- The program allows users to test different memory management strategies.
- Follow on-screen instructions to input memory requests and observe the allocation process.

## Memory Management Techniques Implemented
- **First-Fit:** Allocates the first available memory block that fits the request.
- **Best-Fit:** Allocates the smallest available memory block that fits the request to minimize fragmentation.
- **Worst-Fit:** Allocates the largest available memory block to reduce external fragmentation.
- **Paging:** Simulated paging memory management technique.
- **Segmentation:** Simulated segmentation memory management approach.

## Example Run

Enter the total memory size: 1000
Enter the process size: 200
Allocating using Best-Fit...
Memory allocated at block starting at address 400


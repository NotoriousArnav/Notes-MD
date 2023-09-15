# Why Study Number Systems?
- The study of number systems is important from the viewpoint of understanding how data is represented before they can be processed by any digital system, including a digital computer.
- It is one of the most basic topics in digital electronics.

## The number systems we are going to cover in our notes include:
- Binary Number System
- Octal Number System
- Decimal Number System
- Hexa-Decimal Number System

## Number Systems Table

| Number System   | Base/Radix | Numbers                                          |
|-----------------|------------|--------------------------------------------------|
| Decimal         | 10         | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9                     |
| Binary          | 2          | 0, 1                                             |
| Octal           | 8          | 0, 1, 2, 3, 4, 5, 6, 7                           |
| Hexadecimal     | 16         | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F |

## Common Terms Related To Number Systems

### 1. Base/Radix
- The most fundamental is the number of independent digits or symbols used in the number system. It is known as the **radix** or **base** of the number system.
- The decimal number system has a radix of 10 with 10 independent digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, and 9.
- Similarly, binary has a radix of 2, octal has a radix of 8, and hexadecimal has a radix of 16.

### 2. Complements
#### Binary Number System
- Bit is an abbreviation of the term 'binary digit' and is the smallest unit of information, either '0' or '1'.
- A byte is a string of eight bits, the basic unit of data in computers.
- The **1’s complement** of a binary number is obtained by complementing all its bits, i.e., replacing 0s with 1s and 1s with 0s.
- The **2’s complement** of a binary number is obtained by adding '1' to its 1’s complement.

#### Decimal Number Systems
- Corresponding to the 1’s and 2’s complements in the binary system, in the decimal number system, we have the 9’s and 10’s complements.
- The **9’s complement** of a given decimal number is obtained by subtracting each digit from 9.
- The **10’s complement** is obtained by adding '1' to the 9’s complement.

### 3. Number Representation in Binary
Different formats used for binary representation of both positive and negative decimal numbers include the **sign-bit magnitude method**, the **1’s complement** method, and the **2’s complement** method.

- **Sign-Bit Magnitude**: In this method, the MSB (Most Significant Bit) represents the 'sign,' with '0' denoting a plus sign and '1' denoting a minus sign. The remaining bits represent the magnitude.

- **One's Complement Method**: For negative numbers, you take the one's complement of the positive binary number by flipping all the bits.

- **Two's Complement Method**: Widely used in computers for representing both positive and negative numbers, you take the one's complement and then add '1' to the result.

### 4. Weighted and Unweighted Number System & Codes
**Weighted Number System:**
- In a weighted number system, each digit's position has a specific weight or significance.
- The value of each digit is determined by multiplying the digit by its weight and summing up these products.
- The decimal, binary, octal, and hexadecimal number systems are examples of weighted systems.

**Unweighted Number System:**
- In an unweighted number system, all digits have equal significance or weight, contributing equally to the number's overall value.
- Unweighted systems are less common and often used for specific purposes. One example is Grey Code.

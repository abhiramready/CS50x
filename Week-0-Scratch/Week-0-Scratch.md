# Week 0 - Scratch

## Computer Science

**Computer Science** is about the goal of **problem solving** using **computational thinking**

Thinking like a computer and applying solutions to problems i.e in a computational way, clean thought process, logical and methodical

## How Data is represented

### Binary

- Humans use base 10 e.g. 123 (read as one hundred twenty-three) = 1 x 100 + 2 x 20 + 3 x 1 (hundreds, tens, and ones place)
- Computers use base-2 or binary using 0's and 1's, Bit comes from the _**Bi**_ nary digi _**t**_
- A Binary system maps readily with electronics as they store electrical charge using transistors like 'on' (1) and 'off' (0)
- Modern devices like laptops and mobiles have millions and billions of transistors. Apple M3 Pro has 37 billion
- In base-2 or binary the number 7 = 111 i.e (1 x 2^2 = 4) + (1 x 2^1 = 2) + (1 x 2^0 = 1)
- If we want 8 we add one more bit 8 = 1000 i.e (1 x 2^3 = 8) + (0 x 2^2 = 0) + (0 x 2^1 = 0) + (0 x 2^0 = 0)
- Data is stored in **bytes**, 1 byte = 8 bits, let's take 1 byte with all 1's 11111111 = can hold 255 or 256 numbers if we consider 0

| ![Light Bulbs used to represent 7 as 111 ( on, on, on)](https://github.com/user-attachments/assets/c9a11472-c464-4441-995a-891215a31a9e) |
|:----------------------:|
| Light Bulbs used to represent 7 as 111 ( on, on, on) |

### ASCII

- ASCII - American Standard Code for Information Interchange
- Ultimately all devices read or understand only bits so we made ASCII (a standard data-encoding format for electronic communication between computers)
- **A** in ASCII is 65 in binary it's 01000001, Hi! is 72 73 33

| ![ASCII Table with 128 unique characters  ( 7 Bit ASCII has 128 and now used 8 Bit has 256 ](https://github.com/user-attachments/assets/03903ca2-cf3c-4bb6-9ec9-9fe5dfc10a4a) |
|:----------------------:|
| ASCII Table with 128 unique characters  ( 7 Bit ASCII has 128 and now used 8 Bit has 256 ) |

### Unicode

- Unicode is an encoding standard that uses up to 32 bits, as required with the goal of capturing all known languages and characters
- Unicode uses two encoding forms: 8-bit and 16-bit depending on the data to be encoded
- Emojis contain colors and some emojis are a combination of emojis which is a result of combining the Unicode characters of various emojis, although emojis might look a bit different on Android, Apple, etc the underlying Unicode is the same
- **Context matters while representing data:** We follow various methods to represent information in different forms like text, emoji, and colors for example, each pixel can be 8 bits to represent the combination of RGB, and pixels come together to form an emoji or a picture, video is moving images, music is made up of notes and loudness, and so on

| ![How an Emoji is encoded in Unicode](https://github.com/user-attachments/assets/1b4799fd-3873-4cb1-8bfe-1b7b6d8d4f9a) |
|:----------------------:|
| How an Emoji is encoded in Unicode |

## Algorithms

What stands between input(problem) and output(solution) are algorithms, which are step-by-step instructions to solve problems. Better algorithms are designed to be faster and more efficient.

Let's say we follow three methods to search for a number from a 1000-page phonebook
1. Method 1 [ n ] - We search all 1000 pages individually, which takes n time. i.e each page has to be turned
2. Method 2 [ n/2 ] - We search one half of the book based on the alphabet and we have to turn only 500 pages
3. Method 3 [ log<sub>2</sub>n ] - Here we keep only halving the pages to reach our desired page, first 1000 becomes 500 then 250, and so on

| ![Algorithm efficiency of three different methods to search a number in Phonebook](https://github.com/user-attachments/assets/6104e944-76ea-43d4-92ac-affafc4527bb) |
|:----------------------:|
| Algorithm efficiency of three different methods to search a number in Phonebook |

## Pseudocode

- Pseudocode is a human-readable step-by-step version of the code/solution to the problem
- Pseudocode is made up of a few building blocks like functions, conditionals, boolean expressions, and loops that are common in all programming languages
- In the below Pseudocode, **Pick up, Open to, Call, and Quit** are [ **functions = actions or verbs that tell us what to do** ]
- **If** and **Else** are [ **conditionals = do this or that** ]
- **Person is on page** is a [ **boolean expression = ask a question with two possible answers like true or false, yes or no** ]
- **Go back to line 3** is a [ **loop = like a cycle to do something again and again** ]

| ![Pseudocode to search a number in Phonebook](https://github.com/user-attachments/assets/4298e506-4acd-4322-9697-abf48b4f4bb4) |
|:----------------------:|
| Pseudocode to search a number in Phonebook |

## What is Artificial intelligence

**LLM - Large Language Model**: An implementation in software that takes in lots of information like text, various forms of content, and all of the web pages as input, and then infers(concludes) what a human might answer when asked the same question. An LLM answers like a human by learning the language patterns and predicting a human answer statistically/probabilistically.

| ![CS50.ai - LLM](https://github.com/user-attachments/assets/df13b113-7e27-44c1-97e3-e877ba7c1b38) |
|:----------------------:|
| CS50.ai - LLM |

## Scratch

Scratch is a visual programming language, i.e., Scratch is used to visually represent ideas in code

| ![Hello world in Scratch](https://github.com/user-attachments/assets/c4dbf895-4470-43ee-a942-afae4837477c) |
|:----------------------:|
| Hello world in Scratch |

| ![Input -> Algorithm Join (whose purpose is to join the inputs) -> Output](https://github.com/user-attachments/assets/7fed3015-262d-47e3-80d3-ad7826350c6f) |
|:----------------------:|
| Input -> Algorithm Join (whose purpose is to join the inputs) -> Output |

### Abstraction & Conditionals in Scratch
We can create a function in scratch to do something, by using a function we achieve modularity and abstraction.

| ![Code to Meow function](https://github.com/user-attachments/assets/cb0e6a04-96ba-4ed2-a383-912f0975864d) |
|:----------------------:|
| Code to Meow function |

### Oscartime - a Game made from Scratch

- Oscartime is made possible over a few iterations and blocks of logic coming together
- Step by step where each block handles a particular logic

| ![Oscartime - one of the Games made with Scratch](https://github.com/user-attachments/assets/06c51359-8b87-4ed6-a395-0a4ea375e1b8) |
|:----------------------:|
| Oscartime - one of the Games made with Scratch |

| ![Ivy's Hardest Game](https://github.com/user-attachments/assets/079bf78c-998a-4d6a-a4fb-ae114fd81d71) |
|:----------------------:|
| Ivy's Hardest Game |

### This is CS50 - Special Thanks to Harvard Professor David J. Malan

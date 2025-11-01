<!-- 🎨 Animated Header -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3000&pause=800&color=FF69B4&center=true&vCenter=true&width=800&lines=🎨+Image+Modification+Program;Java-Based+PPM+Image+Processor;Algorithms+%7C+File+I%2FO+%7C+Color+Transformation+💻✨" alt="Typing Animation" />
</p>

---

# 🎨 Image Modification Program

The **Image Modification Program** is a **Java-based application** that processes and modifies **PPM (Portable Pixmap)** image files.
It demonstrates strong skills in **file I/O**, **algorithmic problem solving**, and **low-level image manipulation** — key areas in both software development and computational image processing.

With just a few commands, users can transform images using operations like **negation**, **quantization**, **grayscale**, and **horizontal flipping**, all built from scratch without external image libraries.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c5c07d45-60dd-4404-9df6-830f6e384e13" width="250" alt="Input image preview"/>
</p>

---

## 💡 Overview

1. The program reads and parses an input **PPM image file**, extracting metadata (width, height, max color value).
2. Users choose one of the available transformations.
3. The modified image is written to a new output PPM file, preserving format integrity and header details.

This project showcases practical **Java programming**, **algorithm design**, and **data structure manipulation**, all applied in a real-world computational task.

---

## ⚙️ Features

| Feature                | Description                                                    | Output                                                                                                   |
| ---------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 🧩 **Negate**          | Inverts each pixel’s RGB value (`new = 255 - old`)             | <img src="https://github.com/user-attachments/assets/e8a0c3c9-040d-48c7-a611-5eeffd9e4c66" width="200"/> |
| 🎛️ **Quantize**       | Converts pixel values to 0 or 255 depending on a 127 threshold | <img src="https://github.com/user-attachments/assets/51ed4f66-ab4f-427c-9c34-64a5cfd299e2" width="200"/> |
| ⚪ **Grayscale**        | Averages RGB components for each pixel                         | <img src="https://github.com/user-attachments/assets/52901c28-817b-42ed-aa33-ac64236599dd" width="200"/> |
| 🔁 **Flip Horizontal** | Flips the image across its vertical axis                       | <img src="https://github.com/user-attachments/assets/7eb9d03f-1485-4b51-bb27-1e86b3fc872e" width="200"/> |

---

## 🧠 Technical Skills Demonstrated

| Skill Area                    | Technologies & Concepts                                            |
| ----------------------------- | ------------------------------------------------------------------ |
| 💻 **Programming Language**   | Java (JDK 8+)                                                      |
| 🧮 **Algorithms**             | Pixel-wise manipulation, conditional quantization, matrix flipping |
| 🧱 **Data Structures**        | 2D arrays for RGB pixel data                                       |
| 📁 **File I/O**               | Reading & writing raw PPM files                                    |
| ⚙️ **Procedural Programming** | Modular design and reusable transformation methods                 |
| 🧩 **Problem Solving**        | Manual image processing logic without dependencies                 |
| 🧪 **Testing & Debugging**    | Command-line execution and visual output verification              |

---

## 🧩 Code Structure

```
ImageModificationProgram/
├── ImageModify.java          # Main class: user interaction & method control
├── processHeader()           # Extracts PPM metadata (width, height, color max)
├── NEGATE()                  # Inverts RGB color values
├── QUANTIZE()                # Converts pixel brightness to binary threshold
├── GRAY_SCALE()              # Applies average-based grayscale filter
├── FLIP_HORIZONTAL()         # Reverses pixel positions horizontally
```

---

## 🚀 How It Works

### 🧾 Input Example

**Input file (input.ppm):**

```
P3
4 4
255
255 0 0  0 255 0  0 0 255  255 255 0
255 255 255  128 128 128  64 64 64  0 0 0
```

**After Negation:**

```
P3
4 4
255
0 255 255  255 0 255  255 255 0  0 0 255
0 0 0  127 127 127  191 191 191  255 255 255
```

---

## 🧰 Usage

### Compile

```bash
javac ImageModify.java
```

### Run

```bash
java ImageModify
```

### Follow Prompts

* Input PPM filename
* Output PPM filename
* Choose operation:

  * `a`: Negate
  * `b`: Quantize
  * `c`: Grayscale
  * `d`: Flip Horizontal

---

## 🧱 Requirements

* Java Development Kit (JDK 8 or later)
* Valid `.ppm` input file (P3 format)

---

## ⚠️ Notes

* The output file **overwrites** existing files with the same name.
* Ensure the input image follows correct **PPM syntax** (header + RGB data).
* No external libraries are required — **entire logic implemented manually**.

---

## 🎯 Learning Outcomes

Through this project, I gained experience in:

* Designing low-level image processing algorithms
* Building modular and testable Java programs
* Parsing and reconstructing structured data formats
* Strengthening my debugging and console-testing workflows

---

## 👩🏻‍💻 Author

**Mahnoor Iftikhar**
📍 *Pacific Lutheran University* — CS & Economics Double Major, Data Science Minor
💡 Passionate about **software that merges math, logic, and creativity** to solve real-world challenges.

📫 [LinkedIn](https://www.linkedin.com/in/mahnooriftikharrr)
📧 [mahnooriftikharr@gmail.com](mailto:mahnooriftikharr@gmail.com)

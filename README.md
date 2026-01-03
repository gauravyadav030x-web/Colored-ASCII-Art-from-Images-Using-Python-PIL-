# Colored ASCII Art Generator Using Python

Convert images into colored ASCII art directly in your terminal using Python and the Pillow (PIL) library.
Each ASCII character represents pixel brightness while preserving the original RGB color using ANSI escape codes.

## Project Overview

This project transforms a standard image into ASCII art with true colors, displayed in the terminal.
It demonstrates core concepts of image processing, grayscale conversion, pixel manipulation, and terminal graphics.

Unlike traditional ASCII art, this project keeps the original image colors, resulting in a more vivid and expressive output.

## Objectives

Understand how images are stored as pixels

Learn RGB to grayscale conversion

Map pixel brightness to ASCII characters

Apply ANSI escape codes for colored terminal output

Build a creative image-processing project using Python

## Basic Theory
  # 🔹 Digital Images

An image is a grid of pixels. Each pixel in an RGB image has:

Red (R)

Green (G)

Blue (B)
values ranging from 0 to 255.

 # 🔹 Grayscale Conversion

To calculate pixel brightness, the luminance formula is used:

Gray = 0.299R + 0.587G + 0.114B


This formula matches human visual perception.

# 🔹 ASCII Mapping

Dark pixels are represented using dense characters (@, #),
Light pixels use lighter characters (. , ,).

# 🔹 ANSI Escape Codes

ANSI escape codes allow color formatting in terminals using 24-bit true color (RGB).

## Motivation

 This project was created to:
 Learn image processing in a fun and visual way
 Strengthen Python fundamentals
 Explore how terminals handle colors and text
 Build a unique project beyond basic tutorials

# 🌍 Real-World Relevance

The concepts used here are applied in:
Image preprocessing for AI & ML
Computer vision pipelines
Graphics and game engines
Terminal-based system tools
Data visualization

## ⚙️ Prerequisites

Python 3.x
Basic Python knowledge (loops, functions)
Pillow (PIL fork)
Install Pillow using:
pip install pillow

## 🧑‍💻 Implementation
🔹 ASCII Character Set
ASCII_CHARS = ["@", "#", "S", "%", "?", "*", "+", ";", ":", ",", "."]

## 🚀 Future Enhancements

Save ASCII output to a .txt file
Add grayscale-only mode
Video-to-ASCII conversion
GUI or web-based version
Windows CMD compatibility

## Output

Displays a colored ASCII version of the image
Works best in:
Linux terminal
macOS Terminal
VS Code terminal

## 👤 Author
Gaurav Yadav
B.Tech CSE (Core)

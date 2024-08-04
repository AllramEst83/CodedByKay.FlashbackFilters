# Flashback Filters

## Introduction
Welcome to the Flashback Filters project! This initiative aims to recreate the nostalgic aesthetic of family photos from the 1980s and 1990s through digital filters. Our goal is to encapsulate that unique visual feel that many of us remember fondly from our old photo albums.

Currently, the project is in its early stages, being developed as a console application. The long-term vision is to evolve this into either a mobile app or a web-based platform, providing easy access to retro-style filters for everyone.

## Project Status
**Current Phase:** Initial Development  
The project is currently being developed as a console application. This phase focuses on building the core functionality of the 80s and 90s image filters.

**Next Steps:**
- Enhance the console application with more complex filter algorithms.
- Begin transitioning the console logic to a web or mobile-based interface.
- Design a user-friendly UI that captures the retro theme.

## Getting Started
To get started with Flashback Filters, clone this repository to your local machine:

```bash
git clone https://github.com/AllramEst83/CodedByKay.FlashbackFilters.git
```

# 80s Film Style Image Filter in C#

To create a filter that mimics the style and feel of 1980s film using C#, you'll need to dive into image processing and manipulation. Here are the steps and tools that can guide you through the process:

## 1. Understanding the 80's Film Style
The 1980s film style often includes characteristics like:
- Graininess and noise
- Faded colors with a slight yellow tint
- High contrast
- Slight blurriness
- Vignette effect

## 2. Choosing the Right Tools
For image manipulation in C#, you have a few options:

### A. System.Drawing (GDI+)
This is a common library for basic image manipulation in C#. It's part of the .NET framework and provides functionalities for drawing and processing images.
- **Pros:** Well-documented, widely used.
- **Cons:** Limited in advanced image processing capabilities.

### B. ImageSharp
ImageSharp is a modern, cross-platform library for .NET. It offers more advanced features and better performance for image manipulation.
- **Pros:** High performance, modern API, cross-platform.
- **Cons:** Less documentation compared to System.Drawing, but it's growing.

### C. OpenCV with Emgu CV
OpenCV is a powerful image processing library. Emgu CV is a .NET wrapper for OpenCV.
- **Pros:** Extremely powerful and versatile.
- **Cons:** Steeper learning curve, more complex to integrate.


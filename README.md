# Amazon Desktop UI Architecture

A pixel-perfect implementation of the Amazon desktop interface, built to deconstruct complex e-commerce layouts using pure CSS3 and HTML5.

🔗 **[Live Demo (Desktop Only)](https://muhammadumerfareed.github.io/amazon-desktop-ui-architecture/)**

<img width="1907" height="884" alt="image" src="https://github.com/user-attachments/assets/448f2425-fa2c-481f-b550-406f5cb9ff84" />


## 🎯 Project Scope
This project is a **Desktop-First Architecture Study**.
 
Instead of relying on modern frameworks, I challenged myself to reconstruct the Amazon landing page using **Vanilla CSS**. The objective was to refine my understanding of the CSS Box Model, positioning contexts, and flexbox alignment strategies without the overhead of libraries.

*Note: As this is a layout architecture study, the build is optimized for Desktop viewports.*

## 🛠️ Technical Implementation
* **Layout Engine:** CSS Flexbox (Nested Flex Containers).
* **Positioning:** Relative/Absolute positioning for overlay elements and z-index management.
* **Component Architecture:**
    * **Navbar:** utilized `flex-grow` logic to create a responsive search bar that adapts to available width.
    * **Horizontal Scroll:** Implemented a native CSS scrollable list (`overflow-x: auto`) for the "Best Sellers" section without JavaScript.
    * **Grid System:** Calculated percentage-based widths (`23%` vs `45%`) to maintain consistent gaps in the product card grid.

## 📸 Interface Details

### Navigation & Search Logic
The navbar demonstrates complex alignment of mixed content types (Images, Text, Inputs, Icons) within a single flex parent.
<img width="1897" height="149" alt="image" src="https://github.com/user-attachments/assets/39ea44a5-6e99-4962-b1b1-03340a07b040" />


### Footer Layout
A structured multi-column layout focusing on semantic grouping and precise spacing.
<img width="1904" height="871" alt="image" src="https://github.com/user-attachments/assets/bcb8deb6-4290-44f1-b69f-37ea7cfa47b8" />


## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [[https://github.com/YOUR-USERNAME/amazon-desktop-ui-architecture.git](https://github.com/YOUR-USERNAME/amazon-desktop-ui-architecture.git)](https://github.com/muhammadumerfareed/amazon-desktop-ui-architecture.git)
   ```
2. Open ```index.html``` in your browser.
   
##⚖️ Disclaimer
**This project is a frontend implementation study for educational purposes. All logos, images, and branding assets are property of Amazon.com, Inc.**

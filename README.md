<!-- Title -->
<div align="center">
  <a href="https://github.com/EggCalculator/eggcolourcalculator">
    <img src="https://raw.githubusercontent.com/EggCalculator/eggcolourcalculator/main/android-chrome-512x512.png" alt="Egg Calculator" height="100">
  </a>
</div>

<h3 align="center">Egg Colour Calculator</h3>
  
<div align="center">Calculator that will predict the possible chicken egg colours based on parental genotypes!</div>

<!-- Project Sheilds -->
<div align="center">
  <img src="https://img.shields.io/github/stars/EggCalculator/eggcolourcalculator.svg?labelColor=003694&color=ffffff" alt="Stars">
</div>
  

<!-- Share -->
<div align="center">
  
  <strong>Share</strong>

  <a href="https://x.com/intent/tweet?hashtags=opensource%2Creadme&text=Check%20this%20out:%20Readme Forge!&url=https%3A%2F%2Fgithub.com%2FSenaThenu%2Freadme-forge">
    <img src="https://img.shields.io/badge/Share_on_X-%23000000.svg?logo=X&logoColor=white" alt="Share on X" />
  </a>
  
</div>

<!-- Contents -->
<details>

<summary><strong>Table of Contents 📜</strong></summary>

  - [Website Demo 🧑‍💻](#website-demo-)
  - [Features ✨](#features-)
  - [Usage 🛠️](#usage-)
    - [Basic Usage 📝](#basic-usage-)
    - [Advanced Usage 🦾](#advanced-usage-)
    - [Additional Options 📌](#additional-options-)
  - [How It Works 🔍](#how-it-works-)
    - [Gene Breakdown](#gene-breakdown)
  - [Built With 🔧](#built-with-)
  - [Acknowledgments 💝](#acknowledgments-)

</details>

<!-- Demo-->
## Website Demo 🧑‍💻
You can use the calculator live here : [https://eggcalculator.github.io/eggcolourcalculator](https://eggcalculator.github.io/eggcolourcalculator/)






<!-- Features -->
## Features ✨
* **Genotype Punnett Squares:** Dynamically generate genetic cross grids based on parental genotypes.

* **Egg Colour Prediction:** Accurately simulate combinations of base shell color, brown topcoats, and modifier genes.
* **Multi-Gene Trait Modeling:** Accurately simulate combinations of base shell color, brown topcoats, and modifier genes.
* **Chicken Breed Reference:** Quickly select traits for popular breeds like Araucana, Cream Legbar, and Marans.
* **Instant Client-Side Engine:** Get real-time genetics calculations directly in your browser without page reloads.        

<!-- Usage -->
## Usage 🛠️

### Basic Usage 📝
Input 2-letter genotype letter combinations for Parent 1 and Parent 2.

**Example:**
* **Parent 1:** `Ww`
* **Parent 2:** `Ww`

(Generates a 2x2 monohybrid cross tracking base shell color: white `ww` vs. blue `Ww`/`WW`)

### Advanced Usage 🦾
For more complex operations or customization:

Input 4-letter or 6-letter genotype combinations to track multiple traits, including brown topcoats (BB/Bb) and optional third density modifier genes (CC/cc).

**Example:**
* **Parent 1:** `WwBbCc`
* **Parent 2:** `WwBbCc`

(Generates an 8x8 trihybrid cross matrix for ultra-precise shade probability statistics) 

### Additional Options 📌
- Breed Selection Helper: Select popular chicken breeds (such as Araucana, Cream Legbar, or Marans) to automatically configure parental genetic traits.

- Visual Colour Map: Instantly generate a visual map displaying potential egg shell shades (Green, Olive, Blue, Tan, Brown, or White).
- Matrix Scales: Toggle grid complexity between 2x2, 4x4, and 8x8 scales based on your input length.
   

<!-- How It Works -->
## How It Works 🔍

Chickens can lay either white or blue base coloured shells and then a brown topcoat may be added on top.

* If a **white** egg has a **tan/brown** topcoat, the egg will be **tan** or **brown**.
* If a **blue** egg has a **tan/brown** topcoat, the egg will be **green** or **olive** (depending on the shade of tan/brown).

Hence:
* If a **white** egg has **no** **tan/brown** topcoat, the egg will be **white**.
* If a **blue** egg has **no** **tan/brown** topcoat, the egg will be **blue**.

### Gene Breakdown
* `ww`: The White Shell gene (recessive). 

* `WW / Ww`: The Blue Shell gene (dominant).

* `BB / Bb`: The Brown Coating gene (determines the overlay strength for green, olive, tan, or brown shades).

* `CC / cc`: Optional third modifier gene to add deeper brown shade variety to the eggs



## Built With 🔧
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS33](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Vanilla JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)


## Acknowledgments 💝

- [Readme Forge](https://readme-forge.github.io) - Creating README.md
- [Awesome README](https://github.com/matiassingers/awesome-readme) - Suggesting great tools

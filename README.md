# 🔮 Quandle and Rack Tools for GAP

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![GAP](https://img.shields.io/badge/GAP-4.11-blue)

This repository provides a collection of GAP functions for studying **racks** and **quandles**, with a focus on their algebraic properties, congruence structures, and computational exploration. These tools support tasks such as identifying subracks, generating congruence lattices, and analyzing symmetry and generation properties.

The functions are designed to be used within the syntax and framework of the GAP package **RIG**, developed by **Leandro Vendramin**. You can find more about RIG here:  🔗 [https://gap-packages.github.io/rig/](https://gap-packages.github.io/rig/)


## ✨ Features

- Display rack Cayley tables and access rack rows and columns  
- Test properties like primitivity, connectivity, and affineness of quandles  
- Compute connected congruences, congruence lattices, and subracks  
- Generate minimal generating sets for racks  
- Build coset quandles, twisted principal racks, and conjugation racks  
- Utilities for partition refinement and congruence checking 

## 📂 Project structure

```bash
quandle-tools/
│
├── quandle_tools.py            # Main module with all functionality
├── LICENSE                 # License
├── manual.txt              # Documentation with a brief description of each function
├── README.md               
│  
```

## 🚀 Installation

Clone this repository or download the source files:

```bash
git clone https://github.com/fspaggiari/quandle-tools.git
```

---

## 🛠️ Usage

Import the functions in RIG

```bash
Read("quandle_tools.g")
```

Each function is documented with a brief description of its purpose. You can use them interactively within GAP to analyze racks and quandles.

---

## 📄 License

This project is licensed under the **MIT License**.  

You are free to use, modify, and distribute this software with proper attribution.

---

## 🤝 Contributions

Contributions are welcome!

If you have ideas for improvement, bug reports, or would like to add new features:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

Please ensure your code is clean, documented, and tested. Thank you!
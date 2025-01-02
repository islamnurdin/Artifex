# Artifex: AI-Powered Text-to-CAD Tool 🚀

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![FreeCAD](https://img.shields.io/badge/Powered%20by-FreeCAD-orange)](https://www.freecadweb.org/)
[![OpenAI API](https://img.shields.io/badge/API-OpenAI-brightgreen)](https://openai.com/)
[![Claude API](https://img.shields.io/badge/API-Claude-brightgreen)](https://www.anthropic.com/)

Artifex is an AI-driven engineering tool that acts as a copilot designed to simplify CAD workflows by enabling natural language-driven design. With **Artifex**, you can describe your ideas in plain English, and it will translate them into complex 3D CAD models within FreeCAD. Built as a macro, Artifex leverages state-of-the-art APIs like OpenAI and Claude to provide real-time design assistance.

![Artifex Demo](https://github.com/islamnurdin/Artifex/assets/demo.gif)  
*Above: A live demo of Artifex in action*

---

## ✨ Features
- **Text-to-CAD**: Transform natural language descriptions into CAD models.
- **Real-time AI Assistance**: Get instant feedback and suggestions for design improvements.
- **Multi-API Support**: Compatible with OpenAI and Claude APIs.
- **Open-Source and Extensible**: Built to encourage community contributions and enhancements.

---

## 🛠 Installation & Setup

1. **Install FreeCAD**  
   Download and install FreeCAD from the [official website](https://www.freecadweb.org/).

2. **Clone the Repository**  
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Artifex.git
   cd Artifex
   ```

3. **Set Up API Keys**  
   Obtain API keys for the required service:
   - OpenAI API: [Sign up here](https://openai.com/).
   - Claude API: [Sign up here](https://www.anthropic.com/).

   Configure the keys as environment variables:
   ```bash
   api-key = "your-openai-key"
   api-key = "your-claude-key"
   ```

4. **Load the Macro in FreeCAD**  
   - Open FreeCAD and navigate to `Macro > Macros...`.
   - Load the `Artifex.FCMacro` file from the `src/` directory.
   - Click **Run** to start using Artifex.

---

##  How It Works
Artifex uses AI to process natural language inputs and generate 3D CAD models:
1. **Input Design**: You describe your design in text, such as:  
   *"Create two spheres (20mm diameter) connected by a cylinder (20mm diameter, 200mm height)."*
2. **AI Processing**: Artifex uses OpenAI or Claude to interpret your input and create a script for FreeCAD.
3. **Model Generation**: FreeCAD executes the script, generating a precise 3D model.

---

## Project Structure
```
Artifex/
  src/                   # Macro source files
      Artifex_OpenAI.FCMacro
      Artifex_Claude.FCMacro
  docs/                  # Documentation
  examples/              # Example input and output files
  README.md              # Project documentation
  LICENSE                # MIT License
  CONTRIBUTING.md        # Contribution guidelines
```

---

## Contributing
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### How to Contribute
- **Bug Reports**: Open an issue describing the problem.
- **Feature Requests**: Suggest new features via issues.
- **Pull Requests**: Submit code improvements or fixes.

1. Fork this repository.
2. Create a new branch for your feature or fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes with clear messages:
   ```bash
   git commit -m "Add feature X"
   ```
4. Push to your branch and open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Credits
- Developed by [Izzy](https://islamnurdin.github.io) and [Mussie](https://www.linkedin.com/in/mussie-tsegay/).
- Powered by [FreeCAD](https://www.freecadweb.org/), [OpenAI](https://openai.com/), and [Claude](https://www.anthropic.com/).

---

## Links
- **Website**: [Artifex.com](https://islamnurdin.github.io/artifex.html)
- **Twitter**: [Izzy on X](https://x.com/islamnurdin)

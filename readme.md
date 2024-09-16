# Hacking the Python Import System - PyCon Israel 2024
This repository contains the slides for my PyCon Israel 2024 talk on **Hacking the Python Import System**, where I explain Python's import machinery, demonstrate how to extend it, and even show how to generate modules on-the-fly using AI. The talk covers key concepts like Finders, Loaders, and how the system works under the hood.

## PDF Version

You can view the [exported PDF version of the slides](./hacking_the_python_import_system.pdf) directly.

## Setup

The slides are built using [Slidev](https://github.com/slidevjs/slidev). To set up and view the slides locally:

1. Clone the repository:
```bash
git clone https://github.com/LiadOz/hacking-import-presentation.git
cd hacking-import-presentation
```

2. Install dependencies:
```bash
npm install
```

3. Run Slidev to view the slides:
```bash
npx slidev
```
4. Open the URL printed in the terminal to view the presentation in your browser.

## Related Project

As mentioned in the presentation, check out [module-found](https://github.com/LiadOz/module-found) for a fun take on generating Python modules on the fly!

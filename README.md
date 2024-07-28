# Mask_Personal_Data

This project provides a Python script to mask specific entities in a given text based on extracted data. Entities include names, addresses, phone numbers, API keys, and spouse names. The script uses regular expressions to identify and mask these entities.

## Features
- **Entity Masking**: Masks specified entities in the text, such as names, addresses, phone numbers, and API keys.
- **Flexible Input**: Accepts a JSON-formatted string with extracted data to specify entities for masking.
- **Case-Insensitive Matching**: Handles case insensitivity to match entities correctly regardless of their case in the input text.

## Data extraction
We use the open-source NER model NuEXTRACT from Numind. 

See blog post https://numind.ai/blog/nuextract-a-foundation-model-for-structured-extraction

## Installation
To use this script, you need Python installed on your system. This script works with Python 3.6 and above. There are no external dependencies beyond the standard library. You can also run it in colab, make sure to use the T4 accelerator


### 1. Clone the repository:
```bash
git clone https://github.com/rayaneghilene/Mask_Personal_Data.git
cd Knapsack_pb
```

### 2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have improvements or fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or issues, don't hesitate to get in touch with rayane.ghilene@ensea.fr.

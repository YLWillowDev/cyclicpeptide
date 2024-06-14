# Project Name

A brief description of your project goes here.

## Installation

To install the project, you can use pip:

    pip install cyclicpeptide

## Usage

Here's how you can use the project in your Python code:

from cyclicpeptide import module

**module**: peptide_properties/sequence2structure/structure2sequence/graph_alignment

```python
# Example code
from cyclicpeptide import PeptideProperties as pp

exmaple = [('Ctopa(CP00005)',
            'CC(C1C(=O)NC(C(SSCC(C(=O)NC(C(=O)NC(C(=O)NC(C(=O)N1)CCCN)CC2=CNC3=CC=CC=C32)CC4=CC=C(C=C4)O)NC(=O)C(CC5=CC=CC=C5)N)(C)C)C(=O)NC(C(C)O)C(=O)N)O',
            'FCYWATCT'),
           ('alpha-Amanitine(CP01656)',
            'CC[C@H](C)[C@H]1C(=O)NCC(=O)N[C@H]2C[S@@](=O)C3=C(C[C@@H](C(=O)NCC(=O)N1)NC(=O)[C@@H](NC(=O)[C@@H]4C[C@H](CN4C(=O)[C@@H](NC2=O)CC(=O)N)O)[C@@H](C)[C@H](CO)O)C5=C(N3)C=C(C=C5)O',
            'ATPTTT'),
           ('Anidulafungin(CP00145)',
            'CCCCCOC1=CC=C(C=C1)C2=CC=C(C=C2)C3=CC=C(C=C3)C(=O)NC4CC(C(NC(=O)C5C(C(CN5C(=O)C(NC(=O)C(NC(=O)C6CC(CN6C(=O)C(NC4=O)C(C)O)O)C(C(C7=CC=C(C=C7)O)O)O)C(C)O)C)O)O)O',
            'AA')]

smiles = exmaple[0][1]
sequence = exmaple[0][2]
print(pp.chemial_physical_properties_from_smiles(smiles))
```
## Examples
Here are some examples demonstrating how to use the project:

Example 1
Example 2
...
## Contributing
If you would like to contribute to the project, please follow these steps:

    1.Fork the repository
    2.Create a new branch (git checkout -b feature)
    3.Make your changes
    4.Commit your changes (git commit -am 'Add new feature')
    5.Push to the branch (git push origin feature)
    6.Create a new Pull Request

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact
If you have any questions or concerns, feel free to contact me at your_email@example.com.
# NFA--DFA

A Streamlit dashboard for visualizing and converting ε-NFA/NFA to DFA, with support for Excel uploads and LaTeX export.

## Features

- Upload NFA definitions from Excel or enter them manually
- Visualize NFA and DFA state diagrams (Graphviz)
- View and export transition tables (including LaTeX format)
- Download SVG diagrams

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for dependencies

## Installation

```sh
pip install -r requirements.txt
```

## Usage

Run the Streamlit app:

```sh
streamlit run NFA_DFA.py
```

## Input Formats

### Excel Upload

Your Excel file should have columns: `State`, `Input`, `Next_State`, and optionally `Start_State`, `Final_State`.

### Manual Input

- Enter states, alphabet, start/final states in the sidebar
- Specify transitions for each state and symbol (including ε)

## Output

- Interactive state diagrams for NFA and DFA
- Transition tables (with LaTeX export)
- Downloadable SVG diagrams

## Example

See [sample_nfa.xlsx](sample_nfa.xlsx) for a sample input file.

## License

MIT License

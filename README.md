# Open AI Use Cases

This repository contains a collection of notebooks and code samples addressing various openai API use cases.

## Structure

- `meeting-notes/`: This folder contains a Jupyter Notebook focused on extracting and structuring action items from meeting notes. The notebook demonstrates how to parse meeting notes, identify key tasks, and assign responsible individuals and deadlines.

### Meeting Notes Folder

#### Notebook: `meeting_notes_processor.ipynb`

This notebook processes unstructured meeting notes into a structured format by:
- Extracting **action items** (tasks) from meeting notes.
- Identifying task **owners** (responsible individuals).
- Extracting **due dates** for tasks, when available.
- Presenting the structured output as a DataFrame.

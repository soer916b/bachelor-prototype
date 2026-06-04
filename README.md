# Bachelor Prototype

Repository for my computer science bachelor thesis.

The repository contains a Jupyter Notebook prototype used to evaluate interactive exercises for programming concepts.

## Notebooks

* `notebooks/pilot_prototype.ipynb`
  v1 prototype version used for pilot testing.

* `notebooks/prototype.ipynb`
  Main prototype version used for the final evaluation.

## Dependencies

The prototype is implemented in Python as interactive Jupyter Notebooks.

The notebooks use:

* `ipywidgets` for interactive notebook components
* `IPython.display` for displaying Markdown, widgets, and clearing output
* `re` for regular expression matching
* `voila` for rendering the notebook as a browser-based web application

The `re` package is part of the Python standard library and does not need to be installed separately.

## Running the prototype locally

### 1. Clone the repo

```bash
git clone <repository-url>
cd bachelor-prototype
```

### 2. Create and activate a virtual environment

On macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r dependencies.txt
```

Otherwise, install the required packages manually:

```bash
pip install notebook ipywidgets ipython voila
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open one of the notebooks in the `notebooks/` folder.

## Running with Voilà

Voilà can be used to render the notebook as a simple web application, hiding the code cells and showing only the interactive interface.

To run the main prototype with Voilà:

```bash
voila notebooks/prototype.ipynb
```

To run the pilot prototype with Voilà:

```bash
voila notebooks/pilot_prototype.ipynb
```

This will start a local server and open the prototype in the browser.

## Interview questions

The file `post_interview_questions.md` contains the post-task interview questions used during the evaluation.

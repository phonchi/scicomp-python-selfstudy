# Scientific Computing with Python — Self-Study Companion

Interactive self-study companion site for the **Scientific Computing with Python** video course (NumPy · Matplotlib · SymPy · SciPy · Pandas), designed for first- and second-year college students studying at home. The goal is not software-engineering training — it is to give students a toolbox for the subjects they are already studying: compute, picture, and verify the math from calculus, linear algebra, and statistics with their own hands.

**Live site:** https://phonchi.github.io/scicomp-python-selfstudy/

## Pages

| Page | Content |
|---|---|
| `index.html` | Course hub: study loop, prerequisites, module cards |
| `00a_why_code.html` | Why still learn scientific computing in the AI era |
| `00b_setup.html` | Home environment setup (Colab / Anaconda / VS Code) + Colab Learn Mode |
| `01_numpy.html` | Module 1 · Array-Oriented Programming with NumPy (8 videos) |
| `02_matplotlib.html` | Module 2 · Visualization with Matplotlib (6 videos) |
| `03_sympy.html` | Module 3 · Symbolic Mathematics with SymPy (6 videos) |
| `04_scipy.html` | Module 4 · High-level Scientific Computing with SciPy (6 videos) |
| `05_pandas.html` | Module 5 · Data Analysis with Pandas (5 videos) |
| `p1_python_basics.html` … `p8_oop.html` | Prerequisites P1–P8 · optional basic-Python refreshers (see below) |

Each module page includes per-video breakdown timelines, concept digests, interactive widgets, a self-check quiz from the course test bank, and key-term flashcards.

### Prerequisite pages (P1–P8)

Supplementary refreshers of the basic Python the modules assume — **not graded, never part of the course assignments**（補充先備知識，不列入作業範圍）. Digested from the intro-programming notebooks (`01_Python.ipynb` … `08_OOP.ipynb`, publicly hosted in [phonchi/nsysu-math106A](https://github.com/phonchi/nsysu-math106A)), with each notebook's own quiz bank and flashcards embedded. No videos and no LMS config — the source-notebook badges link directly to Colab/GitHub.

| Page | Topic |
|---|---|
| `p1_python_basics.html` | P1 · Python Basics |
| `p2_flow_control.html` | P2 · Flow Control |
| `p3_functions.html` | P3 · Functions |
| `p4_lists_tuples.html` | P4 · Sequences: Lists & Tuples |
| `p5_dicts_sets.html` | P5 · Dictionaries & Sets |
| `p6_strings.html` | P6 · Manipulating Strings |
| `p7_files_exceptions.html` | P7 · Files & Exceptions |
| `p8_oop.html` | P8 · Object-Oriented Programming |

## Course materials

The lecture videos, notebooks, and RISE slides are hosted on the university e-learning platform (網路大學). To turn the placeholder badges on the pages into live links, set `LMS_BASE` / `DOCS_BASE` in the "EDIT HERE" config block at the top of each page's `<script>`.

## Development

Every page is fully self-contained (inline CSS + vanilla JS, no build step, no external libraries except Google Fonts). Open any `.html` file directly in a browser.

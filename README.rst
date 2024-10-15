.. image:: https://github.com/pyc-team/pytorch_concepts/blob/dev/doc/_static/img/pyc_logo_text.svg?sanitize=true
   :scale: 50 %
   :alt: PyC Logo
   :align: center

==================================================================
Concept-based Interpretable Deep Learning in Python
==================================================================

This book demonstrates how to build interpretable deep learning models in Python using the PyC library.


Contributing
-------------------------

1. Create local repository by cloning the project from GitHub. The ``main`` branch is the stable branch. **Do not use it to write or test your contributions**.
2. Install the required packages by running ``pip install -r requirements.txt``.
3. Open the ``dev`` branch (or a local branch) to write and test your contributions locally.
4. Write or update a notebook in the respective ``part`` folder (e.g., ``intro``).
5. Add the notebook to the ``_toc.yml`` file in the respective section.
6. Submit a pull request to the ``dev`` branch and ask for a review.
7. Once the pull request is approved, it will be merged into the ``dev`` branch (and eventually into the ``main`` branch).

To check local changes:
1. Run the following command: ``jupyter-book build .``.
2. Open the ``_build/html/index.html`` file in your browser.

To check the changes online:
1. Run the following command: ``ghp-import -n -p -f -o _build/html``.
2. Open the GitHub Pages link <https://pyc-team.github.io/pyc-book/>.

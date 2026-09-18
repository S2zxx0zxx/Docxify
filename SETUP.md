# Docxify setup and status

Source restored from Doclify-main.zip; original attribution, license and ZIP are retained. This is a Python command-line application, not a hosted website.

Create and activate a Python virtual environment, run `python -m pip install .`, then `doclify --help`.

Run `doclify init` inside the project you want to document. Set GROQ_API_KEY privately in your environment or a local .env file before `doclify run`. Never commit that key. Documentation generation sends selected project code to Groq; choose the intended files in doclify.yaml before running it.

The package now includes its required prompt templates. Wheel build is verified; live AI generation requires your Groq credentials and was not run. The original manual PyPI workflow was not executed and the upstream package was not republished.

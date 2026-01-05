# Simple website & CV generator

This is my spin on a simple website & CV generator based on the following needs:

- Generate a website and a CV based on a single JSON file.
- Keep things as simple as possible. The only external dependency is Jinja2. The rest is pure Python and HTML/CSS.
- Utilize GitHub Actions to automate generation and deployment, including a PDF version of the CV.
- Be simple enough that I can remember how to use it for the years to come (😉).

## Want to use my repository as a template for your own website?

1. Clone this repository.
2. Change the `db.json` file to reflect your details. 
3. Change the `template/index.html` file to reflect your bio. 
4. Modify any of the template files to your liking. This will require some knowledge of Jinja2.
5. Modify the `generate_content.yml` file to your liking (e.g., remove the last part where it remote uploads the PDF file).
5. Push the changes to your GitHub repository.

For local development you need an installation of Python 3.9 or higher and `Jinja2` (`pip install jinja2`). After that you can simply run `python website_generator.py` to update the content in public.

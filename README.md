# Grundlagen der Anwendungsentwicklung A4
Submitted by 108758
## Introduction to Pandas DataFrames – Replicating an article in Markdown
### What is this Project about?
This project is an example of using a Jupyter Notebook to render a .html file. The actual content is based on this [article](https://elearn.unigis.at/pluginfile.php/10754/mod_resource/content/29/assignments/Set1/Aufgabe4/PandasIntroduction.html). This project is part of the [UNIGIS]((https://unigis.at)) master's degree offered by the University of Salzburg, Austria.
### Dependencies
The following programs and libraries are used throughout the project:
- Jupyter Notebook (.ipynb)
- Python (Version 3.14 5 was used)
    - the pandas library (Version 3.0.3 was used)
### Project Structure
The data is structured as follows:
- dist
    - Pandas.html
    - Pandas.webp
- Pandas.ipynb
- Pandas.webp

The directory *dist* contains the output *Pandas.html*, and it's single dependency, the *Pandas.webp*.

The Jupyter Notebook *Pandas.ipynb* is used to render the .html. The duplicated *Pandas.webp* is necessary, since both the .ipynb and the .html are referencing *Pandas.webp* in the same directory.
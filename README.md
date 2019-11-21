# GatherDocumentation
This is a Python project that can be used to generate documentation of other Python projects.  This can be cloned and added as a Python project.

## Process to generate documentation for another Project
1. Update the conf.py file to add the project root folder for the project to document to the system path (sys.path.insert)
2. Update the index.rst file to include the modules/functions/classes to be documented.
3. Run sphinx-build -M html . <target build directory> to generate the documentation.

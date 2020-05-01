Optimizely Python SDK Sphinx Documentation
=====================

Getting Started
---------------

### Installing documentation requirements

To install dependencies required to generate sphinx documentation locally, execute the following command from the main directory:

    pip install -r requirements/docs.txt

### Building documentation locally

To generate python SDK documentation locally, execute the following command:

    cd docs/
    make html

This will build HTML docs in `docs/build` directory. To open documentation, simply run:
   
    open build/html/index.html
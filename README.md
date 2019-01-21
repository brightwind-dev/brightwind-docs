# brightwind-docs
Holds documentation for brightwind. Documentation is
automated using Sphinx. Gituhb uses gh-pages branch to host the website. In the main repo brightwind the docs folder contains the configuration and makefile needed by shpinx to run.

To update documentation take care of
the following:

One time setup:
- brightwind-docs repo should be in the same directory as
brightwind repo
- pip install sphinx
- pip install sphinx_bootstrap_theme

To run sphinx:
- Open the docs folder in the main repo (brightwind) in 
command prompt
- Type the command-
```Code
make html
```
- This will update all the files in brightwind-docs repo
- Push these changes to gh-pages repo in brightwind-docs

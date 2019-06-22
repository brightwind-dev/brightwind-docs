# brightwind-docs

This repo holds the documentation for brightwind. All setup and creation of the documentation is performed in the main
brightwind repo.

The documentation is created using Sphinx-docs.

The 'gh-pages' branch of this repo holds the actual webpage files created by Sphinx-docs which are
needed for hosting website on github. To review a webpage locally checkout the gh-pages branch to find it.


---
### Sphinx-docs
###### setting up Sphinx-docs
<br>
First clone the 'brightwind-docs' repo to be in the same folder as the 'brightwind' repo.

```
C:\..\brightwind-dev> git clone https://github.com/brightwind-dev/brightwind-docs.git
```
<br>
Then, navigate to the 'docs' folder in the brightwind repo where there should be a 'makefile'. From
here you can download the sphinx-bootstrap-theme using the following command:

```
C:\..\brightwind-dev\brightwind\docs> pip install sphinx-bootstrap-theme
```
<br>

Also install:
```
C:\..\brightwind-dev\brightwind\docs> pip install nbsphinx --user
C:\..\brightwind-dev\brightwind\docs> pip install m2r
```
<br>

If a module file has not yet been created this will need to be done e.g.
```
C:\..\brightwind-dev\brightwind\docs> sphinx-autogen -o  generated source\API.rst
```
<br>

###### running
If already set up then simply run
```
C:\..\brightwind-dev\brightwind\docs> make html
```
<br>


---

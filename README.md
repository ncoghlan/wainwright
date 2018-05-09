# wainwright
A project for building redistributable wagon archives

## Project goals

Be able to deine a meta-project that can:

1. Collect requirements.txt files from a source tree, and use pip-compile to merge them into a single locked-requirements.txt
2. Create setup.py based pseudo-packages to that allow the creation of wagon archives from each of those locked-requirements.txt files (as per https://github.com/cloudify-cosmo/wagon/issues/30)
3. Use those pseudo-packages to emulate workspace support in pipenv (as per https://github.com/pypa/pipenv/issues/2148)

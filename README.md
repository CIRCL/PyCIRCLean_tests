# PyCIRCLean_tests
This repo contains test files for the [PyCIRCLean](https://github.com/CIRCL/PyCIRCLean) project. The files are organized into two directories: files that we expect PyCIRCLean to identify as "Normal" and files that we expect PyCIRCLean to identify as "Dangerous". There is also a yaml file called [file_catalog.yaml] that lists all of the sample files, along with information relevant to running the PyCIRCLean tests using that file.


## How do I add a sample file?

- Add the file to the correct directory, either [normal/] or [dangerous/]
- Add an entry to [file_catalog.yaml]. Try to keep the list in alphabetical order, and follow the template from the other files.

## How do I name sample files?

- If downloaded, use original filename and include link to source.
- If generated, make the filename descriptive about the file's characteristics.

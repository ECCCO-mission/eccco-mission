# Contributing to ECCCO

We welcome all contributions to ECCCO. There might be a little voice inside that tells you you're not ready; that you need to do one more tutorial, or learn another framework, or read a few more blog posts before you can help with this project. That's not the case. Your contributions are valuable and can help improve the software and resulting science. If you ever have concerns, please reach out in [our discussions](https://github.com/orgs/ECCCO-mission/discussions).

## Types of Contributions

There are numerous ways to contribute to the ECCCO mission: providing code and documentation, suggesting and discussing ideas, submitting issues and bug reports, providing working examples and engaging with the broader solar physics, heliophysics, and instrument calibration communities. **We need you** - All code and documentation improvements, suggestions and discussions are valuable to the ECCCO mission and the wider community. **If you have an issue, you can be sure others will have similar issues.**

### Code contributions and pull requests

ECCCO software conforms to high development standards. However, new innovations, better calibration, and bugs are inevitable, some of which we may not identify. You can help us and the user community in general by helping to identify such issues and improve them.

Suggestions to improve existing code and additional packages are both encouraged.

Additional contributions developed by the user community will be reviewed and distributed where other users can find them, use them, and improve them. When developing code we adhere to certain standards (see the Standards & Style Section below) to ensure code is readable, usable, compatible with existing software, and tested for robustness. All contributed code should try and follow similar standards, if this seems daunting do not despair; the we are here to help, and will help you develop your code for inclusion.

#### Standards & Style

PEP (Python Enhancement Proposal) 8 is a Style Guide for Python, and SOC produced code tries to conform to these programming standards. Using PEP 8 helps the software conform to common programming standards as well as avoid mistakes and ensure code readability and internal documentation is sufficient to pass code between programmers working in a multi-developer project. Code and documentation contributors are encouraged to follow the PEP 8 standards, and the [PEP 8 style guide for Python](https://www.python.org/dev/peps/pep-0008/) is a great place to learn about this.

As the ECCCO leverages several [SunPy](https://sunpy.org) and [AstroPy](https://www.astropy.org) packages the ECCCO software tools generally follow the SunPy coding standards, with specific deviations only as necessary to accommodate data processing requirements. SunPy standards are discussed in the [SunPy Developers Guide](https://docs.sunpy.org/en/latest/dev_guide/index.html).

We encourage contributors to follow and embrace the PEP 8, SunPy, and Astropy standards to help produce contributions usable by others, interface seamlessly with existing software, and fit in with the overarching solar and heliospheric Python software ecosystem.

If a contribution produces data products, we encourage the adoption of standard formats such as FITS.

### Documentation contributions

We have developed user guides and development documents to help users navigate data reduction. As with all projects, those that are close to the project may not be aware as to what is not obvious to an end user. You can help us identify these oversights and improve our documentation. **There are no naive questions or suggestions when it comes to documentation, if it’s not clear to you, it’s not clear to others!**

### Example usage contributions

Examples are a powerful way that people learn how to use code. We will provide extensive user examples as part of the development process, but users may use data reduction code and use cases in ways that the SOC did not plan. As such, additional examples, suggestions for new examples, or suggestions to clarify existing examples will help the ECCCO user community and are welcomed by the ECCCO team.

### Sharing Ideas & Suggestions

You do not have to write new code or documentation to contribute. Simply suggesting an idea in our discussions or issues sections on a repository is tremendously helpful.

## Attribution

This guide borrows from a PyCon talk by Adrienne Lowe, which was adapted by by this project based on its use in the README file for the MetPy project. It is modified from the [PUNCH contribution guide](https://github.com/punch-mission/punch-mission/blob/main/contributing.md). 

<!--- Provide the id(s) of the related issue(s) and a general summary of your changes in the Title above -->

## Description
<!--- Describe your changes in detail -->

## How Has This Been Tested?
<!--- this section will disapear when we'll have automated testing -->

<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, tests ran to see how -->
<!--- your change affects other areas of the code, etc. -->

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Hotfix (test on prod)

## Database changes (if applicable)
<!--- If you're adding or deleting a field in the database -->
<!--- Or if you're changing the type of values of a field -->

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

#### optional 
- [ ] My changes require a change to the documentation
  - [ ] I have updated the documentation accordingly
- [ ] If I have added/modified markdown (`*.md`) files in my code, I have made sure that they do not contain formatting errors
- [ ] If my code requires credentials to run, I have made sure to include a template (aka not the actual credentials) in my code and I have updated the `README.md` file with the location of said template

#### Required
- [ ] I've made sure that my code doesn't generate massive amount of logs and I've put [exclusion filters](https://console.cloud.google.com/logs/router/sink?project=theta-byte-156721) if needed
- [ ] My code follows the [code style of this project](https://www.python.org/dev/peps/pep-0008) (`black` has been run on python files).
- [ ] The filenames of my code follow the [PEP-8 standard](https://www.python.org/dev/peps/pep-0008/#package-and-module-names)
- [ ] Any password/secret keys are stored in the [Secret Manager](https://console.cloud.google.com/security/secret-manager?project=theta-byte-156721), for configuration file, these can still be in secrets/env
- [ ] Any and all connections to DB use SSL encryption
- [ ] My code doesn't contain one-letter variables
- [ ] My code doesn't contain any broad exception (`except Exception` or `except` by itself, or gigantic `try/except` blocs)
- [ ] My code doesn't contain any unnecessary comments
- [ ] My code doesn't contain the same hardcoded strings over and over again, they're are stored in constants instead
- [ ] My code uses [fstrings](https://docs.python.org/3/reference/lexical_analysis.html#f-strings) whenever a string concatenation occurs
- [ ] The function names in my code are clear about what the functions do
- [ ] The variable names in my code are clear and are not stripped of their vowels or of part of a word. Readability first
- [ ] I've been carefull about easy to handle errors like [`KeyError`](https://docs.python.org/3.7/library/exceptions.html#KeyError), [`AttributeError`](https://docs.python.org/3.7/library/exceptions.html#AttributeError), [`IndexError`](https://docs.python.org/3.7/library/exceptions.html#IndexError), [`TypeError`](https://docs.python.org/3.7/library/exceptions.html#TypeError)
- [ ] I have included/updated the `requirements.txt` file and it only contains the necessary dependencies (not the parent dependencies and their dependencies)
- [ ] I have included a `README.md` that explains the process existence and installation ([README.md example](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2))
- [ ] All new code or modified code is covered by appropriate unit tests
- [ ] Calls to external APIs or database calls, the tests are mocked in the unit tests
- [ ] I have run the unit tests
- [ ] I have been through this checklist and my code and filled the checklist accordingly

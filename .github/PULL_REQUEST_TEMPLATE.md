<!--- Provide the id(s) of the related issue(s) and a general summary of your changes in the Title above -->

## Description
<!--- Describe your technical changes in detail and add a link to the issue -->

## How Has This Been Tested?
<!--- this section will disappear when we'll have automated testing -->

<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, tests ran to see how -->
<!--- your change affects other areas of the code, etc. -->

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] Refactoring or code optimization 

## Major changes (if applicable)
<!--- If you're adding or deleting a field in the database -->
<!--- Or if you're changing the type of values of a field, please mention it here -->

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

#### Required
- I've made sure that my code doesn't generate massive amount of logs and I've put exclusion filters if needed
- Make sure not to push any secret or password to the code.
- [ ] My code follows the [code style of this project](https://www.python.org/dev/peps/pep-0008) (`black` has been run on python files) and follow the [PEP-8 standard](https://www.python.org/dev/peps/pep-0008/#package-and-module-names)
- [ ] My code doesn't contain any unnecessary comments
- [ ] I've been careful about easy to handle errors like [`KeyError`](https://docs.python.org/3.7/library/exceptions.html#KeyError), [`AttributeError`](https://docs.python.org/3.7/library/exceptions.html#AttributeError), [`IndexError`](https://docs.python.org/3.7/library/exceptions.html#IndexError), [`TypeError`](https://docs.python.org/3.7/library/exceptions.html#TypeError) and doesn't contain any broad exceptions
- [ ] I have included a `README.md` that explains the process existence and installation ([README.md example](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2))
- [ ] All new code or modified code is covered by appropriate unit tests. Calls to external APIs or database calls, the tests are mocked in the unit tests

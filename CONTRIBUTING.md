# How to contribute to patternfly-design

Hello, we are glad you’re here! We need contributors to help PatternFly improve and grow. While code contributions are important, there are many ways that you can get involved and help out.

This page contains some tips and guidelines for contributing to PatternFly. These are just guidelines, not rules. Use your best judgment and feel free to propose changes to this document in a pull request.

## Getting Started


### Read Our Code Of Conduct

PatternFly adheres to the [Contributor Covenant Code of Conduct](http://contributor-covenant.org). As a PatternFly community member, you are expected to uphold this code of conduct, whether that be attending a community meeting, replying to the mailing list or contributing.

### Report Bugs

Before creating a bug report, check the list of known bugs and open issues. Bugs are tracked as GitHub issues. When you create a bug report, include as many details as possible, use a clear and descriptive title, and remember that an image is worth a thousand words, so try to add images and links to rawgit when possible.

### Proposing or Modifying a Design

You may want to start by sharing your idea on the mailing list (patternfly@redhat.com) to kick off the discussion. A design proposal may have many forms, but it should answer these questions:

- What is the name of the design pattern or component?
- What problem does it solve?
- When do you use it or what are the use cases?

Once your design proposal is ready for review, send a [pull request (PR)](https://help.github.com/articles/about-pull-requests/) written in [markdown](https://guides.github.com/features/mastering-markdown/) to the patternfly-design repo (If you can read this, you're already in it!). The PR will be a way to discuss and refine the design with the goal of merging it as PatternFly documentation and making it viewable on patternfly.org. Design documents are living documents, therefore new PRs may be opened to add to or modify the documentation as necessary.



## Contribution guides

If you don’t know how to send a PR using GitHub, don’t worry! We are aware that GitHub was created by and for developers. That’s why we’ve created guides to get you up and running. If you need additional help, contact us.

- [Setting up your contribution environment](https://github.com/patternfly/patternfly-design/wiki/Git-Setup)
  - [Setup Diagram](https://github.com/patternfly/patternfly-design/wiki/Setup-Diagram)
- [Contribution workflow](https://github.com/patternfly/patternfly-design/wiki/Contribution-Workflow)
  - [Contribution Diagram](https://github.com/patternfly/patternfly-design/wiki/Contribution-Diagram)
- [Working with multiple branches](https://github.com/patternfly/patternfly-design/wiki/Multiple-Branches)
  - [Branching Diagram](https://github.com/patternfly/patternfly-design/wiki/Branching-Diagram)


## File Structure

Files in this repository adhere to the following file structure
*Note: Items not ending in a file extension are folder names*

- pattern-library
  - category
    - pattern-name
      - discovery
        - documents
        - img
          - pattern-name-details.png
          - pattern-name-more-details.png
        - discovery.md
      - design
        - documents
        - img
        - design.md
        - overview.md
      - usability-testing
        - documents
        - usability-testing.md

All folder and markdown file names should be in lower case with dashes in place of spaces.
Image file names should include the name of the pattern and, if possible, the defining feature of the image. Most importantly, however is that the name is descriptive and not something like "image13copy.png"

# PLAYGROUND FOR MKDOCS
[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) is a theme for MkDocs. [MkDocs](https://www.mkdocs.org) is a static site generator intended to documenting projects. 

With Material for MkDocs, you create your website using [Markdown language](https://www.markdownguide.org) and have access to several features, including a search bar.

This repository groups my experiences with Material for MkDocs and (possibliy) other static site generators.

## Overview 
The project in the main branch is based on [James Willett's](https://www.youtube.com/@james-willett) excellent [tutorial on setting Material for MkDocs](https://www.youtube.com/watch?v=Q-YA_dA8C20).

> You can check the result at [https://gabrielcostasilva.github.io/doc-mkdocs/](https://gabrielcostasilva.github.io/doc-mkdocs/)

1. Ensure [Python](https://www.python.org/downloads/) is installed and working.
2. Create a folder and go into it.
3. Create a virtual environment with:
```
python -m venv venv
source venv/bin/activate
```
4. Install MkDocs with: `pip install mkdocs-material`
5. Create a website project with: `mkdocs new .`
6. Run your website locally with: `mkdocs serve`
7. Customise your configuration at your will, then build your website for deployment with: `mkdocs build`

To build the website, I used documentation from several repositories on my [Github account](https://github.com/gabrielcostasilva).

James Willett's tutorial teaches how to deploy to Github sites. But can also deploy your static website on [Amazon S3](https://aws.amazon.com/s3/?nc2=h_ql_prod_st_s3). Checkout [this video](https://www.youtube.com/watch?v=JERwGBvBmjA) to find out how.

## Other Examples
- [AWS Copilot CLI](https://aws.github.io/copilot-cli/)
- [AWS Lambda Powertools for Python](https://awslabs.github.io/aws-lambda-powertools-python/)
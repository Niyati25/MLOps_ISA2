MLOps_ISA2
==============================

MLOps Lab Practical Isa2

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/License-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

# Data Science and MLops Project 
Assignment: DevOps Lifecycle Implementation
Objective: Demonstrate understanding and practical application of DevOps principles and tools.
Scenario: You are part of a team responsible for developing and deploying a web application. Your team follows the DevOps approach to ensure smooth collaboration between development and operations teams. You are tasked with setting up the CI/CD pipeline for the application.
Tasks:
1. Version Control (Git):
    - Create a new Git repository for the web application.
    - Initialize the repository with a README file.
    - Create a branch for feature development.
2. Continuous Integration (CI):
    - Set up a CI server (e.g., Jenkins, GitLab CI, or GitHub Actions).
    - Create a pipeline that triggers on each commit to the feature branch.
    - Include steps for linting, building, and running unit tests.
3. Containerization (Docker):
    - Write a Dockerfile to containerize the web application.
    - Build the Docker image locally.
    - Push the image to a container registry (e.g., Docker Hub).
4. Infrastructure as Code (IaC):
    - Use a tool like Terraform or AWS CloudFormation to provision infrastructure (e.g., AWS EC2 instance).
    - Define the infrastructure in code and store it in a version-controlled repository.
    - Continuous Deployment (CD):
5. Modify the CI pipeline to include a CD stage.
    - Deploy the Docker image to the provisioned infrastructure automatically.
6. Monitoring and Logging:
    - Set up monitoring using a tool like Prometheus or AWS CloudWatch.
    - Figure logging to collect application logs (e.g., using ELK stack or AWS CloudWatch Logs).
*Deliverables:*
Share the link to your Git repository containing the code for the CI/CD pipeline and infrastructure configuration.
Provide a brief report detailing the tools and technologies used, along with any challenges faced and solutions implemented.


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Authors

[@Niyati25](https://github.com/Niyati25)

[@giselle06](https://www.github.com/giselle06)

## Feedback

If you have any feedback, please reach out to us at unigoa.ac.in


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?


# Hi, this is Niyati and Giselle two young data science students trying to do our MLOps LAB ISA

***Refer to the work given,***  
you are required to submit the following  report containing the work done and  issues/ challenges handled  and PowerPoint slides highlighting the work done along with required screenshots . the following template may be followed.
1. any two of the work done of the MLOp pipeline (mention them )
2. tools used to carry out the work above and why you chose these tools
3. issues faced , using the tools and how they are handled.
4. the order in which you would like to learn to do the tasks of the MLOps pipeline.
5. how you propose to measure up to the best of the evaluation criteria 
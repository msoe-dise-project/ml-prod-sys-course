# ML Production Systems Course Materials
[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Course materials for [RJ Nowling's](https://rnowling.github.io) ML Production Systems course
at the [Milwaukee School of Engineering (MSOE)](https://www.msoe.edu).

## Course Description
Students will design, implement, deploy, and operate a machine learning-powered service, including components for data processing,
model training, modeling serving, model evaluation, and monitoring.  Technologies and design patterns for streaming and batch data
processing as well as storage systems will be introduced.  This course builds on and integrates previous course work in offline
machine learning and microservices.

### Course Learning Outcomes
Upon successful completion of this course, the student will be able to:

* Design, implement, deploy, and operate a machine learning-powered RESTful service and supporting backend systems
* Design and implement data processing systems that use batch and stream processing patterns and technologies for ingesting and processing event data
* Apply design patterns and data storage systems to design and implement data storage services to support batch and streaming data processing, model training, and model evaluation
* Create distributed systems to support model training and evaluation
* Automate and monitor model training, evaluation, deployment, and operation
* Evaluate and compare architectures of ML-powered systems

### Course Topics

* Distributed batch and streaming data processing platforms and associated programming paradigms
* Data representation and storage patterns to support batch and streaming data pipelines and services
* Reliability, consistency, and scalability challenges and solutions for big data systems
* Patterns for handling model training and evaluation on data that changes or updates over time
* Tradeoffs between batch and streaming systems in terms of efficiency, computational capabilities, and time until updates are available based on new data
* Model serving and deployment
* Monitoring and alerting for services and performance of machine learning model predictions
* Implementation of systems for common machine learning tasks such as classification/regression and recommendations

## Repository Organization

* `handouts`: Contains tutorials, checklists, syllabus, and class schedule.
* `lectures`: Contains class lectures.
* `projects`: Descriptions of projects.

## Additional Materials:

* [Simple Flask Todo REST example](https://github.com/msoe-dise-project/flask-todo-example)
* [Spark example](https://github.com/msoe-dise-project/spark-examples)

## Licensing

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

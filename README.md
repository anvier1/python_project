# Proyecto Ejemplo Python

El objetivo de este proyecto es servir como plantilla a futuros proyectos en Python.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Es necesario desplegar el entorno de python para poder ejecutar este proceso. En el archivo environment.yml están todos los requerimientos necesarios y para crear el entorno a partir de él si ya existe conda es tan sencillo cómo hacer:

```
conda create env -f environment.yml
```
 Para comprobar que se ha desplegado efectivamente listamos los entornos, lo activamos, hacemos un test y lo desactivamos:

```
conda env list
conda activate python_project
python
import numpy as np
exit()
deactivate
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use git for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Angel Moro**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## Acknowledgments

* Github
* Medium
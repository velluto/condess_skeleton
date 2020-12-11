# Condess Skeleton Template
This is a basic template skeleton that can be used for developing a template that is compatible with the Condess system.

# Required Layout

* All parts of a template must be under a common directory
* The __twig directory contains the dynamic templates and fragments required to render the website
* In the root of the template directory there is a configuration file ```template_config.json``` that contains Condess specific information.  
* The template parser will also scan the __twig directory for available handlers

# __twig structure
In the __twig directory there are four required subdirectories:

* components
* handlers
* layouts
* sections



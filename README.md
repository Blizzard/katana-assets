## [Documentation and Reference in the Wiki](Home).

[Katana](https://www.foundry.com/products/katana) is a software application from [The Foundry](https://www.foundry.com/) for managing, surfacing, and rendering complicated scenes in studio pipelines. It was initially developed as part of Sony Pictures Imageworks. Foundry released version 1.0 in 2011.

Katana ships with a plugin system for integrating Katana with a studio's asset system. Creating a plugin involves implementing methods for a plugin base class. Unfortunately this class is largely undocumented and its usage is unintuitive. This wiki intends to be a collection of information gained by introspecting and implementing from experience.

This documentation is specific to implementing Asset API Plugins. Katana provides many other types of plugins, but Asset API plugins remain the most vague. Originally, asset plugins could be implemented in C++ or Python. Current versions have deprecated the Python version, and only C++ is recommended going forward.

This information assumes familiarity with Katana and will reference different nodes and operations Katana performs without describing them. 

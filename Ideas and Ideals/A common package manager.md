# A Common minimal customizable package manager framework for Linux Systems

Tags - #Linux #Software 

Connections - 
- [[APP POOL - Common Software Application]]
- [[Package Managers]]
- [[software licences]]


A modern, minimal customizable framework for distribution and management of software for the Linux Operating System, allowing distributions to build their own package managers on top of this framework and providing basic services so that the general usage and syntax of the package manager remains same with extra functionality added on the top.

## Simple required features - 

1. Common defined naming scheme ==(add link here)== and Package splitting ==(Add link here)== with a proper dependency check and a dependency file to bundle in all the dependencies, markded with two options - Mandatory and Optional with a short description for the Optional dependency about what it does and if it is installed or not like how pacman does it.
![[Optional-dependency.png]]

2. Using a [[permanent index]] for identification of packages and dependency versions.
3. Developer can specify which version to prefer using the [[permanent index]].
4. Software details are given even in CLI form details include -
	- Licence used by the application 
	- description - short and long form, long form descriptions can be a linked man page too
	- Version - preferably [[permanent index]]
	- Mandatory dependencies with the same information
	- Optional dependencies with the same information
5. Compatibility testing with atleast the non-latest supported Debian Stable Release for the dev preferred version, devs can prefer multiple versions.
6. Optional source compiling for advanced users- should be supported by devs if instructions are given by the dev.
7. All [[permanent index]] is stored is a secure repo distributed to all distributions.
8. Compatibility breakage and other news can be conveyed properly.
9. service to tell users some specific details or news when something happens like mirrors going down or an update breaking the system.
10. In-built bug reporting system which has a basic prompt which can be further customised.

## How will we be able to extend the package manager -

- a simple configuration files for the package prompt and dependency management
- ability to extend the basic framework to incorporate more features if the distro requires
- ability to add more repos and other sources
(Add More)

## For developers -

- ability to specify the preferred and supported version
- a single package to provide that too being optional and be distributed through appimages (recommended over flatpak).
- the requirement for support can be version specified.

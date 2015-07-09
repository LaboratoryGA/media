# Media
Claromentis 7.x module which provides a single, unified interface for handling generic media, such as images and CSV files.

## Prerequisities
This module relies on the following:
* ORM module

## Motivation
Currently, each module/subsystem within Claromentis performs it's own media management (poorly). This results in a fairly messy situation of files scattered all over, within various directories, with no centralized way of handling the most basic of functions. Files cannot be re-used between modules or managed in any meaningful way. Even crude CMS systems for minor websites offer a more comprehensive solution.

This module seeks to fill that gaping void.

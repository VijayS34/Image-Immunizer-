# Image-Immunizer-

Image Immunizer
An Image Tamper Resilient Multi-Task Learning Scheme for Image Lossless Auto-Recovery
Abstract
Digital images on social networking sites are vulnerable to various tampering attacks, which can compromise security and privacy. The Image Immunizer project addresses these challenges by introducing a robust scheme for image tampering resistance and lossless auto-recovery using Vaccinator and Invertible Neural Network (INN), a deep learning approach. This project leverages multitask learning to train the network with four key modules: image vaccination, consistency validation, tampered pixel classification, and self-recovery to closely resemble the original image.

Table of Contents
Introduction
System Analysis
System Requirements
Software Description
System Design
System Testing
System Implementation
Appendices
Bottomline
References
Introduction
Overview
The widespread use of social media platforms like Facebook, Instagram, and Twitter has led to increased concerns over digital image tampering. The Image Immunizer project aims to combat these issues by developing a system that ensures image integrity and authenticity through advanced tamper detection and self-recovery mechanisms.

Problem Statement
Photo sharing on social media platforms often lacks sufficient privacy and security measures, leading to unauthorized access and manipulation of images. This project addresses the critical problem of securing shared photos by developing advanced techniques for detecting and preventing Copy-Move, Splicing, and In-Painting attacks.

Aim and Objective
Aim: To enhance the security and integrity of images shared on social media platforms using Invertible Neural Network (INN).
Objective: To develop a system that can immunize images, detect tampered areas, and recover the original content losslessly.
System Analysis
Existing System
Current techniques for image forgery detection are often ineffective on compressed or low-resolution images and lack self-recovery capabilities, making it challenging to reproduce original content once images have been manipulated.

Proposed System
The Image Immunizer introduces an enhanced scheme for image tampering resistance and lossless auto-recovery using a deep learning approach. The system includes modules for image vaccination, tamper detection, and self-recovery.

System Requirements
Hardware Requirements
Standard PC with a multi-core processor
Minimum 8 GB RAM
GPU for deep learning model training (e.g., NVIDIA CUDA compatible)
Software Requirements
Python 3.8 or higher
MySQL 5
WampServer 2i
Flask
Bootstrap
Software Description
Python 3.8: The primary programming language used for developing and training the neural network.
MySQL 5: Database management for storing image data and metadata.
WampServer 2i: Web development environment to host the application.
Flask: Web framework for building the server-side application.
Bootstrap: Front-end framework for creating responsive web interfaces.
System Design
System Architecture
The system architecture consists of several interconnected modules, each responsible for specific tasks such as image vaccination, tamper detection, and self-recovery.

Data Flow Diagram
A detailed data flow diagram illustrating the interaction between different modules and the data processing pipeline.

Database Design
Schema and entity-relationship diagrams for the database used to store images and related data.

UML Diagram
Unified Modeling Language diagrams to represent the system’s structure and behavior.

ER Diagram
Entity-Relationship diagram showing the relationships between different entities in the database.

System Testing
Software Testing
Procedures and methodologies used to test the system’s functionality, performance, and security.

Test Cases
Detailed test cases for each module, ensuring comprehensive coverage of all functionalities.

Test Report
Summary of the testing phase, including identified issues and their resolutions.

System Implementation
System Description
Explanation of the implementation process, including the setup and configuration of different modules.

System Flow
Flowcharts and descriptions of the system’s workflow from image upload to tamper detection and recovery.

Modules Description
Detailed description of each module, its purpose, and its implementation.

Appendices
Screenshots
Visual representations of the system’s user interface and key functionalities.

Source Code
Link to the repository containing the project’s source code.

Bottomline
Conclusion
Summary of the project’s outcomes, highlighting the effectiveness of the Image Immunizer in detecting and recovering tampered images.

Future Enhancement
Potential improvements and additional features that could be incorporated into the system in future iterations.

References
Journal References
Book References
Web References

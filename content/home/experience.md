---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Machine Learning Research Intern
    company: SAS Institute Inc. IDeaS Division
    company_url: ''
    company_logo: SAS_logo_horiz
    location: Minneapolis, MN
    date_start: '2023-01-09'
    date_end: '2023-08-19'
    description: |2-
        Responsibilities include:
        
        * Designed machine learning predictive model using PyTorch for competitors identification through Hidden Markov Model, Convolutional Neural Network and Dynamic Time Warping, improving detection accuracy from 46% to 67%.
        * Developed RESTful APIs for the production system using Java Spring Framework, and implemented a lightweight version algorithms using MySQL, benefiting over 30,000 clients.
        * Designed statistical model to predict errors in forecasting system through Random Forest and ARIMA, decreasing the mean absolute percentage error (MAPE) from 0.17 to 0.04, contributing to over **$12 million revenue**.
        * Designed clustering algorithms utilizing GNN and GAN with TensorFlow. Refactored the base code using Java functional programming, reducing running time from approximately 8 days to around 3 hours.
   
  - title: Software Engineer Intern
    company: Amazon
    company_url: ''
    company_logo: amazon-dark
    location: Seattle, WA
    date_start: '2022-05-31'
    date_end: '2022-08-19'
    description: |2-
        Responsibilities include:
        
        * Designed and implemented new I/O APIs optimizations using C++ that were used by all teams in the AWS Aurora division, reducing the IOPS (Input/Output Operations Per Second) of the AWS Aurora over 80%.
        * Designed a new batch data structure for I/O submission, reducing system calls by a factor of **4,096**.
        * Refactored code to eliminate lock dependencies using multithreading techniques, reducing I/O latency by **77%**.

  - title: Application Security Analyst
    company: Shift4 Payment
    company_url: ''
    company_logo: shift4-payments-vector-logo
    location: Las Vegas, NV
    date_start: '2018-02-01'
    date_end: '2020-08-14'
    description: |2-
        Responsibilities include:
        
        * Led 12 penetration tests on web and mobile applications using Burp Suite, NMAP, Windows shell, and Python. Delivered comprehensive risk assessments and recommended solutions to managers and stakeholders.
        * Led code review processes before application releases, offering in-depth risk assessments and proposing technical solutions to enhance security and programming standards.
        * Developed statistical models using Hidden Markov Model and Exponential Smoothing to detect transaction fraud.
design:
  columns: '2'
---

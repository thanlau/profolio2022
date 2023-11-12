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

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
  - title: CEO
    company: GenCoin
    company_url: ''
    company_logo: amazon-dark
    location: California
    date_start: '2022-05-31'
    date_end: '2022-08-19'
    description: |2-
        Responsibilities include:
        
        * Lead io_uring infrastructure project, a new Linux kernel system call interface for asynchronous I/O to deliver I/O latency and throughout improvements.
        * Self-designed and implemented new I/O backend APIs, used by all teams in AWS Aurora org. The IOPS data get improved by **80%** with 100,000 requests.
        * Developed a new batch data structure to I/O submission. The system call number has been reduced to **1/4096**.
        * Introduced a new workflow for concurrent request handling. Removed all the mutex usages. The latency data get improved by **77%**.

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---

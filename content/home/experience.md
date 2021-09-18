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
  - title: Software Engineer
    company: Microsoft
    company_url: 'https://github.com/azsk/AzTS-docs'
    company_logo: msft
    location: Hyderabad, India
    date_start: '2020-07-27'
    date_end: ''
    description: |2-
        Worked on the Azure Tenant Security Solution (AzTS), that can be used to obtain visibility to cloud subscriptions and resource configuration across multiple subscriptions in an enterprise environment.
        
        * Worked on daily scanning of ~23 million cloud resources within Microsoft for common security threats.
        * Contributed to a cost-effective and time-efficient solution that attempts to share Microsoft's best practices with the cloud community.
        * Designed and developed control checks to combat security risks for various cloud resources.
        
  - title: Student Developer
    company: Google Summer of Code
    company_url: 'https://summerofcode.withgoogle.com/archive/2018/projects/5544927601623040/'
    company_logo: gsoc
    date_start: '2018-05-01'
    date_end: '2018-08-31'
    description: |2-
        Developed Mind The Word, a browser extension that helps users to learn the vocabulary of new languages through language immersion.
        
        * Introduced local caching of translated words in accordance to Zipf's Law, reducing the number of API calls by 55% - 70%.
        * Added viewport limitation for faster rendering of web pages. Changed translation function to decrease render time to under 5 seconds.
        * Extended Text-to-Speech facility to 51 new languages.

design:
  columns: '2'
---

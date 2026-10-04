# Resume Experience Generator

## Overview

The Resume Experience Generator is a module responsible for transforming structured professional experience data into a professional resume experience section.

It organizes job history, responsibilities, achievements, and technical contributions into a clear ATS-friendly format.

The module helps generate consistent and impactful work experience descriptions while highlighting measurable results and relevant skills.

## Experience Data Structure

The generator processes structured professional experience information:

- Job title
- Company name
- Employment period
- Location
- Responsibilities
- Technical achievements
- Technologies used

Example:

```json
{
  "position": "Senior Full Stack Engineer",
  "company": "Example Company",
  "period": "2022 - Present",
  "location": "Remote",
  "responsibilities": [
    "Developed scalable backend services",
    "Built cloud-based applications"
  ],
  "technologies": [
    "Java",
    "React",
    "AWS",
    "Docker"
  ]
}
# Test Diagrams - Playing with Terrastruct

A repository for experimenting with [Terrastruct](https://terrastruct.com), a tool for creating and managing technical diagrams and architecture visualizations.

## Overview

This repository demonstrates the use of Terrastruct for creating layered technical diagrams. It includes automatically generated diagrams showing system architecture and component interactions.

## Contents

### SMS to EMAIL Architecture

The main example diagram shows an SMS to Email system architecture with:
- Multiple layers showing different levels of detail
- Overview diagrams of the complete system
- Detailed component views (Email Service with EXIM)
- Visual representations of data flow and system interactions

## Structure

```
testdiagrams/
├── SMS to EMAIL/           # Main diagram project
│   ├── SMS to EMAIL.png   # Top-level architecture
│   └── Overview/          # Detailed layer views
│       ├── Overview.png
│       └── Email Service (EXIM)/
│           ├── Email Service (EXIM).png
│           └── README.md
```

## Technologies

- **Terrastruct**: Diagram and architecture visualization tool
- **Layered Diagrams**: Hierarchical diagram organization
- **Scenario Modeling**: Step-by-step diagram progression

## Features

- **Automatic Generation**: Diagrams generated from Terrastruct definitions
- **Layered Architecture**: Drill down into different levels of detail
- **Scenario Support**: Show progression and different states
- **Version Control**: Track diagram changes over time

## Use Cases

- System architecture documentation
- Technical communication
- Design reviews
- API and service documentation
- Infrastructure planning

## Viewing Diagrams

1. Clone the repository
2. Navigate to "SMS to EMAIL" directory
3. View PNG files for each layer and component
4. Read accompanying README files for context

## Example: SMS to EMAIL System

The diagram shows an architecture for converting SMS messages to email:
- SMS ingestion layer
- Message processing
- Email service (using EXIM mail transfer agent)
- System overview and detailed component views

![SMS to EMAIL Architecture](./SMS to EMAIL/SMS to EMAIL.png)

## About Terrastruct

Terrastruct is a tool for creating technical diagrams with:
- Code-based diagram definitions
- Automatic layout and rendering
- Version control friendly format
- Layer and scenario support
- Professional output quality

## Status

Experimental repository for learning Terrastruct capabilities and creating technical diagrams.

## Related Tools

- Draw.io / Diagrams.net
- PlantUML
- Mermaid
- Lucidchart
- Microsoft Visio
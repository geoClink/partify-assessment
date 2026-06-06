# Partify Parts Finder

A vehicle parts lookup form built as a coding assessment for Partify Inc.

## Overview

Users select their vehicle's Year, Make, Model, and Product Type from cascading dropdowns and are navigated directly to the matching Partify collection page in a new tab.

## Features

- Cascading dropdowns that filter based on previous selections
- Data fetched from an external JSON file, separating data from logic
- Dynamically constructed collection URLs
- Submit button disabled until all four fields are selected
- Scalable structure ready for a larger catalog or API integration
- Sorted dropdowns — years newest first, makes and models alphabetical
- Error handling for failed data loads

## Technologies

- HTML
- CSS
- JavaScript (Vanilla)

## Live Demo

[View Live](https://geoclink.github.io/partify-assessment)

## Usage

1. Select your vehicle Year
2. Select the Make
3. Select the Model
4. Select the Product Type
5. Click Find Parts to navigate to the collection

## Scalability

The current implementation fetches data from a local `data.json` file. For a production catalog, this could be replaced with an API call to a database or backend service, keeping the form logic identical and allowing the catalog to grow without touching the UI code.
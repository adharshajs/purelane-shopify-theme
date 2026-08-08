# Purelane Shopify Homepage

A Shopify theme implementation recreating the provided Purelane homepage reference as a responsive, section-based Shopify theme.

## Project Overview

This project recreates the Purelane homepage using Shopify Liquid sections, JSON templates, CSS, and SVG assets.

The homepage was broken into reusable sections so that the page structure is easier to maintain and extend within Shopify.

## Homepage Sections

The implementation includes:

* Hero section
* Ingredients section
* Why It Works section
* Bundles section
* Build Your Bundle section
* Bestsellers section
* Bundle Benefits section
* Purelane Club section

The sections are connected through:

`templates/index.json`

## Tech Stack

* Shopify Liquid
* Shopify JSON templates
* HTML
* CSS
* SVG assets
* Git / GitHub
* Shopify Theme CLI

## Responsive Design

The homepage was implemented for both desktop and mobile layouts.

The responsive behavior was tested using:

* Desktop browser preview
* Shopify Theme Dev preview
* Mobile device preview

The hero product artwork was implemented using extracted SVG bottle assets:

* `kitchen-bottle.svg`
* `tap-bottle.svg`
* `metal-bottle.svg`

## Build Notes

### What I flagged about the original/reference file

The original/reference homepage was primarily a visual prototype and contained content and layouts that needed to be translated into Shopify-native theme sections.

The main challenge was converting the reference structure into reusable Liquid sections while keeping the visual layout and responsive behavior close to the reference.

### What I changed

I converted the homepage into individual Shopify Liquid sections and connected them through `templates/index.json`.

I also:

* Recreated the hero layout and responsive product presentation.
* Added the ingredients section.
* Added the "Why It Works" section.
* Added bundle and bundle-benefit sections.
* Added the build-your-bundle section.
* Added the bestsellers section.
* Added the Purelane Club section.
* Added responsive mobile styling.
* Extracted and reused the provided bottle artwork as SVG assets.
* Added the required styling in `assets/troopod.css`.
* Updated the Shopify theme layout and homepage template configuration.

### Why I made these changes

Breaking the homepage into separate sections makes the implementation easier to understand, maintain, and extend in Shopify.

It also allows individual sections to be modified or reused without having to maintain one large homepage file.

### What I would do with more time

With additional time, I would:

* Connect the displayed products and prices to real Shopify product data.
* Connect bundle selections to Shopify cart functionality.
* Implement real add-to-cart and bundle interactions.
* Connect the Purelane Club form to Shopify/customer or email marketing functionality.
* Replace remaining static content with dynamic Shopify data where appropriate.
* Improve accessibility, semantic HTML, and keyboard navigation.
* Perform additional cross-browser and device testing.
* Further refine spacing, typography, and visual details against the original reference.

## AI Workflow

AI was used as a development assistant throughout the implementation rather than as a replacement for testing and decision-making.

### What I delegated to AI

I used AI to assist with:

* Translating the reference layout into Shopify Liquid sections.
* Generating and refining CSS.
* Structuring `templates/index.json`.
* Troubleshooting Liquid and CSS implementation issues.
* Debugging responsive behavior.
* Suggesting implementation approaches for the Shopify theme structure.
* Reviewing Git and development workflow issues.

### Where AI failed or needed correction

AI-generated code sometimes made assumptions about:

* Existing theme structure.
* Asset paths.
* Responsive breakpoints.
* How Shopify theme files were organized.
* The visual behavior of elements on different screen sizes.

Some generated implementations were technically valid but did not initially match the visual reference closely enough.

I therefore tested the implementation in the actual Shopify Theme Dev environment and made corrections based on the rendered result.

The main lesson was that generated code should be validated against the actual application rather than accepted without testing.

### What I would systematise for 20 similar projects

If I had to build twenty similar Shopify pages, I would standardise:

1. A reusable Liquid section structure.
2. A consistent CSS design system.
3. Standard asset naming and organization.
4. A repeatable desktop/mobile QA checklist.
5. Automated validation of Liquid and JSON structure.
6. A standard Git commit workflow.
7. A component checklist covering layout, responsiveness, assets, accessibility, and interactions.
8. A consistent AI workflow where AI handles repetitive implementation and debugging while visual validation and final engineering decisions remain manual.

## Metafields / Metaobjects

No custom metafield or metaobject definitions were created for this implementation.

The homepage content is implemented using Shopify theme sections and the homepage JSON template.

## Git History

The repository preserves the project development history, including the original Dawn baseline and the Purelane implementation.

Key commits include:

* `Dawn 15.5.0 (#3935)`
* `Recreate Purelane homepage sections`

## Local Development

The theme can be previewed using Shopify Theme CLI.

Example:

```bash
shopify theme dev --store=purelane-by-adharsha.myshopify.com --host=0.0.0.0
```

The Shopify Theme Dev preview can then be opened in a browser or tested on a mobile device connected to the same network.

## Repository

GitHub:

https://github.com/adharshajs/purelane-shopify-theme

## Dev Store

Store:

https://purelane-by-adharsha.myshopify.com

The store password is provided separately as requested in the assignment deliverables.

## Submission

This repository contains the Shopify theme implementation, supporting assets, homepage sections, responsive styling, and project notes requested for the assignment.

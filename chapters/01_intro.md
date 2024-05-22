# Introduction

Welcome to Free and Open Source Geospatial Tools. This book provides resources and examples of open source geospatial software and solutions. Please cite as

Russell, Vance. 2024. Free and Open Source Geospatial Solutions. Jupyterbook.org or Bibtex:

@book{vrussell2024,
	title		  = {Free and open source geospatial tools},
	author		  = {Russell, Vance},
	year		  = {2024},
	publisher	  = {jupyterbook.org},
	url 		  = {https://3point.xyz/geosp-bib}
}

## Support

This book is free to use for anyone. If you want to support me, donate, or buy me a coffee, please go to my [buymeacoffee](https://www.buymeacoffee.com/3point) site. I will be adding chapters and resources in the future. Please make to cite it or share it with others that might benefit. Thank you for your support!

## Why this book

Accessing, processing, and analyzing geospatial data can be daunting, often hindered by data accessibility, compatibility, and cost constraints. There are a lot of geospatial resources, tutorials, and books out there, but most focus on specific tools, such as Spatial SQL {cite}`forrest2023`, the Cloud Based Remote Sensing with Google Earth Engine remote sensing {cite:p}`eefa` or Quisheng Wu's excellent geospatial data analysis book using Geemap and Earth Engine {cite}`geemap`. This book resource provides a beginner's guide to getting going with each of those and compares free and open-source software to paid resources and books.

At the software level, many tutorials, github repositories, and software sites assume you have familiarity with installing software or running code. They'll use acronyms such as CLI and IDE; if you're a beginner, you will have no idea what they're talking about. Once you decipher the terms, running into errors and trying to fix them can be trying or just a downright deterrence to using free and open-space geospatial software. Don't be put off by entering this new world; keep at it when errors occur.

The FOSS book aims to address these challenges head-on by providing practical solutions and resources. Because you want to analyze and visualize data, not spend time looking through stack exchange or asking ChatGPT how to fix an obscure error when your code doesn't run, or your laptop won't install a package correctly.

## Audience & Learning

The intended audience for this book is beginners to geospatial analysis with some knowledge of desktop tools such as ArcGIS Pro or QGIS and limited knowledge of coding using Javascript or Python. Ideally you will have taken an introductory geography and computer science course introducing you to software and languages. If not, you can still get by and get started in each chapter, but some background work will be required, e.g., installing Leafmap or Geemap. Nevertheless, each chapter will offer resources and tutorials to get you up to speed.

## Chapters

The book will contain (some chapters are still in draft) the following chapters:

1. **FOSS**. This is an introduction to Free and open-source software and a little about my journey in this field and my use of these tools.
2. **GEE**. Google Earth Engine is an incredible resource for its large data catalog and cloud-based geospatial analysis. This chapter provides some quick tips and steps to get started.
3. **Proscons**. Outlines the pros and cons of free and open source vs. paid geospatial software.
4. **Python**. Using Python for geospatial data analysis and visualization with a variety of libraries.
5. **QGIS**. There are many QGIS tutorials and a supportive community. This chapter will help you learn the basics of using this powerful geospatial software.
6. **SQL**. Starting to use the universal database Structured Query Language or SQL using DuckDB and Post-GIS spatial packages.
7. **AIML**. Artificial intelligence (AI) and machine learning (ML) are sorta popular right now, no? Here's how to use these tools to complement, not replace, your work.
8. **R**. A programming language universally adopted by academics, R is easy to use and get started with and has many statistical computing, data visualization, and geospatial packages. We'll use it within the free desktop integrated development environment (IDE).
9. **Future**. We'll look into a crystal ball—actually a globe—for some thoughts and insights into the future of free and open-source geospatial software.

## Github, Colab & Binder

The entire book is stored on a Github repository accessible by clicking the Github logo at the top right. Each chapter is also available in Binder and Colab to make running the code easier if you do not have your own integrated development environment (IDE), such as Visual Studio Code set up. I recommend that you set up VS Code to run software; guidance for how to do can be found in the Appendices.

## jupyter{book}

This book was made using [Jupyter Books](https://jupyterbook.org/), a free and open source package that lets anyone build beautiful, publication-quality books and articles from computational content. Thank you, Jupyter Books, for this wonderful resource!

## Acknowledgements

I would like to thank and acknowledge many of the free and open source geospatial pioneers out there who offer their incredible resources and dedication to the trade. I've learned so much from you, not just about geospatial analysis but also about the value of geographic information, analysis, and generosity.

Much of this book is adapted from Quisheng Wu's extensive, innovative, and useful geospatial resources, such as Geemap and Leafmap. Dr. Wu's vast geospatial knowledge, tutorials, videos, and courses are an incredible learning resource. Thank you, Quisheng! I only hope this complements your work.

A special thank you to my family while I wrote this in the early AM or late PM hours. Your love and support are always an inspiration to me. A special extra thank you to my spouse who inspired me to get more serious about geospatial analysis. It's hard to start doing this when you have a Ph.D. in the house with a degree in ecological remote sensing, but you always encouraged me and, with some sighing, helped explain many things. Thank you, Emma!

```{tableofcontents}

```
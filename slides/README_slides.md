---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
<!-- 
+++ {"slideshow": {"slide_type": "slide"}}

# Tutorial slides

- Slides are optional (e.g., you may not use them if your presentation is via live coding).
- If the pre-recorded presentations will use slides, we request that you deposit the slides in this folder.

+++ {"slideshow": {"slide_type": "slide"}}

## Use text-based source

- We ask that you use text-based formats for your slides, e.g., markdown 
- This markdown file is an example source for slides using `nbconvert` and Reveal. See the GitHub action '.github/workflows/slides.yml' in this repo so see how this markdown file is converted to a HTML slide show and published on GitHub Pages - https://fawazsiddiqi.github.io/slides_to_pages

+++ {"slideshow": {"slide_type": "subslide"}}

## An example sub-slide

- Another option: you can write your slide content using markdown and use an app for slide design, like [Deckset](https://www.deckset.com) or similar.

+++ {"slideshow": {"slide_type": "slide"}}

## Naming convention and file list

- Use a **naming convention** where each file name starts with a number, reflecting the order of use in the presentation of the tutorial.
- List your slide files in a markdown, with a brief description.


+++ {"slideshow": {"slide_type": "slide"}} 
-->


**🌟 Overview** <br />
Learn about the first step of any Data Science Methodology - Data Collection and Data Cleaning and how easily it can be achieved by using the Data Refinery Tool. Explore a sample data set and generate visualizations to get more insights & relationships within our data, clean the data accordingly, and enhance your business by taking quick meaningful decisions.


**🎓 What will you learn?** <br />
- Introduction to Watson Studio & Data Refinery
- Data Cleaning - what, why, how
- Exploratory Data Analysis (EDA)

**👩‍💻 Who should attend?** <br />
- Students who are interested in AI, Data Science but don't know where to start
- Data Science & AI enthusiasts who want to learn how IBM can help you
- Professional Developers who want to know more about the world of Data & AI
- People who want to perform Data Cleaning without writing code

+++ {"slideshow": {"slide_type": "subslide"}}

**🎈 Prerequisites** <br />
- Any prior experience with Data Processing would be advantageous. If you have no prior experience, read this blog as reference: https://towardsdatascience.com/data-analysis-using-excel-885f337c85c
- Register for a free IBM Cloud Account: https://ibm.biz/BdfpGB

🍉 Register for the live stream and replay on Crowdcast: <br/>
- Register for the live stream or to watch the replay: https://www.crowdcast.io/e/faster-data-cleaning

👩‍💻Resources <br />
- GitHub Repository - https://ibm.biz/data-refinery-repo
- Workshop Slides - https://ibmdevelopermea.github.io/Speed-up-your-Data-Cleansing-with-Data-Refinery/
- Survey - https://ibm.biz/data-refinery-survey
- Follow along for the hands-on: https://developer.ibm.com/learningpaths/cloud-pak-for-data-learning-path/data-visualization-with-data-refinery/
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide1.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide2.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide3.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide4.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide5.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide6.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide7.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide8.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide9.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide10.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide11.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide12.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide13.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide14.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide15.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide16.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide17.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide18.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide19.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide20.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide21.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide22.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide23.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide24.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide25.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide26.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide27.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide28.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide29.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide30.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Speed-up-your-Data-Cleansing-with-Data-Refinery/blob/main/images/slide_images/Slide31.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

## License

**Recommend** that slides be shared under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.

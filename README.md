# Classify space rocks using python and AI

# Description

This learning path gives you a view into the worlds of AI and space. Learn how to create an AI model that can classify the type of space rock in a random photo.

This is a Microsoft course with the same name to learn about space rocks and how to classify them.

### Prerequisites

- [The role of python in space expliration learning path](https://github.com/Jeffresh/Discover-role-python-space-exploration)
- A basic understanding of Python for Data Science

# Learn about space rocks and how to classify them

## Ways to use AI to improve space rock research

Integration AI into this process can imporve the collection process for both humans and rovers. For example, we could send astronauts to the Moon armed with a computer that can take photos of rocks. The computer could tell the astronaut what type of rock it likely is. The astronaut could then determie if that type of rocks is needed in the collection and decide to take it or not. This computer could also be placed in a rover that could autonomously drive across the surface of the Moon and scan for rocks that we need for research.

By integrating AI, astronauts could more quickly and accurately locate and identify rocks they should bring back to Earth. The computer also culd collect metadata like location, temperature, and light exposure. With accuracy feedback from astronauts and scientists on EArth, The AI model used to identify valuable rocks would be improved overtime.

## AI on Earth

As we mentioned earlier, AI performs better when the sample data is cleaner. We mean not only when the rocks are physically clean, but when the photos of the rocks have similar lighting (so the visual coloring of the rock is consistent), when edges between the rock and the background are clean and consistent, and when each photo has a clear indicaton of scale. An AI model that ould help identify, classify, and track these samples would provide clear instructions about how to take the photos to fit the current model. With an AI model that fits these criteria, lunar rock curation and lunar rock research would move toward answering even more nuanced research questions. Additionally, we could use a rover and AI on Earth to collect meteorites in Antarctica.

## The future of AI in space

Although AI and image quality might not be cood enugh today totake a satellite image of a planet's surface and five an overview of the types of rocks that are on it, we can start to understand where AI can help and whre it's limited.

## Explore a NASA mission that studies space rocks

Many space missions have taken astronauts and rovers into space to search for space rocks. One of these missions is the [OSIRIS-REx mission](https://www.asteroidmission.org/objectives/)

The OSIRIS-REx mission consist of launching a spacecraft into orbit and gathering sampels from an asteroid named Benny. Benny's regolith space rock might record the earliest history of our Solar System. The OSIRIS-Rex mission is all about finding out more about where humans came from adn what our destiny is.

This mission is unique compard to the other types of missions that we have taled about. The OSIRIS-REx will take high-quality photos while it is in orbit, and it will land and gather samples. The photos will be sent to torck experts on EArth, whi will analyze features of the photos that might give us information about sour Solar System.

Visit the [OSIRIS-REx website](https://www.asteroidmission.org/galleries/) to learn more and see some amazing photos captured from the spacecraft.

## Summary

In this module, you learned about different types of space rocks and the forms they can take. You also learned about the challenges of gathering spacerocks, and a solution to the problem.

# Prepare to research space rocks by using artifical intelligence

Learn about the scientifci research of space rocks and how artifical intelligence can enhance research.

## Introduction

You're a geologist working for NASA. Your job is to let the astronauts know which rocks to pick up on their trip to the Moon.(You would go to the Moon to pick them out yourself, but you have a fear of heights). Because astronauts have many other things to learn, teaching them about different space rocks isn't practical. Instead, you deciee to create and artifical intelligence(AI) program that the astronauts can use to take a photo of a rock and find out what type of rock it is. Providing an AI program for astronauts helps ensure that you get enough samples of every type of rock you need.

In this Microsoft Learn module, you'll learn what AI is, and you'll use some libraries that will help you create a program that classofies rocks. The final project uses Visual Studio Code, Python, and Jupyter Notebook to create and AI model that can identify the type of a rock in an image.

The data is provided by NASA. Explore more interesting photos in NASA's [sample collecition](https://curator.jsc.nasa.gov/lunar/samplecatalog/index.cfm)

## Learning Objectives

In this module, you will:

- Get and introduction to artificial intelligence
- Discover how humans classify objects
- Discover how machines classify objects
- Learn about artificial intelligence libraries
- Install artificial intelligence libraries

## Prerequisites

- Ability to write and run introductory Pyhon programs
- Visual Studio Code, a Python extension, and Jupyter Notebook installed.

## The role of AI in research into space rocks

AI is afiarly new but prominent concentration in the field of computer science, and more specifically, data science. The main concept of AI is teaching a computer how to learn thins. The compjter then makes decisions based on what it has learned things. The computer then makes decisions based on what it has learned.

Although you might think that teaching computers hwo to "think" on their own would lead to extinction for the human race, computers need humans to program them. We don't need to worry that computer might take over the world, but we can benefit from programming computers to make decisions. AI is what Netflix uses to recommend what to watch next. AI helps Siri better detect our phone use habits. Tesla uses AI to build driverless cars.

AI works by giving many different pieces of data to a computer, and then telling the computer what that data represents. WE'll give a computer different images of space rocks and tell the computer what type of rock is in each image. For example, we'll upload a photo of basalt rock to our computer and tell the computer that the photo isa photo of basalt rock. This process is the first step of building and AI mode. You use a model to make predictions. After we show the computer a large number of images and create a model based on that data, we can give the computer a new photo that doesn't have a label, and the computer should be able to tell us what type of rock it is.

Finally, you might see the terms *machine learning* and *artificial intelligence* used almost interchangeably. The main difference between the two is that machine learning is a type of AI. They are similar, but in this module we focus on AI.

## Different types of space rock that are used for research

Before we learn the details of how AI can be used to classify rocks, let's start by learning about the different types of rocks that we'll be working with. And, we'll see how well you do at classifying rocks.

## Types of rocks

In this lesson, we'll classify photos of rocks into one of two types: basalt and higland (also known as crustal). These rock types also are found on Erath, but for this lesson, we are looking only at the lunar variants: that is rocks that are from the Moon.

Basalt is a dark rock that comes from ancient volcanic eruptions on the Earth's Moon. When you look up at the Moon and see dark spots and patches, you likely are seeing basalt rock on the Moon's surface. Nearly 17% of the near side of the Moon is basalt; only 2% of the far side is basalt. Only 2% of the far side is basalt. Most basalt in either of the Moon's hemispheres is found in basins or large craters.

Higland rock is lighter than basalt because basalt is made of heavier elements, like iron and magnesium. Higland rock was made when a large magma ocean, which covered the entire Moon as it formed, crystallized. Higland rock is lighter, so it floated to the top of the ocean adn became the crust of the Moon.

It's very  hard to classify this rocks because it looks both like highland and basalt rock. Computers are great at finding the smaller details that the human eye can miss. This is how artificial intelligence can assist us.

## Classify space rocks like a human

Before we build and AI system to detect the rock types, let's consider how humans classify things.

Out thought process usually goes something like this:

### Step 0

We want to collect as many rock images as possible. Having a large number of images helps us see a large number of variations in the items we're trying to classify. Fortunately, in this project, we can choose from a large number of relevant images online.

### Step 1

First, our brain tries to extract patterns from each image. The patterns include the following factors:

- Color combinations
- Sharp edges
- Circular patterns
- Texture in the rock's surface
- The size of the rock
- The size and shape of minerals in the rock

Our brains subconsciously do all of these visual searches and categorization without our notice. In AI, we refer to these factors as *features*.

### Step 2

Next, we try to find the relationships between the features and the type of rock is hown in a photo of a rock.

In this step, our brain tries to separate or collate the characteristics and features of each type of rock. Because of the associations we make, we come up with some rules. For example, we determine that lighter rocks usually are higland rocks and that the texture of basalt rocks is more jagged.

### Step 3

Last, we try to use these relationships between known items to determine how to classify a new item. Given a new rock iamge to consider, our brains extract tis characteristics. Then, our brain uses the associations we already made to determine what type of rock it is.

## Classify space rocks like a machine by using AI

The job of the AI scientist in creating an AI model is to teach the computer to complete three steps. Let's walk through the three steps in the example of training a computer to predict types of rocks in random photos of rocks.

### Step 0

A preparatory step is to import image data and the libraries that help process them on the computer you're training. The computer transforms the images to matrixes of number so that the images are in a format the computer can read.

### Step 1

In photos of rocks that we'll examine, the computer extracts features like texture, size, color, and edges. Scientist use intuition and experience tho choose which features to use.

### Step 2

The computer makes associations between image features and types of rock. Computers can be better than humans at the task of detecting minute details because there are so many associations to make.

The computer builds a network that's capable of keeping track of millions of associations.

### Step 3

Given a new photo of a rock, the computer extracts features in the photo, and then uses associations between existing data and the new photo to predict the type of rock it is.
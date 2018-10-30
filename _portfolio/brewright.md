---
layout: post
title: Brewright
thumbnail-path: "img/brewright.png"
short-description: The basic framework for a recipe building program for homebrewers and professionals.

---

{:.center}
![]({{ site.baseurl }}/img/brewright.png)

## Explanation

This program is intended to help brewers create recipes and visualize the necessities of a brewing session in a standardized and easily readable format.  At the moment the app only allows the user to create ingredients, customize their attributes, and add them to a recipe.  The final product aims to also provide predicted outcomes of the constructed recipe like the alcohol content, color, bitterness, and compare the recipe's values to a style of beer they intend to create.  It will also provide more advanced information like water volumes and target temperatures needed to achieve their targets.  The user will also be able to fine tune the calculations that work behind the scenes and will be provided helpful information about what the various parts of these calculation mean, and what typical values should be expected from real world examples.  The app's intention is to provide new brewer's with helpful information about how to construct a brewing recipe, its possible outcomes, and how it compares to other styles, while also allowing knowledgeable brewers to fine tune their recipes based on their experience and particular brewing system to achieve the desired resulting beer.

## Problem

There are several good recipe builders available for free online, and a multitude of tools available on various sites to aid a brewer in constructing a recipe.  However, few are a one stop shop that will provide all the information the brewer needs, and if they do, they often do not provide it in one easily navigable page.  As both a homebrewer and brewing professional I found this rather obnoxious and wanted to build an ultimate tool that could provide all the pertinent information and calculations necessary for a brew on a single page that would allow a user to construct, customize, and predict a brew with all the pertinent information readily available.  This would help new brewers learn about the variables they have control over and the effects of changing them while also allowing experienced or professional brewers to hone their recipes and improve consistency. 

## Solution

I aim to create an application that will let users add various ingredients to a database so that the user can add them to a recipe.  The recipe builder would use the attributes provided about those ingredients to calculate a predicted outcome of combining those ingredients.  It would also allow the user to fine tune the calculations that create these outcomes so that a very experienced brewer who knows that their system or process may vary from what is typical can be sure that the predicted results in the recipe will match the results in the real world.  This will also help ensure new recipes can be done right on the first try.

## Results

The current application is far from completed, but it does allow the user to create various kinds of ingredients, define their attributes, add those ingredients to a recipe and save that recipe to view or edit it later.

## Conclusion

The greater aim of this project proved to be too large to achieve in the time frame allotted, but the various databases needed to achieve the end result have been started providing a cornerstone on which to build the rest of the applications logic upon.

[You can test out the start of something big here.](https://brewright.herokuapp.com/)

[See it on GitHub](https://github.com/conkytom/brewright)
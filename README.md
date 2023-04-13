# Thoughts about improving the documentation of wagtail

[Wagtail](https://wagtail.org/) is a Content Management System (CMS), like WordPress, Joomla, Drupal, Wix, Magento. I could go on.

[Wagtail is written in Python](https://github.com/wagtail) and is based on [the Django Web framework](https://www.djangoproject.com/). 

Unlike other CMS software, with Wagtail currently you need to do Python coding in order to create something useful and beautiful. The Wagtail project is not clear whether that may change in the future. There should be some discussion document on reusable components (themes, plugins), whether they may come at some point in the future or these reusable components are not really required. The [Wagtail Packages](https://wagtail.org/packages/) list has a number of packages, though a cursory look shows several of them not being actively developed anymore. Wagtail is currently at version 4.0. Versions 3.0 and 4.0 where relased in 2022. Version 2.0 in 2018.

## Opportunities

The CMS market is currently rather saturated. Most new Wagtail users are likely to come with experience from some other CMS software. This requires documentation of two sorts:
1. Learning Wagtail for those that have experience with CMSx. The terminology and the workflows of that other CMS should be translated into Wagtail. These users should get a feeling of familiarity. When you write the documentation for Wagtail for this aspect, you need to go through the respective Getting Started of the other CMS. An easy first step to work with this, is to create _Wagtail for CMSx users_ documents. 
1. Migrating your CMSx installation to Wagtail. There is work on this for the [Migration from WordPress to Wagtail](https://wagtail.org/blog/wordpress-to-wagtail-migration-kit/) and [relevant github repository](https://github.com/torchbox/wagtail-wordpress-import). This is really big for Wagtail. An easy first step is to write a _Stock WordPress installation to Wagtail Migration_ document. Once mastering that, then you can figure out the complexities of a real WordPress installation migration document.

## Types of new Wagtail users

Wagtail is currently developer-centric. You need to be a software developer (Python) to be able to work with Wagtail.

I consider knowing Python as a prerequisite to working with Wagtail. As long as there are no reusable components yet, the guides should be upfront about the requirement. 

Then, there are two groups of new Wagtail users.

1. Those that are familiar with Django.
2. Those that are familiar with Python but not yet with Django.

How important is it to learn some things first about Django (_Django, for prospective Wagtail users_)? There should be Wagtail documentation that helps new users get a good understanding of using Django. Either point to specific Django documentation or host it's own Django documentation for Wagtail users. 

## Strategy

The short-term strategy is to

1. Demonstrate the benefits of using Wagtail.
2. Get the motivated new users to follow the Getting Started Guide

The [bakery demo](https://github.com/wagtail/bakerydemo) is a good example of a beautiful creation with Wagtail. 

## Links

[Awesome wagtail](https://github.com/springload/awesome-wagtail)

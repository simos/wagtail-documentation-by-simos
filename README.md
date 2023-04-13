# Thoughts about improving the documentation of wagtail

[Wagtail](https://wagtail.org/) is a Content Management System (CMS), like WordPress, Joomla, Drupal, Wix, Magento. I could go on.

[Wagtail is written in Python](https://github.com/wagtail) and is based on [the Django Web framework](https://www.djangoproject.com/). 

Unlike other CMS software, with Wagtail currently you need to do Python coding in order to create something useful and beautiful. The Wagtail project is not clear whether that may change in the future. There should be some discussion document on reusable components (themes, plugins), whether they may come at some point in the future or these reusable components are not really required. The [Wagtail Packages list](https://wagtail.org/packages/) has a number of packages, though a cursory look shows several of them not being actively developed anymore. Wagtail is currently at version 4.0. Versions 3.0 and 4.0 where relased in 2022. Version 2.0 in 2018.

## Opportunities

The CMS market is currently rather saturated. Most new Wagtail users are likely to come with experience from some other CMS software. This requires documentation of two sorts:
1. Learning Wagtail for those that have experience with CMSx. The terminology and the workflows of that other CMS should be translated into Wagtail. These users should get a feeling of familiarity. When you write the documentation for Wagtail for this aspect, you need to go through the respective Getting Started of the other CMS. An easy first step to work with this, is to create _Wagtail for CMSx users_ documents. 
1. Migrating your CMSx installation to Wagtail. There is work on this for the [Migration from WordPress to Wagtail](https://wagtail.org/blog/wordpress-to-wagtail-migration-kit/) and [relevant github repository](https://github.com/torchbox/wagtail-wordpress-import). This is really big for Wagtail. An easy first step is to write a _Stock WordPress installation to Wagtail Migration_ document. Once mastering that, then you can figure out the complexities of a real WordPress installation migration document.

## Types of new Wagtail users

Wagtail is currently developer-centric. You need to be a software developer (Python) to be able to work with Wagtail.

I consider knowing Python as a prerequisite to working with Wagtail. As long as there are no reusable components yet, the guides should be upfront about the requirement and provide guidance. Currently, at the top of [Getting Started](https://docs.wagtail.org/en/stable/getting_started/index.html) there is the note that _These instructions assume familiarity with virtual environments and the Django web framework._

Then, there are two groups of new Wagtail users.

1. Those that are familiar with Django.
2. Those that are familiar with Python but not yet with Django.

[Django has quite good documentation](https://www.djangoproject.com/start/). The style should be replicated in Wagtail; not because it's only good but because new Wagtail users would already feel familiar with following the Django documentation.

## Review of Django Getting Started

This is [the index page of Django Getting Started](https://www.djangoproject.com/start/).
1. In the first part it advises to either go through the tutorial or go directly to full documentation site.
2. Then, it deals with the Installation. They should have added more information in the installation, including how to verify the installation works and a roubleshooting section.
3. Next, it takes you to the Django tutorial. The tutorial is split into sizable incremental parts, which is very good. Most of the parts have an overview (of that part) at the start and _What Next_ at the end. The command line environments have tabs that show the command for MacOS/Linux and Windows.


## Review of existing Wagtail tutorial

[I've annotated the current tutorial, specifically the part about the Installation](https://simos.github.io/wagtail-documentation-by-simos/Your%20first%20Wagtail%20site%20%E2%80%94%20Wagtail%20Documentation%204.2.2%20documentation%20(4_9_2023%203_47_03%20PM).html). My comments are in the green notes. 

The [bakery demo](https://github.com/wagtail/bakerydemo) is a good example of a beautiful creation with Wagtail. In its full form, how many tutorial parts would it take to cover all the material? 

## Links

[Awesome wagtail](https://github.com/springload/awesome-wagtail)

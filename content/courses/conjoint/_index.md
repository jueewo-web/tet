---
# Course title, summary, and position.
linktitle: WebConjoint
summary: How to use Conjoint Analysis to measure implicit preferences.
#Learn how to use Academic's docs layout for publishing online courses, software documentation, and tutorials.
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  conjoint:
    name: Overview
    weight: 1
---

Conjoint measures preferences implicitly. This is crucial when (product) features need to be traded mutually. Many real-world decisions require to trade one feature for another, e.g. high quality and low price are precluding each other, so it’s necessary to trade quality for price or vice versa. Traditional measurements (e.g. surveys, interviews, etc.) are testing features separately (itemized). In the case of related features, traditional tools produce incorrect results.   The interactive tool WebConjoint is using a joint measurement of how the features of products and services are mutually traded. It provides a correct measure of the preferences and gives an insight into the customer’s decision making.

---

{{< vimeo 391101637 >}}


<!-- 
## Flexibility

This feature can be used for publishing content such as:

* **Online courses**
* **Project or software documentation**
* **Tutorials**

The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## Delete tutorials

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`. -->

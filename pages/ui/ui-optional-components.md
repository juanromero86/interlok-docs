---
title: Optional Component Discovery
keywords: interlok
tags: [optional_components, ui]
sidebar: home_sidebar
permalink: ui-optional-component-discovery.html
summary: The Optional Component Discovery page allows you to browse components that can be added to Interlok. (Since 3.5.1)
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/dLzBihUtYeE" frameborder="0" allowfullscreen></iframe>

## Getting Started ##

To access the Optional Component Discovery page, you use the optional components button on the header navigation bar, which is located in the Config sub-menu.

The header navigation bar:

 ![Navigation bar with optional shown](./images/ui-user-guide/optional-nav.png)

## Optional Component Discovery Page ##

Upon opening the discovery page, the ui will connect to our public facing [artifact server][] and compile list of the components from the releases repository. Each components build file is then read and a dataset of information regarding each component is compiled and shown on this page.

The discovery page upon opening:

 ![Optional Component Discovery Page](./images/ui-user-guide/optional-main.png)

The page contains search tools and a list of discovered components:

 ![Optional Component Discovery Page Annotated](./images/ui-user-guide/optional-main-annotated.png)
 
## Optional Component ##

The optional component itself has the following options:

![Optional Component Discovery Page Annotated](./images/ui-user-guide/optional-component-annotated.png)
 
## Optional Component Details ##

Clicking on the view more details button shows the optional component details window:

![Optional Component Discovery Details](./images/ui-user-guide/optional-component-details.png)

This page shows all the links as described above, but also shows the dependencies that the component has and a link for the install instructions which takes you to [this documentation page][] 
 

[artifact server]: https://development.adaptris.net/nexus/content/groups/
[this documentation page]: https://development.adaptris.net/docs/Interlok/adapter-optional-components.html#how-to-install
---
layout: essay
type: essay
title: "Baking Code with Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2025-12-03
published: true
labels:
  - Design Patterns
---

<img width="300px" class="rounded float-start pe-4" src="../img/cookiesmm.jpg">

Design Patterns and Baking
Baking is a very similar concept to the idea of design patterns. When baking, you need to first decide how you are going to bake the food you wish to bake. Say you are baking a cake, you can accomplish this in many different ways, but to stick to your desired cake, you need to choose specific tools to create it. In the same way, when coding a project, you need to design and select specific design patterns to hold your code together. 

In addition to this, you can also use different tools in different parts of the baking process, like using a whisk to stir and a cake pan to bake. Similarly, when coding, you might use a factory method pattern to create objects, then structure them with a structural design pattern like a composite tree-like pattern. Just like baking has structural tools (pots and pans), creation tools (oven, stove), and tools related to food properties (blending vs. chopping), design patterns have structural, creational, and behavioral patterns. These patterns work together to structure objects, create objects, and handle objects and their behavior.

Design Pattern Benefits
Using design patterns is beneficial in sorting out how ideas will be implemented. Knowing that you plan to create an object using a specific pattern can structure the code before you even start typing. 

Using a project I’m currently working on with a team as an example, Run & Route Hub uses many different design patterns throughout all parts of the code. Firstly, to create objects, we use creational patterns like an abstract factory pattern. We use similar object data types on each page of our site, without a concrete set of information. This allows us to shape each page to our liking before congregating information in our database. We do this using a behavioral pattern when users submit data. They select the pathway for a running route, which our project then adapts to include all other information we use, like distance across the route in both miles and kilometers, and later providing reviews to it. In terms of structural patterns, we use a decorator style structure which flows well with our other methods. This decorator allows us to dynamically add new features to our route object, like reviews, without changing the object entirely.

By sorting our project using these design patterns, it becomes much easier to direct all parts of the project to the desired result. 

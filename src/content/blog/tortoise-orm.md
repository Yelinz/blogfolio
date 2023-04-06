---
title: "Trying out tortoise-orm"
description: "Trying out tortoise-orm with FastAPI"
pubDate: "2023-04-03"
---

TLDR: [tortoise-orm](https://tortoise.github.io/) in my opinion is not ready for production apps.

Why did I chose tortoise-orm with FastAPI?
In my day to day job I work with django and django-rest-framework and create nice APIs with them.
But for my own projects at night I wanted to try something more modern and cutting edge.
FastAPI was an easy choice as it is an established modern framework.
Choosing an accompanying ORM was not as easy. The recommended and most widespread one is probably SQLAlchemy.
But it did not seem to be a fitting choice for something with Fast in its name, so I wanted to try to use an async focused ORM aswell.
After researching the different options such as Pony, peewee, SQLAlchemy I came to the conclusion (with a little help of the [benchmarking](https://github.com/tortoise/orm-benchmarks) done by tortoise) that it would be a good option.
But after using it a while I came over a few problems with it. My views might be skewed as I could not use it all too much because I ran into a lot of problem just after defining my models.

Cool things
- async
- typed models
- nice FastAPI integration

My gripes with tortoise-orm
- [Creating and using relationships](https://github.com/tortoise/tortoise-orm/issues/709)
- [Cyclic relationships](https://github.com/tortoise/tortoise-orm/issues/506)
- 2 types of model (pydantic, tortoise-orm)

It may seem very negative as there are more gripes than compliments.
But it is a cool project which explores the idea of an async ORM in python which the others have not done.
Try it out for small and simple projects, but for larger projects you might be better served with one of the established ones.

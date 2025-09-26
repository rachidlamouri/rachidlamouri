# Rachid Lamouri

([/rəʃiːd/](https://ipa-reader.com/?text=r%C9%99%CA%83i%CB%90d&voice=Kendra)) he/him

## About Me

I started out with Android development in Java, but quickly switched to JavaScript development, and now TypeScript development, for its portability and high level runtime model. My experience is mainly full stack TypeScript development.
My immediate goal is to streamline my TypeScript development process, and build platform-agnostic patterns that I can port to other languages
when I'm ready to start learning them.

My other hobbies include 3D printing, and playing video games.

## Current Projects

### Testing Platform ([testing-platform](https://github.com/rachidlamouri/testing-platform))

I'm building a testing framework for fun, and I'm being super extra about it.

## Back Burner Projects

I'm focusing on the above [testing-platform](#testing-platform-testing-platform) project to try to fix and/or understand the pain points that I have with existing JavaScript testing frameworks. Therefore, I've had to set aside some projects that I'm really passionate about.

### \[redacted\] (🦒)

This one is private. It has been one of my core projects since I started learning JavaScript and a solid chunk of my development experience comes from iterating on this project. I started working on [testing-platform](#testing-platform-testing-platform) inside of this project, and I'm in the process of porting [testing-platform](#testing-platform-testing-platform) into its own repository.

### 3D Printing ([3d-printing](https://github.com/rachidlamouri/3d-printing))

I was experimenting with using version control to save designs for 3D models. The software I was using was discontinued so I switched to [JSCAD](https://github.com/jscad/OpenJSCAD.org) where you can build 3D models with JavaScript. I may archive this project depending on the direction of the next project:

### 3D modeling ([3d-modeling](https://github.com/rachidlamouri/3d-modeling))

This is one of several projects that I used to learn TypeScript. This project defines a dimension engine, which allows specifying a 3D model as a system of equations of its dimensions. Using the dimension engine, you can create higher order 3D model definitions whereby the model definition can assume that it has access to all dimensions. When you instantiate a model, you can pass any subset of dimensions and the dimension engine will check to see if all equations are solveable and reconcilable. Model definitions output a tree datastructure which can be passed to an adapter to take advantage of existing 3D modeling libraries such as JSCAD to produce STLs or other standard modeling files.

## Guiding Principles

### Know Your Goals

I program because designing and building things is fun. Despite the fact that being rich would make life easier, my personal projects are not made in the pursuit of making a profit. Granted, I'm not going to let someone else get rich off of my work 😄. I also have limited free time, and I have plenty of personal goals, so I try to be wary of expanding the scope of my projects to accomodate the needs of the few (unless "the few" is me). Every developer, team, organization, and company has different goals which affects the tools they use and the decisions they make.

### Be Agile

The best way to future proof is to not future proof. Focus on the requirements that you have today, but create a process that allows you quickly refactor existing work to accomodate your unknown future goals.

### Remember the Path

I really enjoy helping people learn, and one of the biggest things that I've learned about teaching is to try and not forget the path I took to obtain the knowledge that I have today. Being able to identify misconceptions, having empathy for why something isn't clicking, and being able to share your mental model are all key skills for working with others. Also, don't laugh at people that are learning: Yes, you made the same misconceptions or understand how easy it is to make certain misconceptions, but they won't have your perspective, and it will feel like you are laughing **at** them.

When you're standing on top of a mountain, don't be so focused on the clear view ahead that you forget the difficulty of the journey, or you don't go back to clear an easier path for those that follow. Granted, this might be a poor analogy because it's not like you have to go back down the mountain once you get to the top.

### Set Constraints

There are always hidden constraints that don't affect developer's until they affect their customers. For example, information can't travel faster than the speed of light, Excel sheets aren't meant to be used as large scale relational databases (or maybe they are, who am I to judge?), and although the number is large, there is a finite limit to how much concurrent traffic a website will receive. In my case, I'm my biggest customer, and I have found that setting constraints up front allows me to narrow the scope of projects and not be surprised by unforseen edge cases when my project starts to scale.

Side note, I use this principle to limit my edge cases, so I don't focus on edge cases that I'm not sure about. For example, I don't have to handle multiple inputs if I don't allow multiple inputs :finger_guns:.

### Concepts are More Important than Words

The way we refer to things is constantly in flux, and should be decoupled from the core concepts that we're trying to represent. That is, we should be able to change the words we use to reflect an ever evolving understanding of the things we're trying to communicate. Furthermore, words themselves can have semantics and connotations that can change over time, and we shouldn't get caught up in what words used to mean to justify remaining ignorant of what they mean today. The more people understand that, the more we can focus on communicating and understanding one another instead of nit-picking how we say things. In fact, we should encourage having multiple ways to say things so that we can have more puns!

### Use Discoverable and Enforceable Conventions

Conventions can improve developer productivity, but they can also hinder the developer experience with a wall of magic. Use tooling and documentation that is either linked to, derived from, or the specification for the tooling that drive your conventions. Don't waste time trying to check something the computer can check for you.

### There Isn't Always a Best Way to Skin a Cat

Every decision in a specific context will have pros and cons. Not every situation will have a set of decisions that are **all** objectively good or bad. This is especially true for software development where your requirements can affect the decisions you make, and your requirements can change at a moments notice. Just [know your current goals](#know-your-goals) and [be agile](#be-agile).

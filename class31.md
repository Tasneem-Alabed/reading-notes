# Razor Pages

## Introduction to Razor Pages in ASP.NET Core
Razor Pages can make coding page-focused scenarios easier and more productive than using controllers and views.This document provides an introduction to Razor Pages. It's not a step by step tutorial. If you find some of the sections too advanced, see Get started with Razor Pages. For an overview of ASP.NET Core, see the Introduction to ASP.NET Core.

With ASP.NET Core 2 we get another way of building web applications. It’s one of those new things that is actually forgotten old thing and it is called Razor Pages. Are we going back to WebMatrix days? This blog post is short introduction to Razor Pages in ASP.NET Core 2.


One of new features of ASP.NET Core 2.0 is support for Razor Pages. Yes, those same pages that came times ago with WebMatrix. Today Razor Pages is subset of MVC on ASP.NET Core. Yes, support for Razor Pages comes with ASP.NET Core MVC meaning that Razor Pages application is technically MVC application. Also Razor Pages have same features as MVC views.

Application structure is similar to MVC but there are no folders for controllers and views. The folder called Pages contains all Razor views that in this context are called “pages”. These pages are like regular MVC views but they also contain code that for MVC is held in controller classes. I will cover this part of Razor Pages later.

Program and Startup classes are exactly the same as for MVC applications. Not just by name but also by code. As said before, Razor Pages are supported by MVC and they are part of it.

Separating logic from presentation is also possible here. We can create code-behind files for pages and name these as PageName.cshtml.cs. Class that code-behind file contains is called “page model” now. Note the arrows before About, Contacts, Error and Index pages on Solution Explorer screenshot. These views have code-behind files.

As I show later then by architecture Razor Pages are following their own pattern I would call View-ViewModel. It is like mix of MVC and MVVM with some missing genes by both parents.


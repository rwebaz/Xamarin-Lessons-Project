---
title: Xamarin Mac
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
description: Place the intro paragraph ie.) the 'synopsis' here ...
repo: Xamarin-Lessons-Project 
ver_date: 11-17-19
navigation_weight: 8
categories: template
---
{% include toc.md %}

## X-code

If you are an **Apple Mac Book Pro** owner - developer, you already have a copy of Apple **X-code** on your machine.

We will be using specifically, the **X-code** *Interface Builder* when interfacing with **Visual Studio for Mac**.

## Begin

There are a total of seven (7) files to consider at the onset of a basic **X-code** - **Xamarin** app.

## Four C Sharp

The first four (4) files are C Sharp `#` language files (.cs)

## Main dot cs

As in all C Sharp `#` language programs, the *Main dot cs* file houses the intro method that kicks off the program, as follows:

```liquid
{% raw %}
static void Main(string[] args)
{% endraw %}
```

Here, the method creates an instance of the Main class.

## The Main Class

The `MainClass` describes a Xamarin Mac app in object oriented detail and is a *blueprint* for the declaration and assignment of both assets and methods in an instance of the class.

## Imported Libraries

The program recognizes the `AppKit` declared as a library of functionality to be used and imported into the application via the `using` statement at the top of the program.

## Name Spaces

The `namespace` is derived from the original name given the app, in this case `hello-mac`.

After importing the library of functionality `AppKit` into the program via the `using` statement ...

And, then declaring the `namespace` of `hellomac` ...

The program next creates an instance of the `MainClass`, as follows:

```liquid
{% raw %}
using AppKit;

namespace hellomac
{
    static class MainClass
    {
        static void Main(string[] args)
        {
            NSApplication.Init();
            NSApplication.Main(args);
        }
    }
}

{% endraw %}
```

{% include patreon-link.md %}

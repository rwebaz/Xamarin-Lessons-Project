---
title: Xamarin Mac
layout: default
navigation_weight: 9
---
# Xamarin Mac

Apple's **X-code** and Microsoft's **Xamarin** platform combine harmoniously to produce native apps in *Mac Os High Sierra* via **Visual Studio for Mac**.

{% include toc-flammarion.md %}

## Shared Platforms

In addition to the formation of native apps in *Mac Os High Sierra*, the Apple **X-code** - Microsoft **Xamarin** combo can also produce mobile apps simultaneously native for both the **Mac Apple Store** (iOs) *and* the **Google Play Store** (android).

To begin development, download and install a free copy of [Visual Studio for Mac](https://mminail.github.io){:title="Click to Visit the Download Page of Visual Studio for Mac"}{:target="_blank"} from the *Xamarin Mac Development Team*.

If you are an **Apple Mac Book Pro** owner - developer, you already have a copy of Apple **X-code** on your machine.

We will be using specifically, the **X-code** *Interface Builder* when interfacing with **Visual Studio for Mac**.

## Begin

There are a total of seven (7) files to consider at the onset of a basic **X-code** - **Xamarin** app.

### Four C Sharp

The first four (4) files are C Sharp `#` language files (.cs)

#### Main dot cs

As in all C Sharp `#` language programs, the *Main dot cs* file houses the intro method that kicks off the program, as follows:

```liquid
{% raw %}
static void Main(string[] args)
{% endraw %}
```

Here, the method creates an instance of the Main class.

##### The Main Class

The `MainClass` describes a Xamarin Mac app in object oriented detail and is a *blueprint* for the declaration and assignment of both assets and methods in an instance of the class.

##### Imported Libraries

The program recognizes the `AppKit` declared as a library of functionality to be used and imported into the application via the `using` statement at the top of the program.

##### Name Spaces

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

#### App Delegate dot cs

More to come ...

#### View Controller dot cs

More to come ...

#### View Controller dot designer dot cs

More to come ...

### Main Storyboard

- Main dot storyboard

More to come ...

### Two Plist

- Info dot plist

More to come ...

- Entitlements dot plist

More to come ...

## Last Subtitle

More to come ...

```liquid
{% raw %}
Place code here
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Hello Mac: Getting Started](https://mminail.github.io){:title="Click to Visit the 'Hello Mac: Getting Started' Page of the Xamarin Mac Development Team"}{:target="_blank"} page of the *Xamarin Mac Development Team*. Published by © 2017 [Microsoft.com](https://mminail.github.io/) {:title="Click to Visit the Home Page of Microsoft dot com"}{:target="_blank"}.

- The [Project Source Links](https://mminail.github.io/Xamarin/Source-Xamarin-Links.htm){:title="Click to Visit the Source Links page of the Xamarin Lessons Project at GitHub pages"}{:target="_blank"} page of the Xamarin Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

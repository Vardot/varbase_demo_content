[![Varbase](https://raw.githubusercontent.com/Vardot/varbase/11.0.x/images/varbase-logo.png)](https://www.drupal.org/project/varbase)

# Varbase Demo Content
[![pipeline status](https://git.drupalcode.org/project/varbase_demo_content/badges/1.0.x/pipeline.svg)](https://git.drupalcode.org/project/varbase_demo_content/-/pipelines)
[![Varbase Demo Content](https://img.shields.io/badge/Varbase%20Demo%20Content-1.0.0--beta1-0d6efc?labelColor=001d38&style=flat-square)](https://git.drupalcode.org/project/varbase_demo_content/-/pipelines?ref=1.0.0-beta1)
[![Automated Functional Testing](https://git.drupalcode.org/project/varbase_project/badges/11.0.x/pipeline.svg)](https://git.drupalcode.org/project/varbase_project/-/pipelines)

Provides demo content for Varbase sites including a pre-configured sample pages.

Gives new Varbase installations a working starting point that demonstrates key features and can be customized or replaced.

If you're evaluating Varbase, installing demo content will help you get
 an idea of how Varbase works, and what features are included.

> Installing demo content gives you a taste of what Varbase offers and
> its key features. It's a handy way to explore Varbase's functionality and see it in action.

Following with the [Varbase Design System](https://www.figma.com/file/ARfcW5i5Euid8Yv1QFhgSq/VB---Design-System)
Following with the [Varbase Demo Website](https://www.figma.com/file/PZTbT1PCVJPHkUUfkwRi2S/VB---Demo-Website)

💡 Live [Varbase Demo Example](https://demo.varbase.vardot.com)
💡 Live [Varbase Storybook](https://storybook.demo.varbase.vardot.com)

> **NOTICE**
> Apply the Varbase Demo Content recipe only for testing or demo purposes
>
> **NOT** in production sites, only **development**, **testing**, and **demoing** Varbase.

## Usage

This is a Drupal recipe that provides demo content for Varbase. Apply it using:

```bash
cd web
php core/scripts/drupal recipe ../recipes/varbase_demo_content
```

Or via Drush:

```bash
cd web
drush recipe ../recipes/varbase_demo_content
```

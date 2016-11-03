# Vanilla Starter for Enonic XP

This starter kit will set up the basics for your new Enonic project.

Once initiated, you'll have the bare minimum needed to create a new Enonic
application or library. You'll have all the folders set up, and can get
straight to creating what you're creating.

## Usage

To get started, use the `toolbox` script to initiate your project:

```bash
~ $ mkdir new-project
~ $ cd new-project
~/new-project $ [$XP_INSTALL]/toolbox/toolbox.sh init-project -n com.example.name -r starter-vanilla
```

## Building your project

For best results, edit the gradle.properties file and check that the 
xpVersion matches your XP version. 

Build your project with ``./gradlew build``
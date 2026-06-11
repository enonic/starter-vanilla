# Vanilla Starter for Enonic XP

This starter kit will set up an empty shell for your new Enonic app.

Once initiated, you'll have the bare minimum needed to create a new Enonic
application. You'll have all the folders set up, and can get
straight to creating what you're creating.

## Enonic CLI

You first need to install Enonic CLI:

```bash
npm install -g enonic-cli
```

## Building

### XP 8

Run the following commands to create and deploy it:

```bash
~ $ enonic project create -r starter-vanilla myapp

~ $ cd myapp

~/myapp $ enonic project deploy
```

Your brand new app should now be up and running on http://localhost:8080

### XP 7

Run the following commands to create and deploy it:

```bash
~ $ enonic project create -r starter-vanilla -b xp7 myapp

~ $ cd myapp

~/myapp $ enonic project deploy
```

Your brand new app should now be up and running on http://localhost:8080

## Development

After you have created the project, you can also run it in development mode.

In this mode all changes to project files will be automatically compiled and deployed to XP:

```bash
~/myapp $ enonic dev
```

Your brand new app should now be up and running on http://localhost:8080.

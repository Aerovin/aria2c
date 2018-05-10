# aria2c

A Heroku buildpack for aria2c that always downloads the latest [aria2 static build](https://github.com/q3aql/aria2-static-builds).
Unlike other build packs, I never compile anything.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/Aerovin/aria2c.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/Aerovin/aria2c.git
```

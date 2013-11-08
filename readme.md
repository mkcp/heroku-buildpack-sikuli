# Heroku Buildpack: Sikuli

Use this buildpack if you need to add Sikuli dependencies to a Heroku app.
Adds `sikuli-script.jar` and `libs` to `app`/vendor/sikuli and links to `SIKULI_HOME` in your environment.


## Usage

Directly specify this buildpack for your heroku app

```bash
$ heroku build my_app -b https://github.com/mkcp/heroku-buildpack-sikuli
```

Or add this to your .buildpacks file

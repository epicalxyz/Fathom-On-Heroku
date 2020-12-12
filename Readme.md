# Fathom Lite. Simple, privacy-focused website analytics. Built with Golang & Preact

**What is Fathom:** https://github.com/epicalxyz/fathom

**NOTE:** You will reach the limits on the database tables of the free service faster or slower depending on how many visitors you have so you might want to upgrade to a paid plan to raise this limits.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/rubensudos/fathom-heroku)

- check that everything is working

```bash
heroku run bin/fathom --version
```

- add the first user

```bash
heroku run bin/fathom user add --email="email" --password="password"
```

- open the browser to login and add your first website

```bash
heroku open
```

- ENJOY :)

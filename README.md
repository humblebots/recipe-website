# Robyn's Recipe Website

## Develop

Install the dependencies with [Bundler](http://bundler.io/):

```bash
$ bundle install
```

Run `jekyll` commands through Bundler to ensure you're using the right versions:

```bash
$ bundle exec jekyll serve
```

## Deployment

To generate the complete static site locally in the \_site folder, run:

```bash
$ bundle exec jekyll build
```

To deploy to production and push to all remotes, run:

```bash
$ ./deploy.sh
```

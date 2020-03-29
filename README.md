# Learn to use Jekyll to publish static web sites
[Github Pages](https://dmccreary.github.io/learn-jekyll)
## Basics
## Navigation
## Search

## References

[GitHub features about pages](https://guides.github.com/features/pages)
[GitHub About Pages and Jekyll](https://help.github.com/en/github/working-with-github-pages/about-github-pages-and-jekyll)

Here are my versions:
jekyll 4.0.0
gem 3.0.3
ruby 2.6.3p62 (2019-04-16 revision 67580) [universal.x86_64-darwin19]

All the bundle and jekyll with version numbers failed

```bundle exec jekyll 3.8.5 new .
jekyll 4.0.0 new .
Could not locate Gemfile or .bundle/ directory
```

This worked:
```jekyll new . --force```
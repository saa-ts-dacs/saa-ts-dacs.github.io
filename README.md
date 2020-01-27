# saa-ts-dacs.github.io
This is the repository for the website displaying the latest version of DACS, available at https://saa-ts-dacs.github.io. This repo includes the Jekyll config, layouts, css, and other files required for building the website.

You may instead be looking for the repository that holds the content of DACS, available here: https://github.com/saa-ts-dacs/dacs.



## Getting Started

This will show you how to clone and build the site locally.

#### Clone the repo

Use the `--recurse-submodules` option to include the DACS repo.

```
git clone --recurse-submodules https://github.com/saa-ts-dacs/saa-ts-dacs.github.io
cd saa-ts-dacs.github.io
```

#### Prerequisites

Github Pages automatically builds the site from the content in the DACS repo as well as the Jekyll config, layouts and assets in this repo. So, while you don't need anything except git to make changes to the site, you will need Jekyll to build and test locally.

* git
* ruby
* Jekyll

##### macOS/Linux

For macOS/Linux, you should consider using [rvm](https://rvm.io/rvm/install) to manage multiple projects, but this is the easiest method:

```
gem install jekyll, bundler
bundle install
```

##### Windows

It is more difficult to setup Jekyll on Windows. The [Jekyll docs](https://jekyllrb.com/docs/installation/windows/) detail how to install Jekyll with both RubyInstaller and the Windows Subsystem for Linux.

#### Building the site

Once Jekyll is installed, all you have to do is 

```
jekyll serve
```

and navigate to http://localhost:4000



## Deployment

Once changes are made, all you have to do is commit the changes to the master branch to update https://saa-ts-dacs.github.io.

```
git add .
git commit -m "I changed these things!"
git push origin master
```



## Contributing

The site is maintained by the [Technical Subcommittee on Describing Archives: A Content Standard (DACS)](https://www2.archivists.org/groups/technical-subcommittee-on-describing-archives-a-content-standard-dacs), but pull requests to improve the site are welcome.


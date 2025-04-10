# Hugo Cookbook

![logo](/static/favicons/favicon-57x57.png)

Simple and minimal digital cookbook theme built for [Hugo](https://gohugo.io).

This template is here to help people get started with a basic digital cookbook.  
This was created to build an environmet friendly digital cookbook for the project "Klimaschutz einfach machen" (excuse the german).


## Getting Started

### Install with hugo mod
1. Fork the repository, if you want to use it as a base for your own project.
   1. This is not required, but it is a good idea to have your own copy of the theme.
   2. You can also just clone the repo if you want to use it as a base for your own project.
2. Install Go 1.18 or newer
   1. `go version` will help you validate if you have Go installed.
2. Run `hugo mod init github.com/username/reponame`
   1. Go uses git as its package manager so this command creates a `go.mod` file in your project and defines the project name.
   2. Replace `username` with your username
   3. Replace `reponame` with your projects name. 
3. Open your config file `config.yaml || config.toml` and update the theme line to show `theme: ["hugo-tailwind-cookbook"]"`

Next time you build your project, Go/hugo will go download the repo for this theme and add it to your project at runtime!

## Features

- [x] Tags
- [x] Categories
- [x] Meta Tags
- [x] Favicon
- [x] Hugo Module Support
- [ ] Pagination (to come)
- [ ] Recipe Search (to come)
- [x] Card Layout
- [x] Dynamic Navbar

## Contribute

Please fork this repo and send your PR over if you have thoughts on how to improve the template!

## Remarks

If you find the phrase tailfin anywhere in the code, I was thinking on cycling instead of programming. 
See [tailfin](https://tailfin.com/) for more information on that cycling project.
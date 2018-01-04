# vmhandbook

This repository contains the user manual for CeR research virtual machines, which is a Jekyll based static website. It can be hosted on either Github pages or any http hosts.

## I. Setting up this site locally with Jekyll

### 1. Install ruby

On macOS, do **NOT** use the build-in ruby. Install via `brew` to avoid permission errors.

### 2. Install Bundler

```bash
gem install bundler
```

### 3. Clone this repository

### 4. Install Jekyll and other dependencies

```bash
bundle install
```

### 5. Build your local Jekyll site

```bash
bundle exec jekyll serve
```

## II. Content editing

### 1. Directory structures

```bash
├── Gemfile         # Ruby dependencies
├── Gemfile.lock    # Generated by bundler
├── README.md       # This file
├── _config.yml     # Jekyll configurations
├── _doclinux       # A Jekyll collection for Linux VM FAQs
├── _docwindows     # A Jekyll collection for Windows VM FAQs
├── _includes       # Overwritten parts of the template 
├── _layouts        # Overwritten layouts of the template
├── _site           # Jekyll outputs
├── assets          # Static files like images, JS/CSS files.
└── index.md        # Home page
```


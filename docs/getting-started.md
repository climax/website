---
# Page settings
layout: documentation
keywords:
comments: false

# Hero section
title: Getting Started
description: Write and run your first Climax app.

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    # prev:
    #     content: Previous page
    #     url: '#'
    next:
        content: Build Your App
        url: 'docs/build'
---

# Writing Your First Climax App

## Introduction

Let's try to write a CLI client able to:
- Check your Twitter notifications
- Send a new Tweet on your behalf

In order to understand the full process, we will walk you through 3 steps:
1. Write and run the Climax application
2. Build a binary
3. Automate the release via Github

## Installation

The easiest way to generate a Climax application is to install the [Climax CLI](https://github.com/climax/core):

```
npm install -g @climax/cli
climax new
```

## Generate A New Climax App

Now let's generate our application

```
climax new twitter-cli
```

You can replace `twitter-cli`

### As a dependency

# Writing Your First Climax App

Climax is based upon

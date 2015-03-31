---
tags: kids, setup, rvm, homebrew
type: environment setup
language: bash
---

###1. Install RSpec
Enter `gem install rspec` in your terminal.

###2. Install The Learn Gem
This gem isn't open-sourced, so we won't be downloading it from rubygems.org, which is where most gems are hosted. Before we download it, we will need to specify where it's coming from, which is a private server at Flatiron School. Type this into your command line:

`gem sources -a http://flatiron:33west26@gems.flatironschool.com/`

Next, download the gem:

`gem install learn-co`

The Learn gem will help track your progress on labs.


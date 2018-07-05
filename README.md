# Neo-FrameWork

## Overview
Imagine a framework that doesn't care about your core programming language! In the end, it doesn't matter if your backend code is PHP, C# or Java, you are going to render HTML, CSS and JavaScript to the browser. And that's what this framework is going to do. Code in any language and deploy it to the browser!

## Features
Ability to use any programing language
Allowing the usage of any framework

## Structure
  client - contains all files that are visible on the browser
         - Here front-end developer will work on these files
  server - contains all server-side files/code that is not visible on the browser
         - here a programming language is defined and the database engine is selected
  private - this folder contains all the vendor packages from composer and all node_modules packages
          - No changes are made to these files, these files are maintained by 3rd-parties
  public - this folder contains the entry point for the application, and the root of the site
          - all assets are available here after being deployed as well as web engine accessible files
  build - this folder contains all the settings of the application, all tasks and configurations
  storage - this folder contains all data that's store in the file system including but not limited to cache            files, assests, etc.
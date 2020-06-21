---
title: Command lines flutter usually use
date: "2020-06-22T22:40:32.169Z"
template: "post"
draft: false
slug: "command-line-flutter"
category: "Flutter"
tags:
  - "Flutter"
  - "Command line"
description: "Command lines flutter usually use."
socialImage: "/media/42-line-bible.jpg"
---
# ios

- start simulator

```bash
	open -a simulator
```

- install set up cocoapods run first

```bash
sudo gem install cocoapods
pod setup
```

- open xcode run project, choose device before run

```bash
open ios/Runer.xcworkspace
```

# flutter

- init project

```bash
	flutter create new_project
```

- run project, require simulator

```bash
cd new_project
flutter run
```
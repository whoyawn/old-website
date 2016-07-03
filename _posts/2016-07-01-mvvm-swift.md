---
layout: post
title:  Use case for ViewModels inside a tableView
date:   2016-06-28 18:41:53 -0700
categories: iOS
---

As long as I follow the rules of MVVM, it probably doesn't matter if I have an array
of view models or if it's just one view model per controller instantiated with the array
of data inside the view model.

each cell having its own view model

the view is ignorant of the controller
the controller is ignorant of the model
the model is ignorant of the view model
the view model owns the model
the controller owns the view
the controller owns the view model

http://stackoverflow.com/questions/31059693/how-to-define-initializers-in-a-protocol-extension
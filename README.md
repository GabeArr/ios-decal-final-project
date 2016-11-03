# Steal
## Authors
...Gabriel Arreola
## Purpose
...Steal is an app for artists and designers that allows users to extract color schemes from images taken with their phone’s camera.
## Features
...Ability to take and store pictures with inspiring color themes
...Ability to extract and store the hex color codes from stored pictures
...Ability to create color schemes without a picture
...Ability to apply color schemes to default templates (allows users to pick dominant/minor colors)
## Control Flow
...Users are initially shown a list view of photos they have taken along with the corresponding color scheme underneath each photo. Aside from scrolling through these photos, a utilize one of three controls to navigate to the next page: select a photo, swipe right, or swipe left.
...Selecting (touching) a photo, will take a user to screen with an enlarged version of the photograph, along with the color theme associated with it. Additionally, a user will be able to apply to this color scheme to a designated template, to preview the colors in different ways. The user will also be able to store notes about how they would like to use this color scheme for future projects.
...Swiping left will result in the camera screen. This screen will have one button for taking a picture. Once a picture is taken, a user can either “X” (delete) their picture and take another, or save their photo. Saving a photo will navigate the user to a new screen which displays the photo along with the colors. A user can modify the colors and save the theme. At which point they will be navigated back to the home screen.
...Swiping right will navigate a user to a screen with a color wheel and input box. A user can either pick a color from the color wheel or input a hex color code. Either of these options will add that color to a new color scheme, which a user can preview again by using templates (the template would be shown by scrolling down.) The user can then save the color scheme which navigates the user back to the home screen.
## Implementation
### Model
...Steal.swift
### View
...HomepageLIstTableView
...CameraView (Not sure how this would work)
...ColorAdjustView
...PhotoView
...ColorSchemeCreateView
### Controller
...HomepageListTableViewController
...CameraViewController
...ColorAdjustViewController
...PhotoViewController
...ColorSchemeCreateController



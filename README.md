# Lithodomos VR Unity Coding Challenge

> Welcome to the Lithodomos VR Unity Coding Challenge!

## Overview

The purpose of this challenge is to assess your **skills and approach to
composing a simple app** given a mockup and a specification.

The challenge is expected to take about 2-3 hours.

## Challenge

Using the provided mockup and specification as reference, you'll be required to
create a Unity application targetting mobile devices, either iOS or Android.

**Although it's preferred all requirements are met, we'd rather an incomplete
yet well written and functional application, rather than a complete yet poorly
implemented one.**

Please include a `README` with any setup instructions or other documentation you
created.

Additionally, please answer the following questions and include them in your
`README`:

- How did you decide on the approach you took?
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

## Details

You are tasked to create a 360 image viewer, capable of infinitely cycling
through a sequence of images. It will consist of a 360 images that can be viewed
by adjusting the device's orientation, and a simple 2D UI overlay containing
buttons that allow the user to switch to the next and previous images.

All of the images & assets you'll need can be found in the
[resources folder](./resources) found in this repository, with a preview of the
mockup found below.

## Specification

### Functional

- [ ] When a user moves the device, the camera should follow it's orientation
      accordingly to allow for viewing the entirety of the image
- [ ] When a user taps the "previous" button when viewing the first image in the
      sequence, they should be taken to the final image in the sequence
- [ ] When a user taps the "next" button when viewing the last image in the
      sequence, they should be taken to the first image in the sequence
- [ ] When transitioning between 360 images, the screen should fade to black,
      then from black to the next or previous image
- [ ] When a user taps "previous" or "next" while the images are mid-transition,
      the current transition should be interupted & reversed as necessary, as
      opposed to completing & starting a new transition

### Technical

- [ ] Minimize the amount of memory consumed by the application by loading &
      unloading the 360 images from disk to memory as they switched between
- [ ] Keep the last 2 images used in memory to minimize loading time when
      swapping to the previous image

## Mockup

![Code challenge app mockup][mockup]

<!-- resources: images -->

[mockup]: ./resources/mockup.jpg

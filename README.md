# Slender

A very opinionated, probably too sparse Svelte component library.

## About

This library is created and maintained by James Williams (JU12000).

I can not guarantee that documentation will be up to date or that I will be able to quickly and efficiently respond to and resolve issues as this library is intended for personal use on my projects. However, anyone is more that welcome to use it per the MIT license.

The code lives on my [Github](https://github.com/JU12000/Slender). For examples of all the components you should `git clone` the project and then `npm run dev`. The dev server contains a playground which showcases the components.

Any images found in the staging site are courtesy of [Placeholder](https://placeholder.com/)

## Installation

Install as with any other NPM package: `npm install @ju12000/slender`

You should also feel free to include this as a git submodule on any project.

## Components

Detailed below is a list of all the components currently in the library and their corresponding APIs.

---

## Hero

A full width banner, the left side is a slot, the right side is an image.

| Property     |      Values      |              Default               |                                            Usage                                             |
| :----------- | :--------------: | :--------------------------------: | :------------------------------------------------------------------------------------------: |
| imageAlt     |      string      |             'No Image'             |     Alt Text for the image, should always be passed when there is an imageSource passed.     |
| imageSource  |      string      | 'https://via.placeholder.com/1080' |                             The source for the image to be used.                             |
| size         | 'sm', 'md', 'lg' |                'md'                |                                The height of the hero in vh.                                 |
| default slot |                  |                                    | This slot controls the left side of the hero. It is contained in a div with a min-width: 50% |

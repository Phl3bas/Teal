# TealUI

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

<center>
<img src="./assets/logo-blacktext.svg" alt="teal logo"/>
</center>
<center>A Beautifully modular Design System</center>
<br>
 <hr>
<br>
<center><h2>What is TealUI?</h2></center>

TealUI is a modular design system / css framework / web component library where the aim is to provide a multi tierd design system, where developers can "buy-in" to as much of the design system as they like, without feeling like alot of the design system/framework is going to waste.

<center><h2>What packages are available?</h2></center>

TealUI is broken down into four distinct packages.

### @teal-ui/tokens

- A set of design tokens declared at root level

### @teal-ui/elements

- A css normalisation and opinionated classless css framework

### @teal-ui/css

- A utility based css framework / buildtool

### @teal-ui/components

- A web component library which makes use of the previous packages

<br>
<hr>
<br>

<center><h2>Overviews</h2></center>

## @teal-ui/tokens

tokens provides the user with a stylesheet containing a set of design tokens (css custom properties/css variables), these tokens then give the user a curated set of values to use in their project. This gives the developers more consistancy when reaching for values for

1. colors
2. scales
3. eases
4. radius'
5. box shadows

### 1. Colors

TealUI provides users with a curated spectrum of colors to chose from, instead of wildy picking colors from a color picker, we provide a 10 scale tonal scale for Red,Pink,Purple,Indigo,Blue,Teal,Green,Yellow and various greys (grey, warm-grey and cool-grey)

color tokens follow the format of:

`--tl-{color}-[number 000 - 900]`

eg

`--tl-teal-500`
`--tl-indigo-900`

color scales range from `000` to `900` scaling in 100's `000` being the lightest shade and `900` being the darkest

the one exception for this is black and white, which scales from `000` to `300`

### 2. Scales

## @teal-ui/elements

## @teal-ui/css

## @teal-ui/components

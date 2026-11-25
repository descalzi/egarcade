---
name: Grinstead Arcade
description: An arcade brawler set on East Grinstead's High Street
colors:
  bg: "#17172B"
  surface: "#22243D"
  border: "#393B57"
  border-strong: "#8889AA"
  fg: "#FFF1DD"
  fg-muted: "#C9BFD7"
  accent: "#FFD08A"
  on-accent: "#281C25"
typography:
  display:
    fontFamily: "Georgia, serif"
    fontWeight: 700
  body:
    fontFamily: "system-ui, sans-serif"
    fontSize: "1rem"
    lineHeight: 1.5
rounded:
  control: "6px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "32px"
---

# Design system

## Overview

Experience mode, using the media-first composition of Gallery in [the design library](https://github.com/descalzi/uiux#108-gallery). The homepage introduces EG Arcade through the High Street artwork and a single Play Now action. Its games list can grow as episodes ship. The play page is an Experience surface where the illustrated street gives way to live play.

## Colors

Indigo comes from the winter sky and amber from the lit shop windows. Amber signals play and focus. Mint marks a cleared encounter.

## Typography

The episode title uses a serif display treatment drawn from the shop signs. Controls and instructions use a readable system sans. Monospace is reserved for key labels and scores.

## Layout

The 16:9 canvas keeps its aspect ratio. The hero and play controls sit immediately below it. On coarse pointers, play opens a landscape stage with an analogue joystick and round Jump and Attack buttons over the game. Request native fullscreen and landscape lock first. Use a viewport-filling rotated stage if the browser cannot lock orientation. Pause and Exit fullscreen remain reachable. Spacing follows a 4 px grid.

## Elevation & Depth

Flat tonal surfaces and one hairline around the play area. The painted scene supplies the depth.

## Shapes

The canvas and frame have squared corners. Controls use a 6 px radius and a minimum height of 44 px.

## Components

Native hero radios, buttons and a live status line are reachable by keyboard. Focus is visible and the game pauses when the window loses focus. Reduced motion suppresses decorative button movement and rapid sprite flicker.

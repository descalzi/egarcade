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

The homepage and feature pages use the media-first composition of Gallery in [the design library](https://github.com/descalzi/uiux#108-gallery). The arcade name and short introduction lead into a full-width poster for the current game, followed by an illustrated preview of the next one. The Big Reveal feature page leads with its cover, a single Play action, and a gallery with illustrated boss art and labelled gameplay captures. The playable cabinet uses Experience mode and presents the arcade Play button and dedicated character portraits before play.

## Colors

Indigo comes from the winter sky and amber from the lit shop windows. Amber signals play and focus. Mint marks a cleared encounter.

## Typography

The episode title uses a serif display treatment drawn from the shop signs. Controls and instructions use a readable system sans. Monospace is reserved for key labels and scores.

## Layout

The 16:9 canvas keeps its aspect ratio. Game controls sit immediately below the active canvas on desktop. On coarse pointers, play opens a landscape stage with an analogue joystick and round Jump and Attack buttons over the game. Request native fullscreen and landscape lock first. Use a viewport-filling rotated stage if the browser cannot lock orientation. Pause and Exit fullscreen remain reachable. Spacing follows a 4 px grid.

## Elevation & Depth

Flat tonal surfaces and one hairline around the play area. The painted scene supplies the depth.

## Shapes

The canvas and frame have squared corners. Controls use a 6 px radius and a minimum height of 44 px.

## Components

Native character and action buttons and a live status line are reachable by keyboard. Focus is visible and the game pauses when the window loses focus. Reduced motion suppresses decorative button movement and rapid sprite flicker.

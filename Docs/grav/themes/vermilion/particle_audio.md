---
title: Vermilion: Audio Player Particle
description: Your Guide to Recreating Elements of the Vermilion Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/vermilion:Vermilion

---

## Introduction

![](assets/particle_audio1.jpg)

The **Audio Player** particle enables you quickly and easily add embedded audio content to your page.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#main-options)
    - [Item Options](#item-options)

## Configuration

### Main Options 

These options affect the main area of the particle, and not the individual items within.

![](assets/particle_audio2.jpg)

| Option               | Description                                                                                 |
| :-----               | :-----                                                                                      |
| Particle Name        | Enter the name you would like to assign to the particle. This only appears in the back end. |
| CSS Classes          | Sets any CSS class(es) you want to have apply to the particle's content.                    |
| Title                | Enter a title for the particle.                                                             |
| Now Playing Label    | Enter a label for the **Now Playing** section of the player.                                |
| Playlist Layout      | Choose whether or not you wish to have a scrollbar appear in the playlist.                  |
| Overflow Height      | Sets the overflow size (in pixels) for the playlist with the scrollbar.                     |
| SoundCloud Client ID | In order to play SoundCloud files, you will need to have a SoundCloud ID. Enter it here.    |

You can get a SoundCloud Client ID [here](http://soundcloud.com/you/apps/new).

### Item Options

These items make up the individual featured items in the particle.

![](assets/particle_audio3.jpg)

| Option            | Description                                                                                                       |
| :-----            | :-----                                                                                                            |
| Item Name         | Designates a name for the item that appears in the back end only.                                                 |
| Artist            | Enter an artist name that will be displayed with the item.                                                        |
| Track Title       | Enter a title for the track.                                                                                      |
| Album Cover       | Add cover art for the album that will be displayed along with the track in the particle.                          |
| Audio Source      | Enables you to select a SoundCloud track, external URL, or local audio file as the audio for the track.           |
| External URL      | If **External URL** is selected as the **Audio Source**, this is where you enter that URL.                        |
| Local Audio       | If **Local Audio** is selected as the **Audio Source**, this is where you enter the file's location or select it. |
| SoundCloud Track  | If **SoundCloud Track** is selected as the **Audio Source**, this is where you enter the track number.            |
| SoundCloud Artist | Enables or disables the display of the artist's SoundCloud info in the track listing.                             |

The particle has local support for any audio format that can be natively embedded using HTML5. This includes: mp3, ogg, and wav.

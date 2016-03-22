Ok Computer/Lorem Ipsum Generator
=====================

This is a fork of badcow's lorem ipsum generator [badcow/LoremIpsum](https://github.com/Badcow/LoremIpsum). Instead of generating the standard Lorem Ipsum text (e.g. "Lorem ipsum dolor sit amet...") with Latin words, it uses words from the lyrics of songs from Radiohead's album *Ok Computer*.


## Build Status
[![Build Status](https://travis-ci.org/Badcow/LoremIpsum.png)](https://travis-ci.org/Badcow/LoremIpsum)

## Basic Usage

    $generator = new Badcow\LoremIpsum\Generator();
    $paragraphs = $generator->getParagraphs(5);
    echo implode('<p>', $paragraphs);

## Installation

### Using composer

    //composer.json
    
    "require": {
        "badcow/lorem-ipsum": "dev-master"
    }

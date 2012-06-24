# Current state vs. (eve)nt sourcing

The slides and notes of my talk at the EuroClojure 2012.

## Summary

Most of today’s software uses the current state to store its application state. This is often regrettable since you lose a lot of valuable information and therefore a competitive advantage on the business side. However, the event sourcing pattern uses a different approach and stores all events that have led to the current state. At first sight it might seem more complicated than the classical current state based CRUD architecture, but you will see that almost everything gets easier with event sourcing.

This talk introduces you to the new open source framework eve, which combines the (eve)nt sourcing approach with the simplicity and power of the Clojure programming language. Furthermore, you will learn about the CQRS architectural pattern, which can be combined with event sourcing and helps you to build scalable systems.

## Usage

The slides for the presentation has been created with [Org-HTML-Slideshow](https://github.com/relevance/org-html-slideshow). After you have open the talk.html press t to see the slides. The notes contains almost the full speech of my talk.

## License

Copyright 2012 Maximilian Weber
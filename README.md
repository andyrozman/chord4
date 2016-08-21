# chord4
###fork of the sourceforge project [chord 4.0](https://sourceforge.net/projects/chord4/) 

This project is not really an attempt to revive chord4 and breathe new life into it. I'm starting this project because the ChordPro editor I do use [ChordSmith](http://www.statistics101.net/chordsmith/) utilizes chord4 as a viewer. It incorporates easily enough but the current version is a tad buggy and it's usage it a bit clunky since it has to open it's own editor before it opens the renderer.

My main goals are... 
- fix the bugs
- decouple the render engine from the editor and enable it to be invoked directly from ChordSmith

My plan is to try and maintain a working Chord4 instance as I go. However, since my main goal is to streamline the ChordSmith usage of the Chord4 render engine, if I get to a point where that streamlining is in conflict with a working Chord4 instance I'll stop working on this project and start another that just is a viewer (i.e. the rendering piece). I don't expect that to occur but I want to be up front with anyone that may follow along.

------

####TODO List

- My first step will be to create JUnit tests. This will allow me to learn the code and have confidence moving forward that I don't break anything.
..1 hook JUnit suite
..2 use [EclEmma](http://www.eclemma.org/) to ensure proper test coverage and add HTML report to project

- Then fix the bugs I find

- Then decouple the render engine from the editor

As I complete steps I'll ~~strikethrough them~~


------

##bugs

for the list of bugs I'm focusing on see the [issue tracker](https://github.com/DTownSMR/chord4/issues)
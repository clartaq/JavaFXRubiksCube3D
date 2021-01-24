# JavaFXRubiksCube3D

Using JavaFX to render a 3D object.

<img src="https://github.com/clartaq/JavaFXRubiksCube3D/blob/main/src/main/resources/2021_01_24_Screen_Shot.png" width="800" height="834" />

This is an example of how to setup and render a 3D object in JavaFX. This
particular example is an almost _verbatim_ version of the [gist](https://gist.github.com/jperedadnr/28534fcdce605b75382b)
created by [José Pereda](https://gist.github.com/jperedadnr) in response to
this StackOverflow [question](https://stackoverflow.com/questions/34001900/how-to-render-3d-graphics-properly).

Here the program is contained in an [IntelliJ IDEA](https://www.jetbrains.com/idea/) project.

(The few alterations I've made include changing the direction that the mouse drags the cube. The direction in this project just feels more intuitive to me. Also, the image file used as a color palette is included in the project and the name has been changed from "pallete.png" to "palette.png".)

## Build and Run

1. Clone this project from GitHub.
    - Change to a directory where you want to put the project.
        - `cd myProjectDir`
    - Clone it.
        - `git clone https://github.com/clartaq/JavaFXRubiksCube3D.git`
    - Change to the new project directory.
        - `cd JavaFXRubiksCube3D` 
2. Open it in IntelliJ IDEA.
    Either double-click on the `JavaFXRubiksCube3D.iml` file or open IntelliJ IDEA then open the project.
3. Run It
    Upon successfully building the project, a new window will open showing a view of a Rubik's Cube. You can rotate the cube by dragging with the mouse.

## Other Requirements

This was built and tested on a Mac only. It should work elsewhere, but I haven't tried it.

Java version 9 was used for the build. I've been out of the Java world for a few years, but this seems to be the last version that included JavaFX in the SDK. Rather than make folks go through the hassle of downloading a current version of the library, I decided to just use an old version of the SDK.

## License

Dr. Pereda's gist makes no mention of a license. I would not presume to add one.

Copyright © 2021 David D. Clark



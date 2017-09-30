# Canvas Calendar Tweak

### About
By default, the Canvas calendar doesn't look great. There are stylistic components that make it hard to tell which assignments have been turned in, and which are still due.

This tweak modifies the CSS with the help of the chrome extension Stylebot. After defining a style sheet, your Canvas calendar will no longer be frustratingly unhelpful, but will instead be the helpful tool that it should be!

#### Comparison: Before and After
![Canvas tweak comparison: Before and After](img/canvas-demo.gif)


### Issues and Fixes

1) It is difficult to distinguish between incomplete assignments and submitted assignments.

     Fixes:

    - Incomplete assignments appear in red

        - On hover they appear bright red


    - Submitted assignments appear in grey

        - On hover they appear blue

        - On hover the strikethrough is removed

2) You usually can't read the full assignment name.

     Fixes:

    - Assignment logo removed

    - Assignment name wraps to next line (if needed)

3) If there are numerous assignments on the calendar throughout many days bottom weeks become hidden.

     Fixes:

    - Calendar now expands to whatever height it needs

    - Weeks collapse to only take up the vertical space needed to display their assignments

4) Other visual enhancements

    - Cursor changes to a pointer when hovering an assignment

    - The strikethrough on completed assignments is removed on hover

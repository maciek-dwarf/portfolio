
# Game of Life

Implement Conway's Game of Life in 64-bit integer space.

Imagine a 2D grid where each cell (coordinate) can be **alive** or **dead**. Every generation of the simulation, the system ticks forward. Each cell's value changes according to the following rules:

- If an **alive** cell has less than 2 or more than 3 alive neighbours (in any of the 8 surrounding cells), it becomes dead.
- If a **dead** cell has **exactly** 3 alive neighbours, it becomes alive.

Your input is a list of integer coordinates for live cells in the Life 1.06 format. They could be anywhere in the signed 64-bit range. **This means the board can be very large.**

## Sample input

```
#Life 1.06
0 1
1 2
2 0
2 1
2 2
-2000000000000 -2000000000000
-2000000000001 -2000000000001
-2000000000000 -2000000000001
```

Your program should read the state of the simulation from standard input, run 10 iterations of the Game of Life, and print the result to standard output in the Life 1.06 format.

<a href="GameLife.zip" class="md-button md-button--primary">Download my solution</a>


<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>

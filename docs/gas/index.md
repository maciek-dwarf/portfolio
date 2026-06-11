
# Simple GAS project

Unreal Engine project using the Gameplay Ability System (GAS).

## Features

- Ranged weapon shooting projectiles (first person template)
- 4 ammunition types:
    - **Regular** — deals damage
    - **Fire** — deals fire damage and applies an on-fire effect to the target
    - **Water** — puts out flames and cancels on-fire effects
    - **Healing** — heals the target
- No particle effects required; changing asset colors is enough
- **On-fire effect** — deals fire damage periodically to the target; expires after some time by itself or when hit by water
- Damage system with multiple types and resistances to each one
- Health displayed over actors (basic UI or debug draws)

<a href="https://github.com/maciek-dwarf/para" class="md-button md-button--primary">Repository</a>


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


# Silence Remover

Short program which removes silent pauses in phrases from wave files.
First we detect interval where there was almost no sound ( some treshold )
and if longeur of it is significant (short silence periods aren't taken into account).




<a href="silence_remover.zip" class="md-button md-button--primary">Download</a>



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

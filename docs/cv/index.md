
# My CV

<object data="CV-angl.pdf" type="application/pdf" width="100%" height="600px">
    <p>Your browser does not support PDFs. <a href="CV-angl.pdf">Download the PDF</a>.</p>
</object>


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

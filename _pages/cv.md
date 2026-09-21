---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/cv-cazzella.pdf # the PDF this page redirects to
---

<script>
  (function () {
    var pdfUrl = "{{ page.cv_pdf | relative_url }}";
    var link = document.createElement("a");
    link.href = pdfUrl;
    link.download = "";
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);

    if (document.referrer && document.referrer.indexOf(window.location.host) !== -1) {
      window.location.replace(document.referrer);
    } else {
      window.location.replace("{{ '/' | relative_url }}");
    }
  })();
</script>

Downloading the <a href="{{ page.cv_pdf | relative_url }}" download>CV (PDF)</a>&hellip;

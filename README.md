# Setup

    bower install

    M-x: package-install ox-reveal

    evaluate this form with eval-last-sexp (C-x C-e) with your cursor after the last paren:
    (add-dir-local-variable 'org-mode 'org-reveal-root "../bower_components/reveal.js/") 
    (add-dir-local-variable 'org-mode 'org-reveal-title-slide "<h1 class=\"title\">%t</h1>") 

    C-c C-e R B to export the project

    git push to publish

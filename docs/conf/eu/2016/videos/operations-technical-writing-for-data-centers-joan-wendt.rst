:template: 2017/video-details.html

Operations Technical Writing for Data Centers
=============================================

{% set talk = conferences[2016]['eu']['speakers'][15] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}

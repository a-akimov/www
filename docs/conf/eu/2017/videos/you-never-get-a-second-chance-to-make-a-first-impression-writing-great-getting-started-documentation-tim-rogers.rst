:template: 2017/video-details.html

"You never get a second chance to make a first impression": writing great "getting started" documentation
=========================================================================================================

{% set talk = conferences[2017]['eu']['speakers'][1] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}

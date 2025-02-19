![](assets/images/logo_dark.svg#gh-dark-mode-only)![](assets/images/logo_light.svg#gh-light-mode-only)

# {{ project__short_description }}

## About

{{ project__name }} is scientific software for
{{ project__extended_description }}.

{% if project__deployment_type == "both" %}
{{ project__name }} is distributed as both a cross-platform desktop application
and a Python library.

Here you can find instructions for using the {{ project__name }} Python library.
Documentation for the {{ project__name }} graphical user interface can be found
[elsewhere]({{ project__urls__app_docs }}).
{% elif project__deployment_type == "lib" %}
{{ project__name }} is distributed as a Python library.
{% elif project__deployment_type == "app" %}
{{ project__name }} is distributed as a cross-platform desktop application.
{% endif %}

{{ project__name }} is part of the
[EasyScience framework](https://easyscience.software).

## License

{{ project__name }} is licensed under the
[BSD 3-Clause License](https://raw.githubusercontent.com/easyscience/{{ project__repos__lib }}/master/LICENSE).

## Latest release

The latest release of {{ project__name }} Python library is
[{{ vars.release_version }}](https://github.com/easyscience/{{ project__repos__lib }}/releases/latest).

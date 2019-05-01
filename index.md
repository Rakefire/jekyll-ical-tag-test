---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% ical url: https://space.floern.com/launch.ics reverse: true only_future: true %}
  {{ event.summary }}
  {{ event.description }}
  {{ event.simple_html_description }}
  {{ event.start_time }}
  {{ event.end_time }}
  {{ event.url }}
  {{ event.attendees }}
{% endical %}
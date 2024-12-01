---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Professor

{% include list.html data="members" component="portrait" filter="role == 'professor'" %}

# {% include icon.html icon="fa-solid fa-users" %}Ph. D. Students

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

# {% include icon.html icon="fa-solid fa-users" %}M. S. Students

{% include list.html data="members" component="portrait" filter="role == 'ms'" %}

# {% include icon.html icon="fa-solid fa-users" %}[Alumni](/team/Alumni)

---
title: Broken links found (via GH actions {{ event }})
labels: bug
---
{{ workflow }} found broken links. The check was triggered by {{ event }} for {{ env.CHECK_REPO }} on branch {{ ref }} with latest commit {{ sha }}.

You can find the check results here: {{ env.RUN_ID }}

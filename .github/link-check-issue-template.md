---
title: Broken links found (via {{ event }})
labels: bug
---
{{ workflow}} found broken links. The check was triggered on {{ date | date('dddd, MMMM Do') }} by {{ event }} on branch {{ ref }} with latest commit {{sha}}.

You can find the check results here: https://github.com/{{ env.REPO }}/actions/runs/{{ env.RUN_ID }}

---
title: Broken links found
labels: bug
---
{{ workflow}} found broken links. The check was triggered by {{ event }} on branch {{ ref }} with latest commit {{sha}}.

You can find the check results here: https://github.com/{{ repository }}/actions/runs/{{ env.RUN_ID }}


RUN_ID: {{ env.RUN_ID }}

RUN_NUMBER: {{ env.RUN_NUMBER }}

EVENT_PATH: {{ env.EVENT_PATH }}

JOB: {{ env.JOB }}

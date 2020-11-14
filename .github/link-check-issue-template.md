---
title: Broken links found
labels: bug
---
{{ workflow}} found broken links. The check was triggered by {{ event }} on branch {{ ref }} with latest commit {{sha}}.

You can find the check results here: https://github.com/{{ repo }}/actions/runs/{{ env.RUN_ID }}

repo: {{ repo }}

context.repo: {{ context.repo }}

env.repo: {{ env.repo }}

github.repo: {{ github.repo }}

github.repository: {{ github.repository }}

---
title: Broken links found
labels: bug
---
{{ workflow}} found broken links. The check was triggered by {{ event }} on branch {{ ref }} with latest commit {{sha}}.

You can find the check results here: ... // TODO

Check the context: 

tools.context.payload: {{ payload }}

run_id: {{ run_id }}

github.run_id: {{ github.run_id }}

github.event_path: {{github.event_path}}

github.job: {{github.job }}

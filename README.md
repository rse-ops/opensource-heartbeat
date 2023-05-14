# Open Source Heartbeat

![img/heartbeat.png](img/heartbeat.png)

This is the opensource heartbeat for Livermore Computing!  You can generate
your own with the GitHub action [rseng/opensource-heartbeat-action](https://github.com/rseng/opensource-heartbeat-action).

## Running Locally

Given you've cloned the repository above:

```bash
$ export INPUT_COLLECTION=_events
$ export INPUT_EVENTS=Issues,IssuesEvent,IssueCommentEvent
$ python ../opensource-heartbeat-action/scripts/generate-events.py --orgs user-orgs.txt 
```

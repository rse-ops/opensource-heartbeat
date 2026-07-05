---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2026-07-02
repo_name: kubeflow/trainer
html_url: https://github.com/kubeflow/trainer/issues/3427
repo_url: https://github.com/kubeflow/trainer
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubeflow/trainer/issues/3427' target='_blank'>kubeflow/trainer#3427</a>.

<small>@andreyvelich is the user application specifying the entrypoint with mpirun, and the issue is about the environment being discovered for it? If yes, the approach the flux operator takes is to take the application command, and wrap that. In the case of PYTORCH, the problem (I think, if I understand correctly) is that normally there is another layer (the workload manager) like Flux or Slurm that you use to run the job, and its the workload manager that ensures the environment is properly set. If you just expect a TrainJob to be executing a pytorch script, and then have all the envars set (and correct) for leader and launcher, then you are essentially re-implementing a workload manager. ...</small>

<a href='https://github.com/kubeflow/trainer/issues/3427' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-06-20
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/283
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/GLVis/glvis/issues/283' target='_blank'>GLVis/glvis#283</a>.

<small>You can try building GLVis and MFEM separately from your normal MFEM build -- for this you can use Apple clang. GLVis built this way can work with data sent from any other MFEM build, e.g. a build with a different compiler and with different optional libraries. GLVis does not use anything parallel from MFEM, so you don't loose anything by building serial MFEM for use by GLVis. Also, most optional packages that can be used by MFEM do not add any functionality to GLVis so building without them is perfectly fine. The one exception here, that I can think of, is NetCDF which adds support for reading NetCDF meshes which then allows GLVis to read these meshes too....</small>

<a href='https://github.com/GLVis/glvis/issues/283' target='_blank'>View Comment</a>
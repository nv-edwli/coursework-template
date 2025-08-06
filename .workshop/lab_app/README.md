# Section Four

<img src="_static/robots/blueprint.png" alt="Robot Character" style="float:right; max-width:350px;margin:15px;" />

TODO: Insert Content Here

## Subsection A

TODO: Insert Content Here

## Subsection B

<img src="_static/robots/wrench.png" alt="Robot Character" style="float:left; max-width:200px;margin:15px;" />

Open <a style="cursor: pointer;" onclick="openOrCreateFileInJupyterLab('labs/sample_file.py');"><i class="fa-brands fa-python"></i> labs/bridge_inspector.py</a> and we can get started by checking out the initial code.

This file already has a handful of functions templated. We will work on filling these in.

TODO: Insert Content Here

### Subsection i

TODO: Insert Content Here

### Subsection ii

At this point, we will loop over all the video files specified by the user at runtime. We need to call the function
<a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', 'def upload_video_to_vss');">upload_video_to_vss</a>
function in the
<a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', '# upload the video');"># upload the video</a> block of code.

TODO: Insert Content Here

### Subsection iii

<a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', 'def summarize_video');">summarize_video</a> should use the uploaded video ID to request a summary of the video. In the last excercise, we made some effective prompts that will help here.

This function should be invoked by <a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', '# summarize the video');"># summarize the video</a> block of code.

TODO: Insert Content Here

### Subsection iv

Use the `Chat` class from before (it is already imported from `helpers`), and connect to the VSS Chat server. In this example, the VSS URL is provided at runtime. Put this code in the <a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', '# summarize the video');"># summarize the video</a> block.

<a style="cursor: pointer;" onclick="goToLineAndSelect('labs/sample_file.py', '# ask follow up questions');"># ask follow up questions</a> should use the chat API to request additional information. 

TODO: Insert Content Here

<details>
<summary><b>💢 Stuck?</b></summary>

TODO: Insert Content Here

```python
escalations = chat_client.query("List any necessary escelations for maintenance.")
priority = chat_client.query("Score the priority of this report.")
title = chat_client.query("Create a title for this report.")
emergencies = chat_client.query("Does this the bridge require immediate structural attention?")
```

</details>

## Subsection C

TODO: Insert Content Here

## Subsection D

<img src="_static/robots/tpose.png" alt="Robot Character" style="float:right; max-width:350px;margin:15px;" />

TODO: Insert Content Here

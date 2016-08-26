# Introduction

This Repository contains a collections of FORJJ Flow definition.

# What is a Forjj flow?

I will clarify this strongly in the short future. 

But for now, mainly, each flow are stored under a subdirectory and contains at least one yaml file. 

Format: `<FlowName>/<FlowName>.yaml`


The flow helps FORJJ to apply some fixes in sources code and in applications to implement the flow requested.

Ex:
For a Pull Request flow, with github, we use fork technics. Then local repo will refer to 2 differents remotes, one upstream (parent fork) and one origin (your fork)

If we apply jenkins in this flow, automatically on the repo in github, some webhooks are created and jenkins gets at least 2 differents jobs, one for pull request build and one for release.

The `pull_request` found in `pull_request/pull_request.yaml` describe this.


The FORJJ Team

---
title: "YOUR_PROJECT_NAME"
description: "A short, catchy one-sentence description of what your project or tool does."
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Welcome to YOUR_PROJECT_NAME!"
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!-- The description from the metadata block above automatically displays here -->
{{% _param description %}}
{.display-6}

<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Get Started
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    View on GitHub
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}
{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}
Write a longer paragraph here (2-3 sentences) introducing your project. Explain the primary problem your tool solves, who it is built for, and its standout benefit.
{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="Key Feature One" icon="fa-lightbulb" %}}
Describe your first major feature or benefit here. Keep it punchy and short.
{{% /blocks/feature %}}

{{% blocks/feature title="Open Source & Community" icon="fab fa-github" url="https://github.com" %}}
We welcome contributions! Check out our repository to submit bug reports, feature requests, or pull requests.
{{% /blocks/feature %}}

{{% blocks/feature title="Stay Updated" icon="fab fa-x-twitter" url="https://x.com" %}}
Follow us for the latest announcements, feature rollouts, and updates.
{{% /blocks/feature %}}

{{% /blocks/section %}}

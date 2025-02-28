# playground-models
This repository contains Hackolade data models that can be viewed on https://hub.hackolade.com

The Hackolade Enterprise Model Hub is a metadata collaboration platform providing a unified and central access to your Hackolade Studio data models stored in one or more Git repositories. It empowers business teams, governance teams, and other stakeholders to collaborate effectively in order to promote a shared understanding of the context and meaning of data.

Feel free to explore at your leisure. It even allows you to [load your own models](#how-to-load-your-models-to-this-repository) into the repository, and view them in the Hub. We advise each organization to create its own folder, separate from others. The models and model changes you push into the repository are auto-merged, then automatically replicated to the Hub database. They should appear in just a few seconds.

The online user documentation for the Hub can be found [here](https://hackolade.com/help/Hubuserinterface.html).

**WARNING:** this demo of Hackolade Model Hub is open to anyone, so you should refrain from loading any confidential models.

Hackolade reserves the right to remove any inappropriate content from this repository, or any content that would negatively affect the platform.

## How to load your models to this repository
You may explore the Hub with models already present in the repo.  Loading your own models is optional, but the experience is more meaningful with your own models and terminology.

This repository is configured with a "Fork & Pull" strategy, very common in open-source, and also in [inner-source](https://hackolade.com/help/Workingwithforks.html).  But instead of having a maintainer review your models, we enabled an automatic merge of your models, so you could quickly see your models in the Hub, soon after submitting your Pull Request (see step 4 below.)

Follow these steps in order to add models to this repository

1. **Fork the repository**

    This step cannot be done in Hackolade Studio.  It must be made in GitHub, and requires that you have a [GitHub account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) (free.)

    Click on this <a icon="repo-forked" class="github-button" href="https://github.com/hackolade/playground-models/fork">fork button</a> to copy the repository in your own GitHub account. This will open a form like the following

    <img src="./docs/images/fork-form.png" />

    You don't have to change anything, just click `Create fork`

1. Clone the new repository on your workstation with [Hackolade Studio](https://hackolade.com/help/Clonearemoterepository.html), or alternatively with you favorite Git client.
   > Since this a is a public repository, make sure to not add any confidential models

   > We advise each organization to create its own folder, separate from others

1. Create new models or save existing models in the forked repo, then [commit and push the model(s)](https://hackolade.com/help/Commitlocalchanges.html).

1. Still in Hackolade Studio, [submit a Pull Request from the fork](https://hackolade.com/help/Workingwithforks.html#Submit%20a%20Pull%20Request%20from%20a%20fork).

1. After a few seconds, your pull request should be merged into the main repository, replicated with the Hub database, then visible on https://hub.hackolade.com

As an alternative to step 4, you can manually do this in GitHub screens:

4 alt. On the GitHub page, click on `Contribute` and `Open pull request` like shown on the picture below

<img src="./docs/images/contribute.png" />

5 alt. On the pull request page, give a title to your pull request and then click `Create pull request`

<img src="./docs/images/pull-request.png" />

6 alt.  After a few seconds, your pull request should be merged into the main repository, replicated with the Hub database, then visible on https://hub.hackolade.com

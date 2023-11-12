# Universal Story Tags (U-Stags)

<p align="center">
<a href="https://github.com/magejosh/u-stags/fork" target="blank">
<img src="https://img.shields.io/github/forks/magejosh/u-stags?style=for-the-badge" alt="U-Stags forks"/>
</a>
<p align="center">
<a href="https://github.com/magejosh/u-stags/stargazers" target="blank">
<img src="https://img.shields.io/github/stars/magejosh/u-stags?style=for-the-badge" alt="U-Stags stars"/>
</a>
<!-- Commented out the release badge as there's no specific release -->
<!-- <a href='https://github.com/magejosh/u-stags/releases'>
<img src='https://img.shields.io/github/release/magejosh/u-stags?&label=Latest&style=for-the-badge'>
</a> -->
<p align="center">
<a href="https://github.com/magejosh/u-stags/commits" target="blank">
<img src="https://img.shields.io/github/commit-activity/m/magejosh/u-stags?style=for-the-badge" alt="U-Stags Commit Activity"/>
</a>
</p>
<p align="center"><b>Follow MageJosh </b></p>

<p align="center">
<a href="https://twitter.com/ErroneousGaes" target="blank">
<img src="https://img.shields.io/twitter/follow/ErroneousGaes?label=Follow%20@ErroneousGaes&style=social" alt="Follow @ErroneousGaes"/>
</a>
<a href="https://www.youtube.com/channel/UCT1Y4ESuLjKiqtHrRcmr57w" target="_blank">
<img src="https://img.shields.io/twitter/url?label=Subscribe%20to%20@magejoshplays5966&logo=youtube&style=social&url=https://www.youtube.com/channel/UCT1Y4ESuLjKiqtHrRcmr57w" alt="Subscribe to @magejoshplays5966"/>
</a>
<a href="https://www.reddit.com/user/Significant-Ad-2921" target="_blank">
<img src="https://img.shields.io/twitter/url?label=Follow%20on%20Reddit&logo=reddit&style=social&url=https://www.reddit.com/user/Significant-Ad-2921" alt="Follow on Reddit"/>
</a>
<a href="https://discord.gg/5q5bvMFBm4" target="blank">
<img src="https://img.shields.io/discord/5q5bvMFBm4?label=Join%20Discord&logo=discord&style=social" alt="Join Discord Community"/>
</a>
</p>

<p align="center"><b>Support MageJosh</b></p>

<p align="center">
<a href="https://ko-fi.com/magejosh" target="_blank">
<img src="https://img.shields.io/twitter/url?label=Support%20on%20Ko-fi&logo=ko-fi&style=social&url=https://ko-fi.com/magejosh" alt="Support on Ko-fi"/>
</a>
<a href="https://www.patreon.com/Magejoshplays" target="_blank">
<img src="https://img.shields.io/twitter/url?label=Support%20on%20Patreon&logo=patreon&style=social&url=https://www.patreon.com/Magejoshplays" alt="Support on Patreon"/>
</a>
</p>

<p align="center"><b>Share U-STags Repository</b></p>

<p align="center">
<a href="https://twitter.com/intent/tweet?text=Check%20out%20this%20GitHub%20repository%20for%20Universal%20Story%20Tags%20(U-STags)%20-%20a%20framework%20for%20story%20tagging%20and%20mapping.&url=https://github.com/magejosh/u-stags&hashtags=U-STags,StoryMapping,NLP" target="blank">
<img src="https://img.shields.io/twitter/url?label=Share%20Repo%20on%20Twitter&logo=twitter&style=social&url=https://github.com/magejosh/u-stags" alt="Share Repo on Twitter"/>
</a> 
<a href="https://www.reddit.com/submit?url=https://github.com/magejosh/u-stags&title=Check%20out%20the%20U-STags%20GitHub%20repository%20for%20story%20tagging%20and%20mapping" target="blank">
<img src="https://img.shields.io/twitter/url?label=Share%20on%20Reddit&logo=reddit&style=social&url=https://github.com/magejosh/u-stags" alt="Share on Reddit"/>
</a>
<a href="mailto:?subject=Check%20out%20the%20U-STags%20GitHub%20repository&body=U-STags%20-%20A%20framework%20for%20story%20tagging%20and%20mapping.%3A%0Ahttps://github.com/magejosh/u-stags" target="_blank">
<img src="https://img.shields.io/twitter/url?label=Share%20via%20Email&logo=gmail&style=social&url=https://github.com/magejosh/u-stags"/></a> 
</p>

## Description

Universal Story Tags (U-Stags) is an open-source project dedicated to creating a set of Natural Language Processing (NLP) instructions that provide a framework for condensing larger stories into smaller token counts without losing relevant details. It achieves this by associating stories with corresponding tags for efficient classification, retrieval, and organization. The detailed instructions for mapping of stories to tags can be found in `stm.md`.

This project has been designed with scalability and community contribution in mind. It can be expanded to include additional functionalities as discovered and used by the community. It relies on a context window large enough for the instruction prompt as well as a copy of stm.md or it's contents as an example in addition to the story that is being mapped. You can chunk the story for processing if needed.

## Story Tag Mapping

The `stm.md` file contains a robust set of instructions on how each story in our dataset is associated with specific tags. This file is key to understanding the organization and classification system used in this project and serves as a blueprint for condensing larger narratives. It is also the core framework all other branches come from.

## New Feature: Interactive Fiction Storymapping

Introducing a new branch in U-Stags: U-Stags-IF (Universal Story Tags - Interactive Fiction), designed for mapping interactive game narratives. This extension focuses on altering the format of storymapping to be XML in nature which is perfect for structuring dynamic and player-driven stories elements, providing tools for creating engaging game experiences and AI assisted IF. Examples can be found in the `InteractiveExamples` folder. The expanded details for interactive story mapping can be found in `stm4IF.md`.

## New Feature: Adventure Path Storymapping

Introducing a new branch in U-Stags: U-Stags-AP (Universal Story Tags - Adventure Path), designed for mapping interactive game narratives. This extension focuses on structuring dynamic and player-driven stories, providing tools for creating engaging game experiences. Examples can be found in the `InteractiveExamples` folder. The expanded details for interactive story mapping can be found in `adventureMapping.md`.

## Contributing

As an open-source project, Universal Story Tags welcomes contributions from everyone. If you have a feature request, suggestion, or bug report, please open an issue on the issue tracker. If you wish to contribute your code, please fork this repository and submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 - see the `LICENSE` file for more details.

# u-stags Inspiration

Inspired by aider's use of Universal Ctags for repo mapping, but applied instead to fiction writing to facilitate writers who frequently hit context limits and coders wanting to make AI leveraging tools for writers.
https://github.com/paul-gauthier/aider

# Wishlist

Ideally this will grow as more users add it to their workflows.

1. Expanded tags options (this remains the top priority)
2. Refined psuedo code instructions for different use-cases
3. Scripts in python for each of the above code instructions so this repo can be used programmatically built into it.

# Roadmap

Expanding tags and prompts to use the mapping method are next on the list.
Beyond that, remains to be seen where the fires are.

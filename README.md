> [!Important]
> 
> ### This project is no longer actively maintained.
> 
> The source code in this repository is no longer maintained. It has been superseded by [version 2](https://os2display.github.io/display-docs/), which offers improved features and better support.
> 
> Thank you to all who have contributed to this project. We recommend transitioning to [Os2Display version 2](https://os2display.github.io/display-docs/) for continued support and updates.
> 
> **Final Release**: The final stable release is version [2.0.1](https://github.com/os2display/youtube-bundle/releases/tag/2.0.1)
<br>

# youtube-bundle
Contains a template for youtube videos.

## Installation
Add the git repository to "repositories" in `composer.json`.

<pre>
"repositories": {
    "os2display/youtube-bundle": {
      "type": "vcs",
      "url": "https://github.com/os2display/youtube-bundle"
    },
    ...
}
</pre>

Require the bundle with composer.

<pre>
composer require os2display/youtube-bundle
</pre>

Enable the bundle in `AppKernel.php`, by adding Os2DisplayYoutubeBundle to $bundles.

<pre>
new Os2Display\YoutubeBundle\Os2DisplayYoutubeBundle()
</pre>

Run os2display:core:templates:load command to load the template in the installation.
<pre>
bin/console os2display:core:templates:load
</pre>

Enable the template in the administration.

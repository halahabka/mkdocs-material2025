# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Admin

L'application administration centralise toutes les taches d'administration de la plateforme 

## Annotations 

First text that contains an annotation Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
{ .annotate }

1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.


Second text with 2 annotations Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.(2)
{ .annotate }

1.  :man_raising_hand: 22222 I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.
1.  :man_raising_hand:222 and i contain an another anotation (1)
    { .annotate }
    
    1.  :woman_raising_hand: I'm an annotation as well!


<div class="annotate" markdown>

> Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.

</div>

1.  :man_raising_hand: I'm an annotation!
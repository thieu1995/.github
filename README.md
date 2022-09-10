# Default Github's health files


## License Templates

These files are designed to be used by `lice`, a command-line license generator
for software projects. 

### Format/Structure

The template uses variables as placeholders to substitute values specified by
`lice`.

* `{{ year }}`: the year of the software's copyright.
* `{{ organization }}`: the name of the organization or individual who holds
the copyright to the software.
* `{{ project }}`: the name of the software project.



## .gitignore templates 

For more information about how `.gitignore` files work, and how to use them,
the following resources are a great place to start:

- The [Ignoring Files chapter][chapter] of the [Pro Git][progit] book.
- The [Ignoring Files article][help] on the GitHub Help site.
- The [gitignore(5)][man] manual page.

### Folder structure

We support a collection of templates, organized in this way:

- The root folder contains templates in common use, to help people get started
  with popular programming languages and technologies. These define a meaningful
  set of rules to help get started, and ensure you are not committing
  unimportant files into your repository.
- [`Global`](./Global) contains templates for various editors, tools and
  operating systems that can be used in different situations. It is recommended
  that you either [add these to your global template](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files#configuring-ignored-files-for-all-repositories-on-your-computer)
  or merge these rules into your project-specific templates if you want to use
  them permanently.
- [`community`](./community) contains specialized templates for other popular
  languages, tools and project, which don't currently belong in the mainstream
  templates. These should be added to your project-specific templates when you
  decide to adopt the framework or tool.

### What makes a good template?

A template should contain a set of rules to help Git repositories work with a
specific programming language, framework, tool or environment.

If it's not possible to curate a small set of useful rules for this situation,
then the template is not a good fit for this collection.

If a template is mostly a list of files installed by a particular version of
some software (e.g. a PHP framework), it could live under the `community`
directory. See [versioned templates](#versioned-templates) for more details.

If you have a small set of rules, or want to support a technology that is not
widely in use, and still believe this will be helpful to others, please read the
section about [specialized templates](#specialized-templates) for more details.

Include details when opening pull request if the template is important and visible. We
may not accept it immediately, but we can promote it to the root at a later date
based on interest.

Please also understand that we can’t list every tool that ever existed.
Our aim is to curate a collection of the _most common and helpful_ templates,
not to make sure we cover every project possible. If we choose not to
include your language, tool, or project, it’s not because it’s not awesome.


# Copyright

All licenses in this repository are copyrighted by their respective authors.
Everything else is released under CC0. See `LICENSE` for details.


# File Datastore Git Template

The idea is to quickly turn a `git` repository into a version-controllable file
storage facility without spinning a new type of file server (e.g. `samba`,
`syncthing`, etc) using a `git version control system` (GVCS)'s `releases`
feature.

The most important goal is to facilitate **non-tech users to use the same
GVCS server without causing too much damages due to technical debt** while
letting tech folks to seamlessly come in anytime and support them easily.

Ultimately, it is for data warehouse maintenance sanity especially in a
hardware restricted self-hosting environment.

Use cases include but not limited to:

* photo albums.
* non-text, binary, archived zip files.
* CAD design files.
* Non-text files.
* Anything when you have no idea how to use `git`.




## To Access The Content

[![chewkeanho-template](/.internals/trademarks/banner_1200x100.svg)](#)

If you are **NOT ASKED** to create or maintain one, **you are likely looking for
the contents files in the `Releases` section**. Head over there and browse your
contents.

On GitHub:

![gihub-release-section](/.internals/screenshots/github-release-section.svg)

On Forgejo:

![gihub-release-section](/.internals/screenshots/forgejo-release-section.svg)

On Gitea:

![gitea-release-section](/.internals/screenshots/gitea-release-section.svg)




## To Add/Remove Content

[![chewkeanho-template](/.internals/trademarks/banner_1200x100.svg)](#)

If you're asked to add or remove content of an existing release:

1. Head over to `Releases Section` (refer illustrations above).
2. Goto your release version.
3. Select `Edit` button (refer illustrations here).
4. Upload/remove your files accordingly by drag-and-dropping your files into the
   *File Dropzone*. That's how you upload your files. Take note that the max
   size or total number of files limits is ultimately set by the service
   provider.
5. Press `Publish Release` or `Update Release` to save your changes.

On GitHub:

![github-new-release](/.internals/screenshots/github-edit-release.svg)

On Forgejo:

![forgejo-new-release](/.internals/screenshots/forgejo-edit-release.svg)

On Gitea:

![gitea-new-release](/.internals/screenshots/gitea-edit-release.svg)




## To Create a New Release

[![chewkeanho-template](/.internals/trademarks/banner_1200x100.svg)](#)

If you're asked to create a new release tag:

1. Head over to `Releases Section` (refer illustrations above).
2. Select the `Create a New Release` OR `New Release` button instead of the
   edit button (refer illustrations above).
3. Fill in the form (refer illustrations here):
   1. For `tag` (it's like bookmark when reading a thick book), use a sane value
      like `v1`, `v1.0.0` or `Stores`. **Only numbers (`0-9`),
      alphabets (`a-z`|`A-Z`), period dot (`.`), and dash (`-`) ARE ALLOWED**.
   2. For `title`, it can be anything. Basically, it is the title of that
      website.
   3. Optionally, you can refer to the above guide on how to upload files.
4. Press `Publish Release` to save.

On GitHub:

![github-new-release](/.internals/screenshots/github-new-release.svg)

On Forgejo:

![forgejo-new-release](/.internals/screenshots/forgejo-new-release.svg)

On Gitea:

![gitea-new-release](/.internals/screenshots/gitea-new-release.svg)




## To Create New Repository

If you are asked to create a new datastore repository:

1. Simply select the **`Use This Template`** on your GCVS web terminal (refer
   to illustrations here).
2. Create a proper repository with a desired and good pathing. Tip: construct
   a guessable URL address.
2. Then refer the above to create the first release.

On GitHub:

![github-press-use-this-template-button](/.internals/screenshots/github-press-use-template-button.svg)

On Forgejo:

![forgejo-press-use-this-template-button](/.internals/screenshots/forgejo-press-use-template-button.svg)

On Gitea:

![gitea-press-use-this-template-button](/.internals/screenshots/gitea-press-use-template-button.svg)




## License

[![chewkeanho-template](/.internals/trademarks/banner_1200x100.svg)](#)

This template repository is licensed under [BSD 1-Clause License](LICENSE.txt).
The following are the product details:

```
Title               : (Holloway) Chew, Kean Ho's Git File Storage Datastore Template
Creators            : (Holloway) Chew, Kean Ho
Packaged-By         : (Holloway) Chew, Kean Ho
Contact             : hello@chewkeanho.com
UUID                : B5F5091C-81E1-4D01-B886-BC3F82A83537
SKU                 : chewkeanho-software-file-datastore-git-template
Trademark Holder    : Chew Kean Ho (natural person)
License             : BSD 1-Clause License
Repository Made On  : 2025-11-30
Repository Made From: Malaysia, South East Asia
Procure             : https://github.com/ChewKeanHo/software-file-datastore-git-template
```

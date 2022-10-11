# Nota
All of the packages linking to this repository are made for [@Numigi](https://github.com/Numigi). This is with the purpose of facilitating the installation of new systems.

> All of the users machines [@Numigi](https://github.com/Numigi) use the same base distribution: Ubuntu. Packages are compressed in a `.deb` format and must follow the conventions listed in this repository.

The maintainer of these utilities is myself, [@Lanhild](https://github.com/Lanhild).

# Packaging conventions for [numigi-ppa](https://github.com/Lanhild/numigi-ppa)

> Folder structure options and naming conventions for packages

### A typical top-level directory layout for packaging

    .
    ├── your-package            # Source package files (alternatively `src`)
    ├── postinst                # Post-installation scripts (alternatively `ext`)
        ├── install-hook        # Post-installation script
    ├── LICENSE
    ├── README.md
    ├── gen-packages            # Helper script to build packages into an archive
    └── .env                    # Environment variables used to generate the packages.

> Use short lowercase names at least for the top-level files and folders except
> `LICENSE`, `README.md`


### License information

If you want to share your work with others, please consider choosing an open
source license and include the text of the license into your project.
The text of a license is usually stored in the `LICENSE` (or `LICENSE.txt`,
`LICENSE.md`) file in the root of the project.

> You’re under no obligation to choose a license and it’s your right not to
> include one with your code or project. But please note that opting out of
> open source licenses doesn’t mean you’re opting out of copyright law.
> 
> You’ll have to check with your own legal counsel regarding your particular
> project, but generally speaking, the absence of a license means that default
> copyright laws apply. This means that you retain all rights to your source
> code and that nobody else may reproduce, distribute, or create derivative
> works from your work. This might not be what you intend.
>
> Even in the absence of a license file, you may grant some rights in cases
> where you publish your source code to a site that requires accepting terms
> of service. For example, if you publish your source code in a public
> repository on GitHub, you have accepted the [Terms of Service](https://help.github.com/articles/github-terms-of-service)
> which do allow other GitHub users some rights. Specifically, you allow others
> to view and fork your repository.

For more info on how to choose a license for an open source project, please
refer to http://choosealicense.com
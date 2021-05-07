# Spack Repository Template

Spack is a dual-licensed project, and getting all the right files in the right
place can be a pain. This is a simple template repository that you can use to
ensure you have all the right files present in your repo.

## Files you need

These should be at the top level of your repository:

* `README.md` - The `README.md` file should have a short section at the bottom
  called "License", with a really brief statement saying that Spack is
  dual-licensed and what that means. It should also have the SPDX license
  identifier and the LLNL release number for Spack (see below).
* `COPYRIGHT` - Used because Spack is dual-licensed, and if `COPYRIGHT` is not
  present, GitHub's "License" link will point to one of the top two `LICENSE-*`
  files. `COPYRIGHT` has:
    * The same short text that's in the `README.md` so that
      people know Spack is dual-licensed.
    * A statement that copyrights are retained by contributors.
    * Pointers to LICENSE-* and NOTICE files.
    * A description of what SPDX identifiers are.
* `LICENSE-MIT` - The text of the `MIT` license.
* `LICENSE-APACHE` - The text of the `Apache-2.0` license.
* `NOTICE` - LLNL's required `NOTICE` with contract info and disclaimer. The
  `Apache-2.0` license also requires that this be distributed.

## License Headers

In files in the repository, you should have a short header like this:

```python
# Copyright 2013-2021 Lawrence Livermore National Security, LLC and other
# Spack Project Developers. See the top-level COPYRIGHT file for details.
#
# SPDX-License-Identifier: (Apache-2.0 OR MIT)
```

For languages with different types of comments, you can just use whatever is
standard, e.g. `//` for C++, `/* */` for C, `--` for Lua, `%` for Prolog/ASP
etc.

This header lets people know the file is part of Spack and identifies the
license concisely with an SPDX identifier. It also makes it clear that the
copyright is not just LLNS's -- copyrights are retained by developers.

## License

This project is part of Spack. Spack is distributed under the terms of both the
MIT license and the Apache License (Version 2.0). Users may choose either
license, at their option.

All new contributions must be made under both the MIT and Apache-2.0 licenses.

See LICENSE-MIT, LICENSE-APACHE, COPYRIGHT, and NOTICE for details.

SPDX-License-Identifier: (Apache-2.0 OR MIT)

LLNL-CODE-811652

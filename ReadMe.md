# WishKit

Windows Image Servicing Hosting Kit, based on Component Based Servicing API.

## Q&A

### Why this project called WishKit?

- The abbreviation of WISH is Windows Image Servicing Hosting.
- I WISH the DISM++ can be open-source but it's impossible. I'm one of the
  DISM++ developers, but I need to respect with the DISM++ author's decision.
- Many people WISH that we can have an open-source Windows image servicing Kit.

### Why not make DISM++ open-source?

The DISM++ author have the miserable experience when he make his Windows image
servicing tool (the earliest prototype of DISM++) open-source at least 12 years
ago because some people use the open-source implementation to making money only
with changing the project name.

When I making [NSudo] open-source, he strongly disagree with my decision because
of that. But after several years efforts, he created some open-source projects
in the [Chuyu Team] GitHub organization because my decision in [NSudo] makes me
earned lot of reputations.

But he only select making utilities libraries open-source because of the past
experience. I need to respect with his decision because we have at least 10
years friendship.

So, WishKit would NEVER use the private source code from DISM++. Also, I want
to rethink the design of Windows image servicing tool.

[NSudo]: https://github.com/M2TeamArchived/NSudo
[Chuyu Team]: https://github.com/Chuyu-Team

## Planned Features

- [ ] Servicing Stack API definitions with source binary references.
- [ ] Modern UI based on XAML Islands with dark mode support.
- [ ] Full featured command line version.
- [ ] Support Windows Vista and later offline images.
- [ ] Provide lightweight Windows image servicing SDK.

## Currently Status

Not started because I'm working on NanaZip 3.0's development. It will push the
progress of the UI stack used in WishKit.

## Maintenance Policy

- The stability of Windows images are the No.1 priority.
- Try best to provide the best execution performance.
- Try best to provide the best cleanup results.

## Documents

- [License](License.md)
- [Versioning](Versioning.md)
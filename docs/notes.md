# Notes

## GitHub

libESMTP is officially hosted at
[https://libesmtp.github.io/](https://libesmtp.github.io/).

Do not use copies of libESMTP obtained elsewhere.  I do not endorse other
repositories which may contain copies or modifications to libESMTP.

## Tarballs

The libesmtp-1.0.6 and earlier tarballs are widely distributed, however,
being a decade or more old they all contain defunct links. I have no idea how
widespread these are or whether they have been modified.  It is impossible for
me to verify their authenticity, without expending some effort, and I am not
prepared to do so or to discuss the matter.

All users are strongly encouraged to discard any tarballs in favour of
the [GitHub repository](https://github.com/libesmtp/libESMTP).

## Old Websites

The old libESMTP websites at stafford.uklinux.net and brianstafford.info are
gone permanently.  brianstafford.info now belongs to a namesake.

Other than for libESMTP, I had no further use for the brianstafford.info
domain.  Since the web and email hosting fees were a couple of hundred pounds
annually and paid for at my own expense for no particular benefit, I cancelled
the service.

## Modifications

Bug-fixes or other enhancements that have been made against the v1.0.6 tarball,
or other repositories, should be resubmitted as pull requests to
[https://github.com/libesmtp/libESMTP](https://github.com/libesmtp/libESMTP).

libESMTP 1.0.6 may be found on the `libesmtp-1.0.6` branch, however please
also read [the errata](errata.md).

See also the [Reporting Bugs](bugreport.md) guidelines.

## Autotools

Post libESMTP v1.0.6 the autotools build system is removed and replaced with
[Meson](https://mesonbuild.com/).  I have made my feelings on autotools known
elsewhere on several occasions. This decision is non-negotiable, the autotools
build is just too difficult to maintain.


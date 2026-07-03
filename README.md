# Setup Node and pnpm

* Reads node version file (.node-version) from project root
* Only saves pnpm cache on the main branch
* Restores pnpm cache on PR
* Skips `actions/setup-node` on Alpine Linux (which only ships glibc
  binaries) and uses the container's musl Node instead.

## ❤ Who's [Sponsoring Oxc](https://github.com/sponsors/Boshen)?

<p align="center">
  <a href="https://github.com/sponsors/Boshen">
    <img src="https://raw.githubusercontent.com/Boshen/sponsors/main/sponsors.svg" alt="Our sponsors" />
  </a>
</p>

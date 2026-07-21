# Setup Node and pnpm

* Reads node version file (.node-version) from project root
* Only saves pnpm cache on the main branch
* Restores pnpm cache on PR
* Skips `actions/setup-node` on Alpine Linux (which only ships glibc
  binaries) and uses the container's musl Node instead.

# [Sponsored By](https://oxc.rs/sponsor)

<p align="center">
  <a href="https://oxc.rs/sponsor">
    <img src="https://raw.githubusercontent.com/oxc-project/sponsors/main/sponsors.svg" alt="Our sponsors" />
  </a>
</p>

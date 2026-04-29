# Setup Node and pnpm

* Reads node version file (.node-version) from project root
* Only saves pnpm cache on the main branch
* Restores pnpm cache on PR
* Auto-detects Alpine Linux containers and skips `actions/setup-node`
  (which only ships glibc binaries) so the container's musl Node is used.
  Override with `install-node: true | false`.

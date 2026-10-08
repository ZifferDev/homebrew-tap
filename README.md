# ZifferDev Homebrew tap

Homebrew packages for [ziffer.dev](https://ziffer.dev).

The stable digit formula is generated automatically after the first signed stable
[digit release](https://github.com/ZifferDev/digit/releases). Release candidates do
not update the stable formula. Until that first stable release, use the source
build or a specifically selected release candidate.

Once a stable release is available:

    brew install ZifferDev/tap/digit
    brew upgrade ZifferDev/tap/digit

Supports macOS ARM64 and Linux ARM64/x64. Shell completions are included.
See the [digit documentation](https://github.com/ZifferDev/digit/tree/main/docs).
Updating the CLI does not start or update Minecraft servers.

The release workflow in ZifferDev/digit maintains Formula/digit.rb using verified
GitHub release checksums and a deploy key scoped to this repository.

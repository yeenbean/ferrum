<div align="center">
    <br/>
    <p>
        <img src="web/static/favicon.png" title="ferrum" alt="ferrum logo" width="100" />
    </p>
    <p>
        best way to save what you love
        <br/>
        <a href="https://example.com">
            ferrum.tools
        </a>
    </p>
    <br/>
</div>

ferrum is a media downloader that doesn't piss you off. it's friendly, efficient, and doesn't have ads, trackers, paywalls or other nonsense.

paste the link, get the file, move on. that simple, just how it should be.

### ferrum monorepo
this monorepo includes source code for api, frontend, and related packages:
- [api tree & readme](/api/)
- [web tree & readme](/web/)
- [packages tree](/packages/)

it also includes documentation in the [docs tree](/docs/):
- [how to run a ferrum instance](/docs/run-an-instance.md)
- [how to protect a ferrum instance](/docs/protect-an-instance.md)
- [ferrum api instance environment variables](/docs/api-env-variables.md)
- [ferrum api documentation](/docs/api.md)

### ethics
ferrum is a tool that makes downloading public content easier. it takes **zero liability**.
the end user is responsible for what they download, how they use and distribute that content.
ferrum never caches any content, it [works like a fancy proxy](/api/src/stream/).

ferrum is in no way a piracy tool and cannot be used as such.
it can only download free & publicly accessible content.
same content can be downloaded via dev tools of any modern web browser.

### contributing
if you're considering contributing to ferrum, first of all, thank you! check the [contribution guidelines here](/CONTRIBUTING.md) before getting started, they'll help you do your best right away.

### licenses
for relevant licensing information, see the [api](api/README.md) and [web](web/README.md) READMEs.
unless specified otherwise, the remainder of this repository is licensed under [AGPL-3.0](LICENSE).

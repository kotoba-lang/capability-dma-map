# capability-dma-map

Atomic authority package for `dma/map`.

- imports: `#{:dma-map}`
- effects: `#{:memory-access :device-control}`
- default policy: `:autonomous`
- semantic definition CID: `bafyreies4n3abl6d5ei6mfmcel3xsn7lcjqzyn43hboqgk54wsccudtf6u`
- hash contract CID: `bafkreiflhj3fslsbh7okdas2fzlhmogai64x6p3lkla6gtr7berbp7ftvi`
- provider status: `contract-only`

The repository name is a discovery alias. The semantic definition CID
is the immutable import identity. Importing it does not grant runtime
authority: Tamaki must request it explicitly and Kototama must admit
the sealed envelope.

```sh
clojure -M:test
```

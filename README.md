# pixel.rip

A little website for a little studio. 

- Jekyll
- Sass
- Cloudflare


### Local Development

to run: `bundle exec jekyll serve`


### Deploying

Currently setup to automatically deploy to `master` when changes are made on github via Cloudflare.


### Categories and Front Matter
Each category lives in a subfolder of `_posts`. Configuration for `category` and `layout` for each folder is in `_config.yml`

- `resource`: links to useful tools, videos, etc
    - `title: `
    - `date: YYYY-MM-DD`
    - `category: resources`
    - `layout: resource`
    - `xurl: `
    - `tags: [tag1, tag2]`
    - `pinned: true | false`


- `codex`: debateably useful knowlege i've picked up along the way. proofs of concept, demos, etc. 
    - `title:`
    - `date: YYYY-MM-DD`
    - `category: codex`
    - `layout: codex-entry`
    - `github:`
    - `tags: [tag1, tag2]`
    - `pinned: true | false`


- `notes`: meta content, updates, news, etc
    - `title`
    - `date: YYYY-MM-DD`
    - `category: notes`
    - `layout: note`
    - `tags: [tag1, tag2]`
    - `pinned: true | false`

### Todo

- [ ] tag links in hello world
- [ ] tag pages
- [ ] codex page
- [ ] resources page
- [ ] notes page
- [ ] external links
    - [ ] github
    - [ ] bluesky?
- [ ] responsive sidebar

# overture-site

The homepage for [Overture Interactive, Inc.](https://overtureinteractive.com): a single static page served by
Cloudflare Workers static assets.

- `public/index.html`: the page
- `wrangler.jsonc`: Worker config and the overtureinteractive.com custom domains

## Deploy

```sh
npx wrangler deploy
```

This needs a Cloudflare account that owns the overtureinteractive.com zone, so it will not work for forks as is.
Change `name` and remove `routes` in `wrangler.jsonc` to deploy a copy to a `workers.dev` address.

## License

The code is MIT licensed (see `LICENSE`). The Overture Interactive, LoL Sketch, Magistones and Fret Flow names and
logos are not covered by that license.

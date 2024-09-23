# PSBT Wiki

## Intro

This PSBT Wiki provides comprehensive information on PSBT and how Partially Signed Bitcoin Transactions are used for selling and buying ordinals, marketplace listings and other use cases. The wiki also covers BIP-174, BIP-370, and resources for beginners and advanced users alike including eli5, memes, quick glossary and tech contributions.

Built with love by [Ivan Molto](https://x.com/ivanmolto) for the [OP_HACK001](https://app.buidlbox.io/arch-network/ophack001) hackathon sponsored by [Arch Network](https://www.arch.network/) and [Seize CTRL](https://www.seizectrl.io) at [buidlbox](https://buidlbox.io).

## Getting started

To get started with this repo, first install the npm dependencies:

```bash
npm install
```

Next, run the development server:

```bash
npm run dev
```

Finally, open [http://localhost:3000](http://localhost:3000) in your browser to view the website.

## Global search

This website includes a global search that's powered by the [FlexSearch](https://github.com/nextapps-de/flexsearch) library. It's available by clicking the search input or by using the `⌘K` shortcut.

This feature requires no configuration, and works out of the box by automatically scanning your documentation pages to build its index. You can adjust the search parameters by editing the `/src/markdoc/search.mjs` file.

## Tech Stack

To learn more about the technologies used in this site template, see the following resources:

- [Next.js](https://nextjs.org/docs) - the official Next.js documentation
- [Markdoc](https://markdoc.dev) - the official Markdoc documentation
- [Algolia Autocomplete](https://www.algolia.com/doc/ui-libraries/autocomplete/introduction/what-is-autocomplete/) - the official Algolia Autocomplete documentation
- [FlexSearch](https://github.com/nextapps-de/flexsearch) - the official FlexSearch documentation
- [Tailwind CSS](https://tailwindcss.com/docs) - the official Tailwind CSS documentation
- [Headless UI](https://headlessui.com) - the official Headless UI documentation

## License

The code is licensed under a MIT License.

Some contributed definitions have been sourced under a CC-BY license from the https://en.bitcoin.it/wiki/Main_Page [bitcoin Wiki], and other contributed definitions have been sourced under a CC-BY-SA license from "Mastering Bitcoin: Unlocking Digital Currencies" (1st Edition) by Andreas M. Antonopoulos.

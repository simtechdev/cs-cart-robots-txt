# `robots.txt` template for CS-Cart

This repo contains [`robots.txt`][developer_mozilla] file template for CS-Cart and Multi-Vendor.

[developer_mozilla]: https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt

For more information about how `robots.txt` files work, and how to use them, the following resources are a great place to start:

- [Introduction to robots.txt][robotstxt_google_introduction]
- [Robots.txt IETF specification draft][ietf_specification_draft]
- [Robots.txt Google specifications][robotstxt_google]
- [The Web Robot Pages is an information resource dedicated to web robots][robotstxt_org]

[robotstxt_google_introduction]: https://developers.google.com/search/docs/advanced/robots/intro
[ietf_specification_draft]: https://datatracker.ietf.org/doc/html/draft-rep-wg-topic-00
[robotstxt_google]: https://developers.google.com/search/docs/advanced/robots/robots_txt
[robotstxt_org]: https://www.robotstxt.org/

## What is `robots.txt` used for?

A robots.txt file tells search engine crawlers which pages or files the crawler can or can't request from your site.

### Security

Sometimes search engines can index pages, which should not be accessible to the web. Directives "Disallow" in robots.txt with specific locations can make your website more secure.

- [CS-Cart: Debug and configuration information - December 27, 2018][ghdb-id-5064]

[ghdb-id-5064]: https://www.simtechdev.com/cloud/wiki/news/google-dork-config/index.html

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[CC0-1.0](./LICENSE).

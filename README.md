# AdGuard DNS Filters

DNS filtering rules for selected LINE services and content.

## Filters

- [line.txt](line.txt): LINE ads, VOOM, NEWS, OpenChat, and selected analytics endpoints.

## Usage

1. Open `line.txt` on GitHub and copy its **Raw** URL.
2. In AdGuard Pro, open **DNS protection → DNS filtering → DNS filters**.
3. Add the URL and enable the filter and DNS protection.

Use the **AdGuard** DNS implementation for local filtering. These rules can also be used with AdGuard Home and compatible DNS filters.

## Limitations

DNS filtering blocks domains, not individual page elements. Some content may remain, and shared domains may affect other LINE features.

If a feature stops working, disable this filter and check the DNS request log.

This is not an official LINE or AdGuard filter.

## License

Copyright (C) 2026 adguard-dns-filters contributors.

Licensed under [GNU GPL v3.0](LICENSE) (`GPL-3.0-only`). Provided without warranty. Upstream rules remain attributed to their respective contributors.

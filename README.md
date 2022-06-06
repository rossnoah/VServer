
# This is a fork
## VServer is pufferfish fork for Vanilla+ a semi-anarchy, semi-vanilla server
[website]: https://vanillaplus.net
[vdiscord]: https://vanillaplus.net/discord

[Website][website] - [Discord][vdiscord] - IP: `play.vanillaplus.net`



Current Modifications:

- [suffocation]: https://github.com/pufferfish-gg/Pufferfish/blob/ver/1.17/patches/server/0008-Optimize-suffocation.patch
Removed a pufferfish [suffocation patch][suffocation]

- [kb]: https://github.com/VanillaPlusMC/VServer/blob/ver/1.17/patches/server/0010-Fixed-Netherite-KB.patch
Fixed netherite knockback randomization [patch][kb]


------------------------------------------------------------------------------------------------------------------------------------

[home]: https://pufferfish.host
[knowledgebase]: https://docs.pufferfish.host
[discord]: https://discord.gg/reZw4vQV9H
[downloads]: https://ci.pufferfish.host/job/Pufferfish

# Pufferfish
A highly optimized Paper/Airplane fork designed for large servers requiring both maximum performance, stability, and "enterprise" features.

[Homepage][home] - [Downloads][downloads] - [Discord][discord] - [Knowledgebase][knowledgebase]

## Features

- **Sentry Integration** Easily track all errors coming from your server in excruciating detail
- **Better Entity Performance** Reduces the performance impact of entities by skipping useless work and making barely-noticeable changes
- **Partial Asynchronous Processing** Partially offloads some heavy work to other threads where possible without sacraficing stability
- Complete compatibility with any plugin compatible with Paper
- And more coming soon...

## Downloads
You can download the latest JAR file [here][downloads].

## Pufferfish Host

Are you looking for a server hosting provider to take your server's performance to the next level? Check out [Pufferfish Host][home]! We run only the best hardware so you can be sure that your server's hardware isn't bogging you down.
This fork is developed by [Pufferfish Host][home], and we can provide additional tailored performance support to customers.

## Building

```bash
./gradlew build
```

Or building a Paperclip JAR for distribution:

```bash
./gradlew paperclip
```

## License
Patches are licensed under GPL-3.0.  
All other files are licensed under MIT.

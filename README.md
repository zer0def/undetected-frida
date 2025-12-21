# Undetected Frida for Android

This repo follows [FRIDA](https://github.com/frida/frida) upstream, auto-publishing the same version with some extra anti-detection patches applied.
Releases right next door, on the side panel →

## State of the repository

This repo holds a set of community-developed patches geared towards symptomatically attempting to make Frida barely less detectable by applications having lame counter-measures towards it, which I have tried to maintain as part of a hobby.

Due to the amount of users incapable of distinguishing (or even passingly considering) whether bugs are caused by patches from this repository, upstream or themselves "just holding it wrong", the issue tracker is closed, as I ultimately hold no interest in repeatedly attempting to tell people how to correctly debug their issues or donating any form of support to this.

Unless clearly stipulated otherwise elsewhere in ironclad legal writing applicable in the recepient's resident jurisdiction, the reader is never entitled to anyone else's time and effort other than their own, regardless of potential involvement of in-kind contribution. The fact this needs to be explicitly spelled out speaks for itself.

However, constructive feedback is taken via pull request.

With that said, one should never consider symptomatic substring-based detection or evasion as an exhaustive (or even definitive) measure.

## Patches

|patchset|module|name|
|-|-|-|
|strongR-frida|frida-core|0001-string_frida_rpc.patch|
|strongR-frida|frida-core|0002-io_re_frida_server.patch|
|strongR-frida|frida-core|0003-pipe_linjector.patch|
|strongR-frida|frida-core|0004-io_frida_agent_so.patch|
|strongR-frida|frida-core|0005-symbol_frida_agent_main.patch|
|strongR-frida|frida-core|0006-anti-anti-frida.py.patch|
|strongR-frida|frida-core|0007-threads.patch|
|strongR-frida|frida-core|0008-protocol_unexpected_command.patch|
|strongR-frida|frida-core|0009-memory_str.patch|
|florida|frida-core|0001-Florida-memfd-name-jit-cache.patch|
|florida|frida-core|0002-Florida-pool-frida.patch|
|florida|frida-gum|0001-Florida-pool-frida.patch|

## References

- [https://github.com/feicong/strong-frida](https://github.com/feicong/strong-frida)
- [https://github.com/qtfreet00/AntiFrida](https://github.com/qtfreet00/AntiFrida)
- [https://t.zsxq.com/miIunQN](https://t.zsxq.com/miIunQN)
- [https://github.com/darvincisec/DetectFrida](https://github.com/darvincisec/DetectFrida)
- [https://github.com/b-mueller/frida-detection-demo](https://github.com/b-mueller/frida-detection-demo)
- [https://bbs.kanxue.com/thread-276111.htm](https://bbs.kanxue.com/thread-276111.htm)
- [https://github.com/CrackerCat/strongR-frida-android](https://github.com/CrackerCat/strongR-frida-android)
- [https://github.com/hzzheyang/strongR-frida-android](https://github.com/hzzheyang/strongR-frida-android)
- [https://github.com/AeonLucid/MagiskFrida](https://github.com/AeonLucid/MagiskFrida)
- [https://github.com/Ylarod/Florida](https://github.com/Ylarod/Florida)
- [https://github.com/thau0x01/frida-patches](https://github.com/thau0x01/frida-patches)
- [https://github.com/soyasoya5/strongR-frida-patches](https://github.com/soyasoya5/strongR-frida-patches/tree/il2cpp_bridge_embed)
- [https://github.com/Exo1i/MagiskHluda](https://github.com/Exo1i/MagiskHluda)

## Thanks

- [@feicong](https://github.com/feicong)
- [@r0ysue](https://github.com/r0ysue)
- [@hellodword](https://github.com/hellodword)
- [@qtfreet00](https://github.com/qtfreet00)
- [@hzzheyang](https://github.com/hzzheyang)
- [@CrackerCat](https://github.com/CrackerCat)
- [@AeonLucid](https://github.com/AeonLucid)
- [@Ylarod](https://github.com/Ylarod)
- [@thau0x01](https://github.com/thau0x01)
- [@Chensem](https://github.com/Chensem)
- [@soyasoya5](https://github.com/soyasoya5)
- [@Exo1i](https://github.com/Exo1i)
- [@lico-n](https://github.com/lico-n)
- [@Thiasap](https://github.com/Thiasap)
- [@Rycoh99](https://github.com/Rycoh99)
- [@elliott-wen](https://github.com/elliott-wen)

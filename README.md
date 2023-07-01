# Undetected Frida for Android

This repo follows [FRIDA](https://github.com/frida/frida) upstream, auto-publishing the same version with some extra anti-detection patches applied.
Releases right next door, on the side panel →

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
- [https://github.com/Ylarod/Florida](https://github.com/Ylarod/Florida)

## Thanks

- [@feicong](https://github.com/feicong)
- [@r0ysue](https://github.com/r0ysue)
- [@hellodword](https://github.com/hellodword)
- [@qtfreet00](https://github.com/qtfreet00)
- [@hzzheyang](https://github.com/hzzheyang)
- [@CrackerCat](https://github.com/CrackerCat)

# [OpenWrt-Rpi](https://github.com/SuLingGG/OpenWrt-Rpi)

## Project Introduction

1. Provide OpenWrt firmware sutable for all Raspberry Pi seires, Rockchip platform, ipq400xx platform and x86 platform devices
2. Contains rich OpenWrt original LuCI plugins and community LuCI plugins
3. The firmware is automcally compiled following the source code update to ensure the latest experience
4. Pre-configured local kmod repositories to avoid kmod dependency conflicts
5. Integrate most wired, wireless, 3G/4G network card drivers without additional installation
6. Preset the latest version of Clash core and oh-my-zsh to minimize configuration costs
7. Provides full format firmware/files (ext4/squashgs/ubi/initramfs/rootfs)
8. For advanced users, a full firmware/package build tool (imagebuilder/sdk/toolchain) is provided
9. If you want to donate to this project, please go to [FUNDING.md](https://github.com/SuLingGG/OpenWrt-Mini/blob/main/FUNDING.md)

## Documentation

For information on firmware download and installation/initial setup/package installation instructions, please refer to the ducumentation:

<https://doc.openwrt.cc/2-OpenWrt-Rpi>

## Firmware Previes

### Main Interface:

![主界面](https://ae05.alicdn.com/kf/H6814822fa93d4246837bea1edcec6d23j.png)

### Built-in Features:

(It is recomended to save it locally to zoom in)

![内置功能](https://ae02.alicdn.com/kf/Hf29f2d94339d4188bbdde7f3131b500af.png)

## Thanks

Thanks to the following projects/vendors:

| Github Actions                                        | OpenWrt source code project                                             | OpenWrt build project                                             | Action item                                                  | Cloud service providers                               |
| ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------- |
| [Github Actions](https://github.com/features/actions) | [openwrt/openwrt](https://github.com/openwrt/openwrt/)       | [openwrt/buildbot](https://git.openwrt.org/?p=buildbot.git;a=summary) | [ncipollo/release-action](https://github.com/ncipollo/release-action) | [Acloud](https://acloud.net/)            |
|                                                       | [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)    | [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt) | [mknejp/delete-release-assets](https://github.com/mknejp/delete-release-assets) | [Cloudflare](https://www.cloudflare.com) |
|                                                       | [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt) | [immortalwrt/opde](https://github.com/immortalwrt/opde)      | [GitRML/delete-workflow-runs](https://github.com/GitRML/delete-workflow-runs) | [BackBlaze](https://www.backblaze.com/)  |
|                                                       |                                                              | [aparcar/openwrt](https://github.com/aparcar/openwrt)        | [easingthemes/ssh-deploy](https://github.com/easingthemes/ssh-deploy) | [HostHatch](https://hosthatch.com/)      |
|                                                       |                                                              | [klever1988/nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt) | [easimon/maximize-build-space](https://github.com/easimon/maximize-build-space) |                                          |


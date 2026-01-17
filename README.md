> [!IMPORTANT]
> This repository has been superseded by [aviutl2_community_translation](https://github.com/aviutl2/aviutl2_community_translation). Please use or contributed to it instead!

# aviutl2-EN

Edit of the English translation of AviUtl2 for better readability &amp; clarity

## How to install

1. Download raw file of `English [Edit].aul2` for your AviUtl2 version from the repository
2. Place in `C:\ProgramData\aviutl2\Language`
3. Open AviUtl2
4. Navigate to `Setting` > `Language`, Open dropdown and select `English [Edit]`

> [!NOTE]
> File name may differ depending on versioning.
> 
> Some text may not fit in the boxes, so please download `style.conf` and place it in `C:\ProgramData\aviutl2`.
> It changes the wideness of the buttons with text in the `Object Settings` window from `96` to `120`.

## FAQ (General Software Usage)

### Why can I import .JPGs, but not .JPEGs?

For whatever reason, .JPEG isn't included in the default import settings.
You can add it by going to `Settings` > `Input Plugin`, then selecting the `File Extension` field next to WIC image file reader. If you're adding it to the end of the line, type `,jpeg`.

### How do I import other formats like .MOV?

For that, you'll need to download a plugin. 

- [L-SMASH-Works-Auto-Builds](https://github.com/Mr-Ojii/L-SMASH-Works-Auto-Builds) (Most up-to-date)
- [DirectShow File Reader Plugin for AviUtl](http://videoinfo.tenchi.ne.jp/?DirectShow%20File%20Reader%20%A5%D7%A5%E9%A5%B0%A5%A4%A5%F3%20for%20AviUtl)
- [MFVideoReader](https://github.com/amate/MFVideoReader)

### How do I export other formats like .MP4?

For that, you'll also need to download a plugin.

#### Hardware Encoders

- [NVEnc](https://github.com/rigaya/NVEnc) (NVIDIA GPU, Video)
- [VCEEnc](https://github.com/rigaya/VCEEnc) (AMD GPU, Video)
- [QSVEnc](https://github.com/rigaya/QSVEnc) (Intel CPU, Video)

#### Software Encoders

- [MP4 Exporter](https://apps.esugo.net/aviutl2-mp4exporter/)
- [x265guiEx](https://github.com/rigaya/x265guiEx)
- [x264guiEx](https://github.com/rigaya/x264guiEx)
- [ffmpegOut](https://github.com/rigaya/ffmpegOut)
- [al2_wav_saver](https://github.com/hebiiro/al2_wav_saver)

### How do I install Third-Party scripts?

#### Installing Thrid-Party scripts

1. Open Aviutl2
2. `Misc` > `Application Data` > `Script Folder`
3. Restart Aviutl2

#### Supported Scripts

- [azurite](https://github.com/azurite581)
  - [ColorHalftone](https://github.com/azurite581/AviUtl2-ColorHalftone)
  - [GradientPlus](https://github.com/azurite581/AviUtl2-GradientPlus)
- [Satsuki](https://bowlroll.net/user/290)
  - [ANM1](https://bowlroll.net/file/3777)
  - [ANM_ssd](https://bowlroll.net/file/3777)
- [sigma_axis](https://github.com/sigma-axis)
  - [AutoClipping_S](https://github.com/sigma-axis/aviutl2_script_AutoClipping_S)
  - [GroundShadow2_S](https://github.com/sigma-axis/aviutl2_script_GroundShadow2_S)
  - [PenroseTile_S](https://github.com/sigma-axis/aviutl2_script_PenroseTile_S)
  - [PageRoll_S](https://github.com/sigma-axis/aviutl2_script_PageRoll_S)
  - [PixelSnap_S](https://github.com/sigma-axis/aviutl2_script_PixelSnap_S)
  - [Resize_S](https://github.com/sigma-axis/aviutl2_script_Resize_S)
- [Korarei](https://github.com/korarei)
  - [ObjectMotionBlur_K](https://github.com/korarei/AviUtl2_ObjectMotionBlur_LK_Script)
- [TootieJin](https://github.com/TootieJin)
  - [TootieJin's pjsekai-overlay-APPEND](https://github.com/TootieJin/pjsekai-overlay-APPEND)

## Links

- [AviUtl Room](http://spring-fragrance.mints.ne.jp/aviutl/) (Official Homepage)
- [@wiki](https://w.atwiki.jp/aviutlexedit2/) (Japanese Wiki)
- [AviUtl2 Plugin/Script Directory](https://lineside0418.github.io/AviUtl2_Plugins)

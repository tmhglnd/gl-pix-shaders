# gl-pix-shaders

**Please consider to download and donate via http://gumroad.com/tmhglnd**

**or become a patron on http://patreon.com/timohoogland**

---

## About

A small package of various pixel shaders for processing textures in the Jitter OpenGL world. The abstractions give quick access to disable/enabling of the shaders, and setting parameters through lists of values or single values in inlets. The comments on the inlet explain the parameters.

## Contains

- **pix.technicolor1** - *A technicolor shader - results in a orange/brown tint*

- **pix.technicolor2** - *A technicolor shader - results in a white/purple tint*

- **pix.technicolor3** - *A technicolor shader - results in a red/yellow tint*

- **pix.brcosa** - *Adjust brightness, contrast and saturation of a texture*

- **pix.saturation** - *Adjust saturation of a texture*

- **pix.frame** - *Add a border surrounding the texture, adjust border width and color*

- **pix.noise** - *Add gpu noise to an image, adjust threshold, smoothing and add/subtraction from texture*

## Sources

Technicolor pixel shaders ported from the original GLSL shaders by vade
http://001.vade.info

GPU Noise algorithm based on http://byteblacksmith.com/improvements-to-the-canonical-one-liner-glsl-rand-for-opengl-es-2-0/

## Install

Download zip
```
1. download zip
2. unzip and place in Max Searchpath (eg. MacOS ~/Documents/Max 8/Library)
3. restart Max8
```
Git clone
```
1. $ cd ~/Documents/Max\ 8/Library
2. $ git clone https://github.com/tmhglnd/gl-pix-shaders.git
3. restart Max8
```
```
4. Open _pix.help-patcher.maxpat
```
## License

The software is licensed under:
The MIT License

# J-PBR

![portal](https://user-images.githubusercontent.com/29577441/184710281-c364fb7a-bec7-4b99-8a75-04e17ddc27f6.png)

## Compliance/Faithful Addon
J-PBR is a Physically-Based-Rendering pack addon intended for use with Compliance/Faithful 32x. It includes Normal Maps, Parallax Occlusion Maps, Glossiness, Metalness, and Emissiveness for most blocks some entities/items. It does not include most of the actual base textures, so make sure to download Faithful and load this pack on top of it. You can download Faithful 32x [here](https://faithfulpack.net/faithful32x/latest).

## Material Standard:
J-PBR uses the old-school PBR standard set by classic SEUS. I personally recommend Complementary Shaders for use with this pack. J-PBR is not intended for use with custom 3D models, but can probably work with simple 3D addons if you disable Parallax Occlusion Mapping.

Keep in mind that I'm 100% self taught through trial and error and looking at other packs. This is the first pack I have ever released to the public, and I'm still learning the technical standards and best practices.

I do understand that labPBR is overall a more robust and complete standard than SEUS' format, but I'm still in the process of teaching myself how to use it, and my preferred shaderpack doesn't support its most interesting unique features anyway. I may recreate this addon using the full potential of labPBR at some point in the future, but I believe what's here works well enough to release. 

There is quite a bit of overlap between the old-school SEUS standard and the labPBR standard, so this pack may look presentable even using a shader that only supports labPBR. However, you may see some strange artifacts depending on the implementation of the standard and what aspects of it are enabled in the shader settings.

For best results, make sure Parallax Depth is set to 15 cm. This is the default setting in Complementary.

# Soqueroeu TV Backgrounds
<h2>What is SOQUEREU - Mega Bezel TV Backgrounds?</h2>
<p>My TV backgrounds are meant to be used with Retroarch. They are not conventional screen overlays: included presets automatically load configurations for Mega Bezel Reflection shader to obtain maximum retro-feeling. In fact, they are designed to work as an addon to the shader and cannot be used standalone like standard overlays as they don&rsquo;t have any trasparent region for tube.</p>
<h2>Why?</h2>
<p>My idea is to develop special backgrounds to be used while playing close to big screens. Taking inspiration from other designers projects, I started creating my own backgrounds in Photoshop featuring simple TV images. They are intended to as little space for the image tube as possible, bringing comfort for those who play close to big screens.</p>
<p>Users may find several spots to improve my work, after all I&rsquo;m still tranining my skill with graphical tools! Btw, I tried to develop a wide variation of colors and shapes, so they wouldn&rsquo;t result repetitive. I hope people will enjoy playing games and customizing their experience with my assets.</p>
<h2>What is Mega Bezel Reflection Shader?</h2>
<p>This is a collection of special shaders with lots of customization possibilities, as well as beautiful real-time tube reflections! They were developed by <a href="https://forums.libretro.com/u/hyperspacemadness/summary">HyperSpaceMadness</a>, with feedback from many people who like old games. In my opinion, this is one of the biggest contributions to the retrogaming emulation scene.</p>
<h2>Requirements</h2>
<ul>
<li>Retroarch 1.9.8 or later with simple presets enabled</li>
<li>Slang shaders previously installed in your Retroarch (download from Retroarch&rsquo;s update menu).</li>
<li>Shader Mega Bezel pack V 0.9.097 (2022-01-05 Rev 2) or later</li>
</ul>
<h2>Features</h2>
<ul>
<li>All backgrouns 16:9 @ 3840x2160 (4K) png format</li>
<li>Independent, zero-config presets for night and day experience</li>
<li>No need for additional advanced preset adjustments</li>
</ul>

Some Scrennshots:

![](/Screenshots/FDS_Akumajou_Dracula.png?raw=true)
![](/Screenshots/SNES_Super_MarioWorld.png?raw=true)
![](/Screenshots/SegaGenesis_Castlevania.png?raw=true)


To see more about Mega Bezel Shader, please visit  [MegaBezel Libretro page.](https://forums.libretro.com/t/hsm-mega-bezel-reflection-shader-feedback-and-updates/25512/1)

  ---------------
<h2>How to use these backgrounds?</h2>
<p>This guide assumes that you already use Mega Bezel shaders. It means you must have the Mega Bezel shader pack previously installed. If you haven't used these special shaders yet, look for additional information further down in this document for first-time instructions. 

These backgrouns are in 16:9 @ 3840x2160 format. Presets will always use the Standard version of Mega Bezel. Please note, there are no presets with Advanced parameter in this package.
Shader presets use relative path. You can then unzip this pack to any folder from the Retroarch root folder if you wish. If you choose a location other than this guide, consider the locations you determine to find shader presets. </p>

<p>1 - Inside the downloaded .zip you will see a folder called Soqueroeu-TV-Backgrounds_V2.0. Unzip this folder to 

*Retroarch/shaders/* </p>


<p>2 - When a game is running, load a shader preset. Find presets in one of these directories:

*Retroarch/shaders/Soqueroeu-TV-Backgrounds/presets/TV-Console* </p>
*Retroarch/shaders/Soqueroeu-TV-Backgrounds/presets/TV-Console-Night*</p>

-----------------------------------
<h2>Beginning Users</h2>
<p>If this is your first use of Mega Bezel shaders, here are the complete instructions:

**1** - You must have Retroarch 1.9.8 or later (you will not be able to load in previous versions)

**2** - You will need Slang shaders previously installed in your Retroarch. Download them from Retroarch's update menu.</p>
<p><strong>NOTE</strong>: You will only be able to see the Slang Shaders in the Retroarch download list if video drivers is set to Vulkan. It may be necessary to save changes and restart your Retroarch.</p>

**3** - You will need Shader Mega Bezel pack. Find the links on the [**MegaBezel Libretro page**](https://forums.libretro.com/t/hsm-mega-bezel-reflection-shader-feedback-and-updates/25512/1)

**4** - If you have previous versions of Mega Bezel installed, you need to delete the old shader pack. Do not overwrite files, this can cause crashes.</p>

**5** - After downloading Mega Bezel pack, see inside the .zip there is a folder called bezel. Copy this folder into the following directory: *Retroarch/shaders/shaders_slang*.</p>

**6** - After downloading the TV Backgrounds pack, inside the .zip you will see a folder called Soqueroeu-TV-Backgrounds_V2.0. Unzip this folder to: Retroarch/shaders/</p>

**7** - Open Retroarch and go to driver options (Settings&gt;Driver&gt;Video). Set the video driver to Vulkan. It also works with GLCore, but seems to be faster with Vulkan.</p>

**8** - Still in Retroach, go to Settings&gt;Video&gt;Scale. Set integer value scale to OFF Set the screen aspect ratio to match your monitor, for example 16: 9.</p>

**9** - With a game running, load a shader preset. Find presets in one of these directories:</p>
*/Retroarch/shaders/Soqueroeu-TV-Backgrounds/presets/TV-Console*</p>
*/Retroarch/shaders/Soqueroeu-TV-Backgrounds/presets/TV-Console-Nigh*t</p>

<p><strong>Note</strong>: A shader preset can take between 5 and 10 seconds to load. On first use, small stutters may occur when navigating through the parameter menus. The loading time can also be a little longer. This happens because the shader is caching the changes. Wait and trust!</p>

**10** - If any background appears upside down, access the shader parameters and modify the Flip Viewport Vertical option, in the [FLIP & ROTATE] section.</p>

**11** - If you want to change shader parameters, you should know that MegaBezel offers several customization options. Once you have desired result, you can save preset to Core (active core), content directory or whole system. I recommend you save by applying to platform/console folder contents, as each system operates with different display resolutions and a customization may present unwanted results for some other core.</p><p><strong>IMPORTANT</strong>: When saving a preset, make sure you have the Simple Presets feature set to ON. This will save a preset that has a reference to the preset you loaded, along with any parameter changes you made. This is what will keep your presets loading correctly when the shader is updated in the future.</p> 

<p><strong>Have a good time!</strong></p>

----------------------------

<p><strong>AGREEMENT</strong></p>
This pack is free. You should not pay for anything related to this graphics pack and shader preset.
You may distribute and reproduce part from this content, as long as you give credit to the authors involved.
You may not profit from the sale of products that contain material in this package without the author's prior permission. 

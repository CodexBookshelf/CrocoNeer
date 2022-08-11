<img src="https://github.com/CodexBookshelf/CrocoNeer/blob/main/newBanner_%23rect807.png?raw=true">
<h2>by Codex Bookshelf</h2>
<a href="#about"><p>About</p></a>
<a href="#tutorials"><p>Tutorials</p></a>
<a href="#contribute"><p>How to contribute</p></a>
<div id="about"><h3>A free library of prefabs for <a href="https://prominent.itch.io/crocotile3d" target="_blank">Crocotile3D</a>!</h3>
<p>This was made to accelerate modelling scenes for the <strong>Crocojams</strong> or general <strong>Crocotile projects</strong>. It has a CC0 license after alpha 10 and a CCBY license prior to that (as long as you indicate the license for this work in your license there's no problem).<br> 
    </p>
<p><em>
    </em></p>
<p>There's a total of 54 <em>"architectonic"</em> <strong>prefabs</strong> (more to be added in the future)&nbsp; to be done in 5 resolutions of pixels:&nbsp; 8x8 (COMPLETED), 16x16 (in process), 32x32 (in process), 64x64, 128x128.<br></p>
<p>We now have <strong>collision shapes</strong> that match the base meshes (i.e. you can export "object" and "object_col" to your Godot project and have an automatic collision shape for your model with only the faces the mesh needs).<br></p>
    <p>This project can also be found on <a href="https://codexbookshelf.itch.io/croconeer">itchio</a> (better for users that don't know how to use GitHub)</p>
</div>
<div id="tutorials"><p>If you don't know how to use prefabs or how to change the textures, follow this tutorial:<br><br></p>
<p>ENGLISH</p>
<div class="video-container"><a href="https://www.youtube.com/watch?v=MkglCYeM8dc"><img src="https://img.youtube.com/vi/MkglCYeM8dc/0.jpg" target="_blank"></a></div>

<p><em><br></em>PORTUGUÊS</p>
<p></p>
<div class="video-container"><a href="https://www.youtube.com/watch?v=CFtqi5-RNxs"><img src="https://img.youtube.com/vi/CFtqi5-RNxs/0.jpg" target="_blank"></a>
<p></p>
<p></p>
<p><em><em></em><em><em><em><em>If you have any suggestion or question you can contact me on the official <a href="https://discord.gg/bfAmdGX7tH" target="_blank">Crocotile3D Discord server</a>.</em></em></em></em><br><em><em><em><br></em></em></em></em></p>
<p><em><br></em></p><div>
<div id="contribute">
    <h2>How to contribute</h2>
    <p>If you have any contribution to the models please follow this standardization rules:</p>
    <ul>
    <li>use the "collisions.png" for making collision shapes and the "primitives8_16_32_64_128.png" for making prefabs (they are in the baseMeshes folder)</li>
    <li>follow the size (or try to match in terms of pixels and size) of each base (8x8, 16x16, 32x32, 64x64, 128x128)</li>
    <li>create objects names like this: name[letter, 1st = nothing, 2nd = B, 3rd = C...][base, 8, 16, 32, 64 or 128][if it's a collision: _col]<br>
    examples: "door32" (1st door, base 32x32), "doorE16_col" (5th door, base 16x16, collision shape)</li>
    <li>only export collision shapes equal to it's prefab shape if the geometry can't be simplified.</li>
    <li>maintain the origin point of the objects (prefab + its collison shape) equal to eachother.</li>
    <li>export objects to the right folder: "base8", "base16", "base32", "base64" OR "base128", "prefabs" OR "collisions"</li>
    <ul>
</div>

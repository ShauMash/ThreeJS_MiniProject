CAVE Labs Training week - Project
🚀 Wireframe Wormhole — Three.js Mini Project
Wireframe Wormhole is a 3D interactive experience built with Three.js, where you fly through a glowing wireframe wormhole while shooting laser bolts at floating cubes, with a starfield backdrop and stunning bloom effects.

📦 Project Structure

File	Purpose
script.js	- Main wormhole game: wireframe tunnel, shooting system, stars, post-processing bloom effects, and gameplay loop.
getStarfield.js -	Utility to generate a colorful 3D starfield backdrop.
spline.js -	Defines a curved spline path that shapes the wormhole tunnel.

🧩 Main Features
🌌 Starfield: Randomly placed colorful stars around the tunnel.

🌀 Wormhole: A wireframe tube built along a spline curve path.

🔫 Laser Shooting: Fire laser bolts from the camera crosshair.

🎯 Impact Effects: Lasers hit and destroy floating cubes.

💥 Sound Effects: Laser firing and destruction have accompanying sounds.

💡 Bloom Post-Processing: The wormhole and effects have a glowing bloom.

🎛️ Crosshair HUD: Center crosshairs to aim and shoot at cubes.


🎮 Controls

  Action	                      How
Move Mouse	          Move crosshairs to aim
Left Click	          Fire laser towards the crosshair
Hit Floating Worms	  Destroy worms for your own satisfaction
Window Resize	Scene   dynamically adapts to window size

Note: In the wormhole experience (script.js), the camera automatically moves through the tunnel along the spline. You don't control the movement directly.

📜 How to Run
Clone or Download the project files.

Set up a local server because the project loads local assets like MP3s and textures:

- bash
- Copy
- Edit
- npx http-server .
- or use any extension like "Live Server" if using VSCode.

Navigate to index.html linked to script.js to experience the wormhole game.

Optionally, you can open the script.js scene separately to explore OrbitControls with 3D objects.

🎵 Assets Required
Star texture at ./star.jpg

Sound Effects inside ./sfx/:

- fitz.mp3
- laser-01.mp3
- blarmp.mp3
- splode.mp3

Make sure these assets exist in the correct folder structure relative to your project for the full experience.

✨ Technologies Used
Three.js (WebGL 3D Rendering)

Postprocessing (EffectComposer, UnrealBloomPass)

Procedural geometry (TubeGeometry, EdgesGeometry)

3D math (Vector3, CatmullRomCurve3)

3D sound with AudioListener and Audio

📸 Screenshot
![image](https://github.com/user-attachments/assets/943e9439-1ac9-4548-b94a-49a3ef41d119)


🧠 Author Notes
Designed for quick exploration of raycasting, procedural 3D graphics, collisions, and post-processing in ThreeJS.

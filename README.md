## Project-ideas
New project and research ideas

### 1. Convert rastered bitmap images to vectorized images and back using bezier surfaces, with zero data loss.

##### Current methods:

![image](https://user-images.githubusercontent.com/52484751/169096549-4edf5815-af6b-49fb-ba4f-8df443cbd257.png)

##### Expected project outcome:

![image](https://user-images.githubusercontent.com/52484751/169096161-01f6b1de-21fd-4ba4-9e45-8c1e5f4ebb0f.png)

##### Possible surprising outcome: A new image format

##### Read about: 

1. Adobe Illustrator's gradient meshes
2. B-Splines

### 2. Online collaboration with TexStudio & Git

1. Real-time saving and local hashing of tex files, continuous staging (not committing) and then automatic rebasing as soon as "confirm" ping is requested (or not).
2. [VS-Code live-share](https://visualstudio.microsoft.com/services/live-share/) like feature on TexStudio with live saving in client PCs. 

### 3. Invisibility cloak, real-time

1. Taking inspiration from [such static projects](https://www.linkedin.com/posts/alexsviryda_how-i-built-an-invisibility-cloak-with-ai-activity-7369126549196791809-9MAl?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAACzquSABp2B9JtPRK-rVDg4mWW-QsJiukDs), the proposed invisibility cloak need not have a prior reference image to fill in the HSV values. It will do real-time semantic mapping with object layers based on occlusion.
2. The real-time map is converted into a 3D model using images gathered from mapping keyframes, replacing images having background with more oblique visibility with images having background with more normally-directed visibility.
3. The 3D model is taken as a reference and is used for inpainting with homography, while still building the map and the 3D model.

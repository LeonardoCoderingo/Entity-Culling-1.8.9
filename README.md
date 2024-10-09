# EntityCulling

### Using async path-tracing to skip rendering Block/Entities that are not visible.Minecraft skips rendering things that are behind you, so why is it rendering everything that you still can't see because of a wall in the way? This mod utilizes your other CPU cores/threads to do really quick path-tracing from your camera to all block/-entities to determine rather they are visible or not. During the rendering, the not visible ones will be skipped the same way entities behind you are.

### Dependencies

 - none

### Tested with
 - Sodium
 - Iris
 - Optifine


# voxel-ludei

This is a version of [voxel-client](https://github.com/maxogden/voxel-client) that includes a rendered bundle.js and
points to a static ip address for ws.

Modify the ip address in js/demo.js and run

    browserify -d demo.js>bundle.js

Zip everything up in www. There is already an Archive.js ready for deployment, but it currently does not run in the Android
CocoonJS launcher.

The backend is [voxel-server](https://github.com/maxogden/voxel-server)

BSD LICENSE
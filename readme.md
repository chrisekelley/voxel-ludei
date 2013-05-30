# voxel-ludei

This is a version of [voxel-client](https://github.com/maxogden/voxel-client) that includes a rendered bundle.js and
points to a static ip address for ws.

Modify the ip address in js/demo.js and run

    browserify -d demo.js>bundle.js

The backend is [voxel-server](https://github.com/maxogden/voxel-server)

BSD LICENSE
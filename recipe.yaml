$engine: 3
$onesync: on
name: NexusRP
description: DanskRP, åbenthus

tasks: 
  # Download default DevoNetwork resources
  - action: download_github
    src: https://github.com/servercfg/DevoNetwork/tree/master/server
    ref: master
    subpath: resources
    dest: ./resources

  # Download default server.cfg for FiveM
  - action: download_file
    url: https://github.com/servercfg/DevoNetwork/blob/master/server/server.cfg
    path: ./server.cfg

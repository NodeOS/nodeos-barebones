#!/usr/bin/env node

const manager = require('download-manager')


// Source versions

const INIT_VERSION = "master"


// Source URLs

const INIT_URL = "https://github.com/piranna/nodeos-init/archive/"+INIT_VERSION+".tar.gz"


//
// Download nodeos-init
//

const downloads =
{
  name: 'init',
  url: INIT_URL
}


manager(downloads, {path: 'deps'}, function(error)
{
  if(error)
  {
    console.trace(error)
    process.exit(1)
  }
})

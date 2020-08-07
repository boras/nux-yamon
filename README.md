# nux-yamon

Yamon (Yet Another Monitor) bootloader for Nuxitron board.

Issue "quilt diff" to see the changes done for Nuxitron board over the Yamon source code.

Here's a "quilt files" output:

  arch/env/platform/env_platform.c
  arch/include/initmodules.h
  arch/include/initswitch.h
  
  arch/include/lan_smc911x_ini.h
  
  arch/include/pb1000.h
  
  arch/init/reset_db1200.S
  
  arch/init/reset_nuxitron.S
  
  arch/syscon/platform/syscon_platform.c
  
  bin/link/link_el.xn
  
  bin/makefile
  
  drivers/flash/flash_amd.c
  
  drivers/lan/smc911x.c
  
  drivers/lan/smc911x.h
  
  env/env.c
  
  include/lan_smc911x_api.h
  
  include/sysdev.h
  
  include/sysenv_api.h
  
  init/reset/reset.S

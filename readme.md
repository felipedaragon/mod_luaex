# An apache module to extend mod_lua

mod_luaex is a module for apache2, which extend mod_lua to support socache, session, dbd, filter and other, so more flexible.


## Introduce

   In 2005 year, I begin write a lua modlue(http://mod-lua.sourceforge.net), inspired by mod_python. Some years pass, I glad to see office mod_lua appreas.
 But officer version, not fully function. So I want to write a module which extend office version. mod_luaex not to replace mod_lua, mod_luaex works after active mod_lua.
 Lua/APR is a good apr bind for lua, So I embed Lua/APR in mod_luaex.

   mod_luaex depends on mod_lua, mod_session, mod_socache, mod_socache.
   Target apache version is httpd 2.4

## How to get and install the binding

### Build on Windows with MSVC IDE.
   
   Open build\mod_luaex.vcproj with MSVC 2008 or 2010.

### Build on UNIX using makefile

   Please wait for finished.

### Build on Windows using makefile

  1) change setting in config.win
  2) nmake -f makefile.win

## Status

## Contact

If you have questions, bug reports, suggestions, etc. the author can be contacted at <zhaozg@gmail.com>. 

## License

This software keep same license with apache.

some code steal from [Lua/APR]
Lua/APR is write by 2011 Peter Odding (<peter@peterodding.com>) and a few by zhiguo zhao (<zhaozg@gmail.com>).
[Lua/APR]: http://peterodding.com/code/lua/apr/

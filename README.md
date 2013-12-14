Fibaro-HC2-Toolkit-Framework
============================

This Framework is a lua library for HC2 and is an addon for HC2 Toolkit application in a goal to aid the integration.
Hope that it will be useful!

Current version 1.0.2 [12-13-2013]

Tested on Lua 5.1 with Fibaro HC2 3.572 beta

<b>Informations:</b> Memory is preserved: The code is loaded only the first time in a virtual device main loop and reloaded only if application pool restarded.

Use: Toolkit or Tk shortcut to access Toolkit namespace members.
Example: 
          Toolkit:trace("value is %d", 35); <b>or</b> Tk:trace("value is %d", 35);
          Toolkit.assertArg("argument", arg, "string"); <b>or</b> Tk.assertArg("argument", arg, "string");


Find more information on http://forum.fibaro.com/


Copyright (C) 2013 Jean-Christophe Vermandé

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, orat your option) any later version.
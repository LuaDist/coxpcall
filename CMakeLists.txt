# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( coxpcall NONE )
cmake_minimum_required ( VERSION 2.6 )
include ( dist.cmake )

install_lua_module ( coxpcall src/coxpcall.lua )
install_data ( README )
install_doc ( doc/ )

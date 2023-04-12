# Stop-Antialiasing-for-wz2
This code is a C++ DLL for Warzone 2 that prevents anti-aliasing in the game. The DLL intercepts calls related to the global variable "g_AntialiasingEnabled", with functions blocking or always returning 0. DllMain registers the three functions as callbacks and disables calls to library threads.

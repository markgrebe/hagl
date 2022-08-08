from building import *
import os

cwd = GetCurrentDir()
src = ['src/bitmap.c','src/clip.c','src/fontx.c','src/hagl.c','src/hsl.c','src/rgb565.c','src/rgb888.c','src/tjpgd.c']
CPPPATH = [cwd]
group = DefineGroup('FileSystem', src, depend = [''], CPPPATH = CPPPATH)

Return('group')

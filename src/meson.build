executable(
    'termshort',
    ['Main.c', 'Log.c', 'Utils.c', 'Screenshot.c'],
    install : true,
    c_args: ['-DUNICODE=1','-D_CRT_SECURE_NO_WARNINGS'],
    link_args: ['-lgdi32', '-luser32']
)

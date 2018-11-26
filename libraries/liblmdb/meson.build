liblmdb = library('lmdb', ['mdb.c', 'midl.c'])
lmdb = declare_dependency(
    link_with: liblmdb,
    dependencies: dependency('threads'),
    include_directories: include_directories('.'))

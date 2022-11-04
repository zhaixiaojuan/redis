(1) 共修改了两个文件：
deps/jemalloc/build-aux/config.guess
deps/jemalloc/build-aux/config.sub
这两个文件通过以下命令可获取：
curl -sL -o config.guess 'https://git.savannah.gnu.org/gitweb/?p=config.git;a=blob_plain;f=config.guess;hb=HEAD'
curl -sL -o config.sub 'https://git.savannah.gnu.org/gitweb/?p=config.git;a=blob_plain;f=config.sub;hb=HEAD'

(2) 执行构建敏命令：
make

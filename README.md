# my_toy_compiler
1. It needs to install the llvm 3.5 version using following command:
sudo apt-get install clang-3.5 clang-3.5-doc libclang-common-3.5-dev libclang-3.5-dev libclang1-3.5 libclang1-3.5-dbg libllvm-3.5-ocaml-dev libllvm3.5 libllvm3.5-dbg lldb-3.5 llvm-3.5 llvm-3.5-dev llvm-3.5-doc llvm-3.5-examples llvm-3.5-runtime clang-modernize-3.5 clang-format-3.5 python-clang-3.5 lldb-3.5-dev

2. after installation, you can use following commands to create llvm-config 
alternatives --install /usr/bin/llvm-config  llvm-config  /usr/bin/llvm-config-3.5 

